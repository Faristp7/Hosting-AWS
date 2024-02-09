# Check the documentation for better understanding


https://medium.com/@mrfaristp/deploying-your-web-application-on-aws-ec2-fd339f29e482


# Project Deployment on AWS EC2

This guide provides step-by-step instructions on deploying a Node.js project on an AWS EC2 instance. Whether you're new to AWS or a seasoned developer, this beginner-friendly guide will help you set up your environment and launch your Node.js application.


# Setting Up the Fresh Ubuntu Instance

## 1. Switch to Root User

```bash
sudo su
```

## 2. Update the Package List

```bash
apt update
```

## 3. Upgrade Existing Packages

```bash
apt upgrade -y
```

## 3. Install Node JS

```bash
sudo snap install node --classic
```

## 4. Install nginx

[Nginx](https://nginx.org/) is a powerful and widely used web server and reverse proxy server. It is known for its efficiency, scalability, and low resource usage. Nginx is commonly used to serve static content, act as a reverse proxy, and handle load balancing.

```bash
sudo apt install nginx
```

## 5. Configre nginx

### Open Nginx Configuration File

```bash
nano /etc/nginx/sites-available/default
```

### Clear the Default File and Paste the Configuration

```bash
  server {
        listen 80 default_server;
        listen [::]:80 default_server;

        root /var/www/html;
        index index.html index.htm index.nginx-debian.html;

        server_name _;

        location / {
            proxy_pass http://localhost:3000;
            proxy_set_header Host $host;
            proxy_set_header X-Real-IP $remote_addr;
            proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
            proxy_set_header X-Forwarded-Proto $scheme;
        }
    }
```

### Restart nginx

```
service nginx restart
```

- If any problem occurs check nginx status

```bash
sudo systemctl status nginx
```

## 6. Clone your project from github

- Go to you repository Click the code button below

![](https://lh3.googleusercontent.com/pw/ABLVV87mfVe_OM9qh5UNPjSXoNioMU8EF3uBB_GhYKeITNHvEgaXBcfacPUVxCe0r0AJIQ-yO7ZX5Py_JbqbJcaq-j2PWlKbL7FpvPr6TaBgfYWpazCbPHwzMoiBaovv1RcWJigkpncoDbmenN0UZJNrfKDJowmkqyA62pK16zFmxmmAwSwm-0GreEYv88YS6rFmKfrLtdXUY93FJCjxgNHNlJy5SI5zin4BZb6ralCHDDcNqZzZGf7Z85ozkKyFJge1uuRNSrLBwW1E3QAbiru8Clw-uOHMw1DE9NAI9n0_zh_tguur7vTmxdDMI8n8WL2U9scusclDW9DqqAGWK8QAqZLtc4LEhGshiKuVIfSeJKaQH_KGVSJroFlmfE0fmc1CdF4GWuemwZWaqTmOaZbNNLlVbt2G8XtYwqcwk0RDubo6JdTFtO6KGb--iZkfRskOy_TO8GojspuhsuJIZQULdqAfeapfwpX1rASrkOd5aO9o2SfxPQqH8RJvTaKD4EBJ6Wxt9YBJuA9zFy7Wt5PmAK6wubgtFVcKcPPdTFlQK86AadbGBjfEm8ufwaQxaOGRZq-KowKU9b3cM3kEbyTh4C-PLxLrIyKLl1ZK677V9fCbAtZ6_-bO6eX4wnpcVjBv1uCTp2sJvnYwEg1wvOArPoSrN45Ct_WY2JBLmu61zGO4_Pc445b2bu1NHAjiW6hbB7_OBjW79lxn98_-rZGbG2uBDaR3L3z_FRZcIm29G1mUuwH7Efsip46H53eCSwjXtBXh6xY6WR4QaQ3QybE0sejWfJVYo6_6uCrDqoLY5mY97bXbsUEc1jgHhfSF8MQGbGX3xvUpON_KA6SboaHXuPokbhgJro6WXZo8VGNOzsstbc8QLW0AETNbKeDmt8zdTtL2RRxp5QgbyBlej5cJwBZ-is8jzu24kKmobI0=w959-h465-s-no-gm?authuser=1)

- Copy the HTTPS Link

![](https://lh3.googleusercontent.com/pw/ABLVV860IB4w4RKj915zJjYO6yzUXdNc2IS_lE9DKmIL4LCFE1I7mNS0pdLAvPR06uok2VkFQunSVhcW7_uvMIdCCYSSkrYVcqTn69r6nmbaHs22YWjen51F45T5CaCuT1_rW1N0r0YrdmNpKgf1abM5aWjThS6qb__Myj_FdpbuiCzHXP_BHMNFwHfszU51MvbmQgW1bchkVKKQskwJCIEPZp2F4WZ1vRpznAUwzEl5v6gAI6q3vUIl6tVhPpBjMOFmIRj_SikJsJcDEIl95Bl6MHhZaTaqzyYVrLgmqwhFBVJlQWPj4GW13yvNOuyMTNOBCw95YHjmS8Wm4nCNd7HWpUEhheCGJypGLawiLxnQM7SAnCg4sIz0XSdrhkFKr_4f7Aiy_GVHjNk6YHWugRyLG_hXGINTiUkdUBZtxg-kbwxjU4XmbGEuABlT36D4OcrIPntBLIh3xwzzAKrDMLGCJE7d88_3PFDCAJgkgTPb8RUtjU4t_zw1tOjynQ7udBtYL1gbHUsoNtZJoQm_plfQe-AgnG9GdhN-AOwlkLvFVa84107CAN8RUJgVyAPbATZb3fmKNp7033R6lrnjkwZo-ZsjASDF6_qETmh7AMhL7HaxXD4okP4jnoM7hoLTq9gYoPvf7cM13fvjTOEbVv8b6uQF-aT_Xa43-0FbPSy09qGpd4O4v_Q5srZ4LVJXNpKw2Ex9nwaV6UG-wSsBOjvp4lootaw3OQyyNuIUJ13HSk7lzHTtMpEBTbjNIPrJ5b5V9sEmdPu_DLqI9mk6lhCraVu3wZ1M_CVklRGGbJkD7my5Bm7wqg55K6FvnVI5pv7z70tkC9ZWMmx1ACManFEVAYJLIccGUAGKN5smHD10eRvjE2dEKRUebzVt0FoMvaMf8xR6mH7P-R3w_VgBaXK-llb0HtHnjKKzIVhCA-s=w959-h459-s-no-gm?authuser=1)

- Back to instance

## 7. Clone the repository

```bash
git clone your-repository-link
```

## 8. Setup the project

- Change Directory

```bash
cd
```

- List Directory

```bash
ls
```

### 9.Add env variables

```bash
nano .env
```

Open the .env file for editing using the Nano text editor. Paste your environment variables, and to save changes, press Ctrl + X, then confirm with Y and press Enter.

### Install node modules

```bash
npm install
```

**Notice:** Run your project using the start command example : npm start

## 10. Install pm2 (production-ready process manager)

```bash
npm install pm2 -g
```

- Start your application with PM2:

```bash
pm2 start your-app.js
or
pm2 start your-server.js
```

## 11. SSL certificate (http to https)

1.  First, install PIP

```bash
sudo apt install python3 python3-venv libaugeas0
```

2. Set up a virtual environment

```bash
sudo python3 -m venv /opt/certbot/
```

```bash
sudo /opt/certbot/bin/pip install --upgrade pip
```

3. Install Certbot on NGINX

```bash
sudo /opt/certbot/bin/pip install certbot certbot-nginx
```

4. Create a symlink to ensure Certbot runs

```bash
sudo ln -s /opt/certbot/bin/certbot /usr/bin/certbot
```

5. Choose the best option for your needs.
   Create SSL certs for all domains and configure redirects in the web server

```bash
sudo certbot --nginx
```

```bash
sudo certbot --apache -d example.com -d www.example.com
```

6. Only install SSL certs

```bash
sudo certbot certonly --nginx
```
# Finshed

- If your project has been successfully deployed, feel free to check it out.

[![Instagram](https://img.shields.io/badge/Instagram-faris_tp_-blue)](https://www.instagram.com/faris_tp_/)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Faris%20TP-blue)](https://www.linkedin.com/in/faris-tp/)
