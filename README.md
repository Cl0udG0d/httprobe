# httprobe
子域名检测存活,在原版基础上进行部分修改

添加了对于状态码的判断,可以输入自定义状态码

> cat 1.txt | httprobe.exe -c 20 --status-code 200,302 | tee 2.txt

![status_code_image](./images/1730437139089.jpg)