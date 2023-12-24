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

![Select Launch Instance](https://lh3.googleusercontent.com/fife/AGXqzDmS7wgpfMtD5gD3_8U7H-dEuJEpI0NIvGKKpvVG6aY0PlYaw9qXtTAFUUO4lKDcomYAPikyfabiTMrVmYxOWibKwUkuEUY9P9Qshlx79ywqUlAWs5HxSMG_B2bUmFu_XPXO3kLTSvs4reD9HF4vDiParwqCDkqFgo7LPcm49LpWeMMZTTEKePI3vgFnlYs6H3KGyfDBHWg0RgMc1ZGvA-yVvGTcZV6cyzu_mfAhwpCeqcjYehQC5QL9krMKJ4fvfvs6Ua6cvsV8ifXKWO2WzPWb5A9bhf1cK9ry66OX-0dhbtzsR3SP0j36hzgxE17qqCByPhpvTMnvc6bof_gFudObhTY9SSKReA98-QqkA6imJorNeyABepTraY2BvscSAnRKuJhVRa-iLGqjz_VAqw1v85ENIWmKzsfEV2yhZWNpEe_HUea4SGDKYg7gbJvwl__QxFVK3n0l45SW39DuE9JWIUtplcg3QD6g8Or0tLFakahWklzXBd8xO4-7WyFzAjusafsv5_Wa-iyL6Y0nEOfToScnJl_ZudF9K6lw4ekvmokyueF7K7j6CUb-Tv9MM5ks_pOJRljTSHZDqrFKXtzPeo1r1K_8y7T1lU-62t1otn-nRdD0KKJKK96ZCgycIJEmAvi0ZOogRj-5NjMk8q0-4sB9FTEGnVUad8pKOFEGbeFdBMkdMICs8iYgOZI7D1TPMHhL_SRfXRM3tR2Cup2E6d30nQNS3Js3am9f0WxZeCQQ4Zbf5jjqtZQVc1vso1qO9JC7l1_yjLPo5P40GikS7tNtcqxb0m8C1qCopsdBLmrE9NOLZB-8Z0Dy643jH88ZhdGBM0mnzefMPRoYa4oGLTQ92sTJCwCitj4SYAZWN8nidb4L9jVmkmLQesNdSdqIhYDpBcnZKKKCEg4MjOaRutmt5vzuXqS0y2zsbcF70kWm80GVqKVIoJTPmicKgqFm_9zBIMMtsrKHGp1tvdCRTgFC5BjlSLsOGnQdGT61x24IV0mQnx9hlhl8sH33UuHI-ynool9RuPNWm0rpQCPJhkT5ZZ1S7CuQuGdvUT5jl4VKO2aLlusM2H2kAYfLNFoQfjde6kN0qt_VwO4e6KJYO-xgRk21eUoRq5XlRn2hYvfTjEpcK7SnzUhLruMaaD1eTLyCvh9FS-h4_UxMH7h38fuLdUFnAucZUB9-VQ8drZQWneQ4ZIKMGNF5GS5HcP7IX6W0E0FijmRZjCC9YMR3aJtkeLp7Djfld21_-U_FmQ4tkjIBTpxcSpKc4j7Gh8jMd2Dq0yh0lxGqrT6yuWMpbGBDqV_0Zblua_nmzoVduxtSiovSYVAn4duYZWGvQBgaQjaKzvLIFcuuOAAvWWlS7sRmd4mhPIxGu4hA3Tw1omi9BxXE584ZIE4f5wlWJC6UN-vEsb_hO2b52VLjThBZN3gZsIcqApHmhr-Dufbu4PRoYH_T0k8abYGFx21XTXsBDZbp48W4C9uUCwlP2sLUZLouVxbsFzCwadhJlUMF4IAn6_gBNT8QfYF_TF1-sFogdaL5maR4XwA6V4grQWQD3ND67u8ySqGVM7zcg33YZ3rqZj05dQOD_SjrGIfL79k_j0kKxVw1Ksc3CdOtN5qiBLUd-JrFEKbBMJ7M91xTpmk2UIEQLpJObJjtwUjuvhuF_vjz99UN68hAVal77kzBG1_47KhXsVUNBcD59A=s1920-w1920-h909-s-no-gm?authuser=1)

- Give Your EC2 Instance a Name

![Give Your EC2 Instance a Name](https://lh3.googleusercontent.com/fife/AGXqzDkwJBhV25oI1sjvPBH8r0NJprBpxxQpzAAASJhw22t8SOW71KdwuwLrN2ArAlqQkzsZ2YIzbGDZn3Sa6OT8MrZzMrobobD5sCU_hg-Qgt1HooO3TdriTuokv3YMlhBspzjzFPvPiRf-IMGPfo0smosAtRhQrWBPg9GVs2h6VMITBmZP6yvJbAaEmcMfMUcJld_D8lYoiqofm74WyI9n1gdZb5jAuBn5COiZwYq5Z6X_7mSpMeZAub8IEwioK_XrRRY-ox5qLN4EXZ5GL9YwbJf0SLxAr28U_JI9-7ulvEoviUVat4QA1SM1u4GWtpfr-_s3DWVdztJIt5lVH0TvE6Ly--HwQA9354uPbaPrmf1iRkMB5QyC-fKLY6ClSA9Ih7mGwXDk7g_SIz4F8yApVENlttib3fiLbwhVrJ95G--xvg6-jYXUHNHRIbVI9BnmxL8br4RiCdWEfuHuTZ2vCfWnPGBB631p1QrXYEVy97FSA9xpijj4oT74RFsi3wAS6DZvuG0v4_Aronb3NcuuVEHsKlai7tmLJbMvWhG6YxvbODfjIZyjXfLaw4w3MT6kz1P3k4QtPtrobZXJHYEeQ-LhePxLhNVep2ZKUH6hniyLST8ngUCllc2r8rMTgOE3dCrusmggGobPtW6xg86rm8ShsxmStX6ihs1IrZCPIqbVktMj8jdBoTmsoLlItmkbyx_DuEzg8MNkj9IayH-FfIq2Qsxu-uBxk7KvwpvtdBSHhwKOEI3rjzGc9GH5lBprTbHXtI1s8VvHCEMAw5NDTbEPZttRd7w1JDz-NWV3LxQSm9RdM8ncwdbDeKABH_SxqaNtEe0ftG9eWqSk5IXyIPymi0mcjc4b3ELccwKZ6D924njVf03o2DANLqIuEcNMQHau86gwQjzvZnan0pD6DaFbtrD1_xXrcwcDV4ZPJE9x04JV7NdMqWtpS64x7cgwSMXS6MAZeTvzs-sBlMWP7lo7xauaCaKYK4FISMU_616mZokuRqzIjdZiGt3bcsNbD-33lmdcbQVmPr9gwRhYgygzSxWQVU9HjnkjiRAUAwk6op98fQ9KSNPh_HV_FR6nfdI76NgAAWPUuw2APY0SUCHuvbeR-NL4HPZfVbyHTiDN4KSVl3waqQRI8LFVJa2iKih5CClEvsA00FxHsvpRF_X_SvaXBi1xPOxbWMQvMBS6165NV02Mc68ZqXEyD_8WbAq2Yj09MlyEhpkZxzqzzRMZQkKu0WroeZ4U3qe2Q1LdoxQZR1L0sEPych1SupBN0Ixg6HRlV53qR-Bcb8hKMk4KITQCTc3NCivKVGlZqbty01vV5A-WcqrQ4g-I8zHN1jGx84r2hAxFhzz8xuqahD7foFeAseYwc1iFCaJLsIKmjD032-QYmi_d0LU0itZcGWeWbywgk7O3dhHonAjf2U2yBGzmkBPbulMf5Jok9pCAzRUy2cdZBhRlCkS-mIwNN1VBMOajyDgM5yjqXLhNwNCQLRnelnn5hez4g4bZSix13QWunAj7kUKvdT6Vjku1r7EZh_k6KLBIgNv9paF7Dy1DhTfGLnSVDJwtAt0gXUsdmUKi5fjA1uS78L5CH8JRQvBRiC3OOPLawW0chj9_-lShvtI4clstrqDpemzQpSCVlu4ddbTyYTsgBwdzEOlPnAPx8D03NyhdHSzC6SDwbXpZtVrY3zQUlR8GNCEgeg=s959-w959-h456-s-no-gm?authuser=1)

- Select ubuntu

![ubuntu](https://lh3.googleusercontent.com/fife/AGXqzDlE8UrUXpzD7KY_lj3gGP0MlCP_DpkDmtzm6f_HLEBEXkpQxf0TmirdkIyTqI9BQV5FjJUYXvL9BL4HBNIig8-CW5n4QMYlwJp-uIeWgHaMYvBDeGFNWk8f91Wj32qbCB7FzYNoxb6l4EWLCxWVL3LMHObZV_yQWvPwQVPoiSeQ5Fa-e6n-jm47zkutK5Qazz3DLkDyP2IaiVcyB_-NcvN-mxUZMnHSQFSuWzOsJ-FjsBkTCGfGmUCT3VnDQzxwymo7dBKMTillaXPz8u1oHSPkVN96-HAksAW2cw5gy0eiaOjFR55XBxBqQXppJU6Jh3rhp3l8t7wbxydOOg8DqaiErkO3TlUypE8uv5GfQH1gMnsL2cBYQaCxeRtAUVKT9tftpt7OFmY0yJBwZULkH3Afx3XPlAGO-9d2tPTKO448R3PYWj0Wyg2Mf57o8SPuDzXPCl-SciA0vl-82yKwfDqgPTU9J5rsbOJPjylT_R-O7mCUFgpghT7G_zaaGTUzsSlwu4qDVsCXFm8CGUkV2ExKoA_trXrfwNxCvIGMfzIRk7QSFEQ4iM3A4vl3aB3NT7HuNyWwGsHDDHuAyHf04jrynnwOS7sBUmlyAfx7zYKTnYZocEAKhRkAO_MuZyD8DDwWGXSKB63UYE9nEdJNJ21MUkCwQ_fuhJhz_MWP5RSO1UyIPXdIJ4fRdPXHXw4WAfky5dSxlUK2D9UIKyLnYl0ZDYlA20Os9Qn5TB0bMoVujmdMniGNhit9uwCvF7yEnLk47pkw5u8vLn_fVrHbfLiQbHTdXZN2ItrRar2f_rmtK_f8NbBOh7Rn-efi5WvmoFbBMZkEKojI4hxmri-sgVWrPnyh0a7rM99RQosqRj_QJBY7U-DpKLXk8Th_U3JFRdiNH6WoyePi2DpMcBJGQoYU4g7FJUkuwVy-GiGcTx77L5js7851Uvc8cBChCatpmSyDKvCiPTUna5__lvP_1_livpXY0TkIhxBzDg2wnoqFYC-VMtXJ5zFlRQnktM2rs044ycPMw_FDaTRKWNn8IJDJVmkkHlFTaIYq_USz7IG-SaZRqBLMBIL0DMU87Pu0XipWlX7eRJowSlt2VjEyr9WyHTz4GjrVS46qNhj2ljSydLJfH5NayMSbgB5JyQG2QEH8w_Xb4DXHmgy6pVhgUZzj8BfHHFtliMpf61T0WDt869Lsfm4F1aAu6ReNt3gvtExVE1JqNZlYEK8LowkcgZq4gBRtwXVnObuxUqm08zl2CAuMDvpITd80xphq_Flw2bprnzqJZrgSrdHTA30HbQJVRHBjUxIbl-uRCZxX5O8110FbNrQEFX62LL3GYMTLyapxyof5gPgSlJDdC1lpqo-uii0vXHO4_FB0FR6GZxuNqv3u3P1532AdnCAPtAA5_Xqn4o8V166JgXetrqokQqvWoxIlrz9wzv56oicCYevwnH1olT3IA4g5pmbKq3_n5JFRQXvajwtHi97hkF7SFIg53NeDEWAHNMXq0Ar3nVhTJXEFOKqcb2WwadKbULC8WTQ7Nn0JeM4vLHhFLPp15OUuZASwOdPfa26AgL_OrEs8hAhWkipXGWfkizmt2T8kjYiokOMjYAUsiPR06ODz0oLMyk0LBuC4nssxniVH4u3KI6jTFPfZptGgbJ9IWIrzX4pDbLDQYZ3Ocjqtsax6-6s1Ix0OCrJkkv9-5TpU6g=s959-w959-h459-s-no-gm?authuser=1)

- Create a pem file wiht key value pair
  It will download a pem file.

![pem](https://lh3.googleusercontent.com/fife/AGXqzDmb70EJ8tnjgt8cBPPEWMvPr4wLWUgdZltVxR1hMRfOef7p-fqSQHuM8sUCi-Cmy7Nt1FzPDrtSE3j4Rvb3HPF5vEyE0zc2tb0i7f39ffCALpjlhwFTqudrHAZOSgJOipuVENGBuG8pYGzBL0O6fbimm3GmeLOTFr18ONDfTB1PXKMYqSNFwzPVlKBPjcpdl08PPwzVukhOZV1YNC_xpgsRMqhDCcZfXaniFotHV4ocEnd102_v4jrpGsx6Ljd0KY8YmWUVaDKl15AmSXUS2WnuWC3c52GaHxnjX_JluxJn0IeGSQKbi67tZ86n-R13LlX9uATWX6rqdtB5KJm5pVLM4PR0kAPtLh4TjeF64vdxLb0-PtkXoGF-1aaQRips58WkGUZc9EsXyI56tbzn2803VWw0_2kkeZp554ieX688RDOtCg3rVkcau6D4fomyy5-5WR94Y6iUtyXKZo6SwzXX4QAhX8n_b-zHdbfVJ9kBGSbkKWj3iGcbeSe_mHOFRJeueXEOAc6_Cpt4hfAGhHfn7xeiUKMAtaSu3HbtEwaR0vet7mxA0zpq20c3fIq22h933TLW2UKChkeNvfeVyCEE_RZM-PfrqTL7n0l6ofqTiq2uYvomGKrlS7DAwS-irSnEaBXNdyJIEECxhJu6uLqeU9ibBuMKDDAgl16PgaillP9UXLOyCGEm6Y6qKnmGFMFlEyF5FTBhnOkh69o7eHd-l51YPQeL9nrAtMSLZhdtdis9iFL_v5gY0LPqwx4CBmlutUi-tkB2D_YTi56SeXvQUN1uvMM-hQ1e_oUnmjmDaF8Yf9eWXtwNFHvLhqDFjigT3ADXxicniqA-If78BZzdRRKf4YWC2gBRjtjw7LtRmem0tCJPnxgtWjLEA9EMfrlpXabzpbY24jlCYMZlelAxwOLcx8Auzpz80Tgi8e-_0o52y0V5BNMZMq5mARZBvVSalFkRBti-vN2BePBSvifijfjJrS6x8dZleIRgvFmIRygp0TgVVSj8cqjKsI3FPntX4dTJK9xZ3zuBSE3YcbmiUthpb-EBC8tnK41uzpOJ3rbYIHfNCHLWX_4_AfGV-yaUF8kTlqefd6O9BrG2XLddkDQeKiGww-CJud1Nrd7HhvXFiXs-EoGrahMe8P3MY18BL8FBM22a1qszyHYwVcouR3Huo3VwJCpWUsVQ0c5AQ6ds2SrpCUfEzSZY1ZdOvPlnosDygoqiA-JE_5RIjSx128E4aNJ7Zv0PiKeC1mKc7OMqOQlCERiWo6FDY19UNJELoI6QPn5pEa3nEu_P-8dih0z9TOCKZSujGtJhfRaM_i-_UtWXrTdXWTlTAbNomq41HWzDsFZw_CT03Z9k-P3Wg6IKyqVu8-Fa2BXPU_uRWi-QUtbR9DT7CcmxozMuuX0xV-AorlNezE1rRLASGXqcKn_WWntshYik9qj1ARHlgE4NdeRR1ISvOotDEjAE5oBipi4RCg0XrShpmC1nYrFUGF8jWQcbGuwkxsvUtRFHsbyBt9Rnd35vw8z1aSJ9h8f2_BPNqX_Ml8bX7rM5WaXRpafnhZSuJQF7XfP9ksVeO5I7mYCk0XYbsMmDywDUh9uujQpI7YqOhOkFQRcRosrKVnszjQUxrXkBEotmUVuAWM0pMMKs2rHsu51jIyXYb2_K3HihF1Ox7morxwPfGpEiT4wXomh_rrLzLc_qNQ=s959-w959-h458-s-no-gm?authuser=1)

- Make sure checked 3 boxes

![http](https://lh3.googleusercontent.com/fife/AGXqzDlT7rBny9oKyn_EAkEjv8L2UrA9ct8IUFtK0ARxA7imoVpxm5ITey9Wxd8RVyx1p5Y1UDyHcMz654JiTjscqCT9rtd03ILKhnXLZlXphujsYODUIFmDFhw4Fuivro6RgIrhWxmxSgRx1lWQ7DVEVlaeziDG50DQ3KDGw6QFfIkFOwaA6aGc2Dy0bbp2zS8Axt5HXS9Cvb9DU8A2-xhWXzgf3clPabkrqMu762USYfiKyOaMxzkKhDJfagp3QTfEVnYcX2kcO3BOYAzgvJP3tEcornfoqWDn2k6yOCNZt_1lh5aPnKZNuDX5g6AW34EK-fgS7DzNMyL2S_99fKilWm_cIZwlUxCZUs-kqhAF_V_FWaomoqMOaYDbMlIHlzwYQ_ObZJifnXlhyrnEuERw3F3TdcrclC4By91h9abT-8FoPqJ5OvlGSq6xVyqik62GlqGb2c-td2-MxePFi_HZnZGmAPIKqKmEi3fPC1N2_mYYnZsytymHHfDThX8NN-b9HK4aM5jyQJopNtLEqO90VWmQMtPTeWrca96D_hGKyT9YOf2jjpHtczpALqFRdQW7AXpzrODojpaCFE9C4pXcmW-wumpgpngkv78Dbd3LWGNJhcAA43IpsgtanMCdHJOhg0JkBiByns1AE8sMj1KI6kMsQ2MJnrk77HZDhTLG1KN6GJjbLRV1tDfU9Vd-MVESuKZ9mDbw0CJY99vCb3_Y2WZydeaWmNhqMDx5bRBdnU9qR3idsi1wVHXMF_VofLyZhKQRoFWy8orjWYz9kEG-nQUpgXXqgWwcfJRO4K_IleYLBFLYtTKTkukQKWDc5ZZrIaxSaJ2LpTQpxEHLHDGuzANCdz6OiugsXW6ZPlownlj6DilLRVmTMsVwfcMG-CT1i67f9Vog5eaZYXTRQc0Y5gGAhhAFyQIdiNUZpw_Tj1kf6onay0bWyvZ3FBeeJOsn7YGDWkyX0mTD-a6-UFJBXiMxE-nYcC98dlj7sWHvlwl5Mzl0Mauw5VgZFvbYDS0ONHm4apaOlArld8qljQNcIQ07uDbGG64O3gzoJcKGHkfNLu-vGM09OnjwKGSuC0297lFQI9oWMmFvBbymlQo-uoYDfcjIU9loZ0azntMEO6b7AD4HhGVFxwkWjVNjKeRFB4lNk00XyBsUdB13FJxAxqXUMH94r1uGPMeZ91KWB_Q9CNFZGfPd8AUmmkr31CxzBD7Y5YnFb7fACmFV913t9rq2Ko_eH1IITrrFV_vWzb9HX1lJco6qWM160vpDtKGNh_6GigHi9vcPchVSDlfa_SgnfiM6RQYwP9rp8-GuRh6jrdmGjj9EahpHZmNOOB-5Y8ZNF7i6kY3QeFIWE7agjEMobTTWtf_JdW5AejCA14BPxkTlWKHJ7xlTyqFHRVRBKg5HnfAoOAtK-hc3W6pVlDM1jf2Np61my7yoFt8T0oKYy7EdfFtq2RZ8cXYX3fwBTDASRYUMgV0p8509662fMJI-ic1N059ABPNHr2rZPqzvA8cA6JbdqY5EvaqQ58hWE-OWRvvpxsIFqFxs_xbtXxPuLFKau522QRKtcD3zTS0ZCvYuP38QGOnCRbPOwroPTMeFL0TluwjxCUBGA7yAG_d0S_NQNriJMats9g_AYAmd0eSy-lR-YWhEVCwjcdXC-va5DxkEfrebYnGr68TRl5fhvTHWgO1qIVd9WbYw2w=s959-w959-h455-s-no-gm?authuser=1)

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
