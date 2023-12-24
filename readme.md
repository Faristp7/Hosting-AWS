# Project Deployment on AWS EC2

This guide provides step-by-step instructions on deploying a Node.js project on an AWS EC2 instance. Whether you're new to AWS or a seasoned developer, this beginner-friendly guide will help you set up your environment and launch your Node.js application.

## Account Creation on AWS

Before you can deploy your Node.js project on AWS EC2, you need an AWS account. Follow these steps to create one:

1. **Visit the AWS Website:**

   - Go to the [AWS homepage](https://aws.amazon.com/).

2. **Click on "Create an AWS Account":**

   - Locate the "Create an AWS Account" button on the top-right corner and click on it.

3. **Enter Your Account Information:**

   - Fill in the required information, including your email address, password, and an AWS account name.

4. **Continue to the Contact Information:**

   - Provide your contact information and continue to the next step.

5. **Payment Information:**

   - Enter your payment information. AWS may ask for a verification charge, which will be refunded.

6. **Complete the Registration:**

   - Review your information, agree to the terms, and click "Create Account and Continue."

7. **Verify Your Identity:**

   - Follow the on-screen instructions to verify your identity. This may include receiving a phone call or text message.

8. **Access the AWS Management Console:**
   - Once your account is set up, you can access the AWS Management Console.

## Next Steps

With your AWS account ready, you can proceed to launch an EC2 instance and deploy your Node.js project. Continue reading the README for detailed instructions on setting up and deploying your application on AWS EC2.

## search EC2 on search bar then select the EC2 instance

Select Launch Instance button

## Select Launch Instance button

- In the EC2 Dashboard, under "Instances" in the left navigation pane, click on "Instances."

- Click the "Launch Instance" button to start the instance creation process.

![Select Launch Instance](https://lh3.googleusercontent.com/pw/ABLVV84nouc5fsXeFn9WwGF1g9jArlw1qxPoQV94ijVNbMC1EWJBB2EdQV7hQ9baaZZ-ZSx18zfYGTDQfYvB6-OqgMsOxjc-S154ppmFtGly4ShF1Pm2qDlveDupQ5fd4kR3zwVbuXEU01wjm8o3Nwbf0NzW-AJWyWrEKCSjIrMZgozicfg5aaSXyikmKYvKIaBTOuEDvxhzXF4aHj2p52RvOblH_yhaOdnmR32sX1u_HB34Bf1kJX4sMnTtqc-6I_4wmpS5wotll6T9At6dNrg_qaeNMF1ZyCTigFen7zg7lpsIB4OY4vN7QBFInTsZWPqzY-wyAWxhEr9uXsX8sJKZERUDaSfWbNMgD2fmMkAppMbH2lXrdYSPeYMnXNTuDifrKPwJuzqOKAjH44jTPa6LV9B9W_frS_ixxl-HMqMekVzf_39tM77DZ3aoPKhj9Rad_FxfYCnE15v1YgWPihZYinhPAWqcgIuw1NHohqjwas2eHh83dviKvwa-XFBDcjdpKwOmEwYI42Xujxc_YGqghvJhPm2oSjO2a8-vwa4CdQuQHDLA-q8mrapCZJyle7yjJbY04ftf8MDcgGYEhTYNYp1PEz8acPHLgMEjESzmBzhWkXO9_TS1NdCxrlUqc9YLO41cmh1EcgWDtLiPVAoH0hCo7akLkRpKf_OV0IQbVOpNe6cuCEvij6VIY6YnpmmYBBSfp2JhNPKGs4_4NvfckmB94p5moLkS6h_YwO8tP__hlIfEGI0sKp6ba6EXN9H8q2Ekl2Pg34ZFsWYpmaKztJArG9b6_Vjj9onQ6TFb01_85Tjunz1eMJpZAlHvdlJsdIh7XOZfIVqtdhVM7H7TL3MdAezeH7fwMrOMPJe8yzQUjfvoEJo0rFMdrGjtoFhFeStUwFfnDCevkvAYE4JonGbyynP1YakMCsCXxOo=w1920-h909-s-no-gm?authuser=1)

- Give Your EC2 Instance a Name

![](https://lh3.googleusercontent.com/pw/ABLVV84ZEEfwABZ4VllDCWa4ksuTKgAwDmMeNkSe8rCBn6nURAEkzPFY9ItMEtbbhoOly9nX8bC7LZnKie16Tokzs4DzLW_ITcUieUcAubB3fhqztCfc8lwWeZ7ixrClhpEI26N9HxN66tUD5h_HA53nFvwvybw4t3Do0-VkPzYSInKUtOSSzqxYROF1SCboN8O7FIxrhemQguhLLb5NuZaKKQpVkQWFl4XeCnxxgXoNnJwJLWqg8MkbPxFPfdTKImtgR6Uv-Ox2msC7O_fmv-0-NmtOgtlP8boP1hfa5kzT70tI47oDvtuIl6d0UnwyLuOx6DNzGg4u2gZjYTr-AjI0CWRnrinnBS5D1u7TOKDrJd-dsRW1KfnUL1nim67yavB2ouVwOGl97kglyaga_-3Trn5vR3TJ7MItvTjZSVaqLipsDSrm1dFIx3cW5lrYIqpeFaCyxp5DzJec3aMlQQaLkcvLL84-jEeadxS2iBft6smWAA9hGu73ZufBkh0s1Tf5nswGAlEyGzRbVVrsIWA1ODJZKyQdwAeQ-mY1UJ-DI6Bsw1__e1P7bmDK8PSgofkTquqLAr0Z2zHVQu8T0IMZp4o9HGTNePtATbjrlAGcHEaxmGER8alTeWqpnQDgN7u4sUevGSoQc32wR-5sE_BWWeuXbvPn_tn9HX4UsRUC1lCsTr3HteFNfqSdzwhB62hkcPJibjYtns8Va-Iz_wRYZilkeI7n8kSJs0LfdgUE__MOsqNt8u6ihcZdngb-R2-N3u8_2VP-nJKs2BCIiXy78X-_ig1lKG1NChXxdbFFtdbpIPl05ogtUfAO5PK-Xg4757XE4bYXRGT11kAg_LonLj9aGr2oUdkEfoAUddu8MZxER_MSml5xC25n7Uqi0oN7NYALQVh4ymo78ueT1ntPANXBi-TR6ZILx4Xi0f8=w959-h456-s-no-gm?authuser=1)

- Select ubuntu

![](https://lh3.googleusercontent.com/pw/ABLVV843SBbiIF1UDgBsbOj_EqcPH0h0xW7klNbrjVgQasJ668YlIVLceqPSDBLawLHRpV3PLFM8lH9I1zJXkVP1vcopTJfMPF3nHqETdK8N33dl-WEE6yacGBOlUp09k4o_p-McEHgxe5lANa0SGaaod2VGhUY_Za2lPcaHY81ueuA-eCIQ8xgXjMXSj0n6zRAcE-6p9i6SQ6AhBR6K_dOC2KFH-gt_AjEghELR84tmzp0ojkBVWdgMYIKb-f1E-5bBQeLapDNrIOH0PSWfLZ6NFOi2dzl0l4cBhVbPEMXwtJbbxPLN01YymtmY3-d5MLoYI6pidYdQSd5AiztZNKystj8Ix1ZaVQ5XC_8oW0Mend7C8zk0xNX2wnusCfe298beg94eT2WSr7td6IPDLAR49nvOAMlEtvraish9m9Zo6nPnIJKDUYVzu1GVc7a4Ngc1_oXdkURwcY_s9K-quULQiPTEOMkcNNTuHijvbjecl7VVnqDbbuenYBwRNq3Veb9hwD87bz6f-el6a2uBGAkHvYsiEfzgYEtXlarbS6SE-c_WIuhWTIewTp1t8h_Z5fBUKOgMlSrPPuByu_WQKDctEv-AGRj-TrgJC26_lKLtC4GJzsTKO3sXY_VOYbFekGTg6vjPzi0vJBcBpmjg2jVLrA8ielyJVd7i52Z0yrLmLiOGWS_-cRAlofygYG873c2Rf9YT-8XwseUj4mze7QgYv4NKz3TBllm6GPVxzzHDqIvUyMbgl53GKTgV8PJxfLuong0xII17cqcL5u6DutNpImwSIuVS43oHUGMYTDnTl78CmnjvdYgJYUjgIuZxEtXwZgWL2PzaoXPVW5VMn81ywcicgAxbtioHT-21pQgv-r5TO6w1p2t6z9DYCear3KHrdijABDvXBxr4PpPe0dAhNMuw6q_XlNmTJF-EglA=w959-h459-s-no-gm?authuser=1)

- Create a pem file wiht key value pair
  It will download a pem file.

![](https://lh3.googleusercontent.com/pw/ABLVV86UGCxThO-9jnOo7iVUG71QYOEaq8-y-91WQTYMNh6v7vIZ2TYqtahFoeGlY42MUNCQdi-Cu0BtCxfu2ZC5jElhRGy4i1MCiixzs9lWAeeZBBkYSd2-MoseiaromhaJySuRaMuMlkHp-vZypWMK5HXCY0nB0jkw1y5Ui4OcfMidTs6MQGvnLTh26OXIDmKAL8pfde1A8orsyqAcg-g8EY3uClat5kMvQALVSf5wmBWK3vE0bJFXQg8ncNywIUfqdbPGOv7MW_R8kiACIVT0FyGuLM5qLJBkTQscFwmqwq3iWLqF0jYXnoLBJQTwWn9MoVVN9EBhSxL0MKAqx74gacbJpSvxtnFpLidnKf8XXLtBweFLlo6DMoLHrc4Q54_GTnpfAGu3e9sfBMSXilOty7L5-6RjavFl5PpxQkvp1IJH7BCu7O_l0WAvnCgFqljf1Dacm1lLzX0l7tiG4_5PnMIBU4DHDYv0yxRt3uXXAOXuN2Fo1i2DhSqGoVfFjwIoUNVLGMvxGYoNfDBJxL3hHqGnt9Tsp5yuDH4WsDNaTVBoNikKF2fkL0SypxKu_TeiOTE3JP0nasRT_eK9B6zUh9H7nyx5KxY18vlWP3AiQqaUtHFMUV16MCP8-9l6Mj3bVrOT1zlNK5dB0YuQSErf0UQ0dfw3ATDP28vrSXqHrgTSgSL3uUOADD539Pw7k3MuJRjqdHqBy90iiffq9FMKvW8BRazNMNzmvQwdJZSGRWAcdrw3lHcJqgTdjTkWYAPGRKNXGXg_xq95mYz7Sn2yjaJBzUZogFvm73yHWl4SC8anXIIpQ-byCyembVCJ6RZ2yUnX5RickXqvPA4OgEr1UJK1vZpUME6S8W89SdruXe6ZKAoVfLI1kXG2Raywsw1U2HoY1DYVBATiR8Hgh_7WzhOV6ZMphfatSU86S9s=w959-h458-s-no-gm?authuser=1)

- Make sure checked 3 boxes

![](https://lh3.googleusercontent.com/pw/ABLVV878TbdJCuLF352GvafMdN53EsFKLROPeG_1qvXhAr9c_lTtR5X9NaKFoBit_h5_GJTivXge_zMHZ28_O87BDIFcmy4HRd0rQpb8Nc4M2-szOsVAd1cOfNZSC_3n--aNu0f2sg9K_MdxvviMEL6MyRzwrQTxB2_iWeuPWn-a7J91bDc-errlI6mSauxpFjxvE17jD03B3qxhvcvmjiMtEDH0c5ReY6bwHRtgskpDjxH2z5pd3HFudb0YDZAo8E5bPGvJJ6Zr8lXu7CsZJJ-SSZVpioXYA_ybgNF9ikvAE4x4vGtfcN8sRMFsOoB1dSTadb2ARXzKQI5aLUv6nTJjw-MweF6YVxmKsdye0pMhrbMpWzRqKR0nZB2zbuhiP3treLzPCor-X1XwSAreX-BqGevWIEPAl7xI08BhG6DG2FfXhby2aQpM0h4Gt-JcYrn5J7qPa3a5oTi3qGYdbbJAN0LUTxz_el6F0SNQxcCxhhOiO0TGF0HsPlKtgUtHY3GeUlF4zYtHDNKB4L_uumvKw_HfMgZ7wqsbCJ3FVnwBalCmcbKPbvzTSKlGupcbj84_GSUHUXIMMvurbTRmZBnu5ci20b7m7VOH19lDE9GgGtzxP5vOaPA1iWRmOIIsLmqMNYrvimK-e8pnnGaJw62nFtkucOYqY19lGsPPGzQ_6qcBIKa_ZjZ17uIxOM9_QX0yKJhmG4eXznWTw4d_cFaMcMut-l-p-yxHDodk3ETtZ_MtQxZSXDahr6mDxj5MvXL9iDCLj29rRqxlzgKM8sg-_u4dArpM0mN2x6F2nwQ6_Ex-Mk3Ptuux4J-4VdVxaTvowZhmrR5uzDGndw5U5SKfNTO6Bz4VnXz3GYN2r9mMPXtz1aQOYEXPpCf1v_cF_a6CynouRTWpdawt3R8SDRXNh4PHxsChu6DC9q1iSLI=w959-h455-s-no-gm?authuser=1)

## Click Launch Instance button on right side

- click view all instances on right side

## Boot Ubuntu System

Click the preview to the video:

[![Launching EC2 Instance](https://lh3.googleusercontent.com/pw/ABLVV84A7sCIXYlCepYqUALWoxohj-WeFYPl6-MzyAoH8S3gIllthptZDbotvFg5hyMHYTv_0Slajh8u92_yQizlWq9dL-X_5Mr-fIl8oVhfFJ0NaeRIPHtaQDNv_pJR_xdkxej8wSJ-iPmCFbmWcgRawvmZ0f_GMK3mzQiXMjNfVY8mhXD5ifh5JeSe-sUw4zFFTOTlZzx81YuCVjjRpRdd2ABG-Wv8TPIy-YfJ_EAXONZU-krq-aOP7NDflAjrtod2JmJV4AvfRA7RANUwutF6HlIeHCgGN_5K5LkujPdUaLltIibonWtEf14Keo-gG6iKPrhQp6NxFy_1cadqINwvz1djPdo-n6C6NJyNVQtNtbd_5Qip5M8R6AeTsL4LTabsKuPz0vqRY2_rJdtOr7mc2UnR7_TNzmmW0wx-zOSFrrDI0HZxsl3-07ca7shO7U4SAJvt-iZU7KT7gkLCDsmz_GYMokw16WbHs0wTXOO4Ak6tWIexLKzArAkX_k7JAl5L4-6pXjjbNqmppPYwLnqBuUk4uJCxPt6NYcvyHMB0O9q8rHaWiyA_2-7b1ySaxpIsvYUs268KsMxSpvjhPQLQAAX8TiTRtSLkVkadVx7nZe0NdXBepxAqAo-Qk2yOI8SsgR-PyyE-Gxeyu0km5aDcSwzelgJ9Fv_7qwuUPd2HDJeRRHy-RxEWOcinKig-3gqL9CVU2hGTfRR1gd3F8d38bIKZZqFDhj3t5ZLu_iLhVSlGcCmqewpAZPoM3aUP0_vC3mTitrWXW096AW5z9s7oj9HM5B9eFF53-cEMHloQu8DNYmJmYaCBYQ5gdffdvVoQcSUDR5Xel--H81Pu70cf-SoUq2PpEdBnyM8MZQWYCdAuQ97VEgEmv75fduhogb239ysD5EfHB1MpocFuqewnyU8FNbvcrTUjkmDuAUM=w959-h458-s-k-no-gm?authuser=1)](https://youtu.be/Cg7nU0paWWw)

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
