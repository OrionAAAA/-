
## 本脚本仅供学习交流，否则后果自负
## 感谢 @ZimoLoveShuang 对本项目的帮助
## 感谢 @Starix610 对本项目的帮助

本项目依赖python3、pytesseract、requests、pyDes、beautifulsoup4,还需要额外安装tesseract-OCR，请自行百度教程。
```
 pip install pytesseract
 pip install requests
 pip install pyDes
 pip install beautifulsoup4
```
本项目不维护，佛系更新。不包含周期执行功能，建议部署在Windows计划任务或远端服务器上  

### 使用
###### 1.安装上文提到的依赖，其中tesseract-OCR安装后可能需要修改pytesseract的某些内容，请自行百度教程
###### 2.打开config.ini ，根据说明填写相关信息，保存
###### 3.运行Fcpdaily-2.0.py，即可完成一次签到（控制台会有文字提示，如果脚本闪退可能说明某些配置尚未完成，请自行调试）


##### 更新说明 Fcpdaily-2.0
###### 1.本次更新废弃了原来用selenium+webdriver的模拟登陆方式，用更加直接的request，提升了签到运行的速度。
###### 2.采用配置文件的方式，降低了耦合度，增强了对多人签到的支持。
###### 3.采用了加密算法生成cpdaily-extention，现在再也不用自己重新抓取extention了
 
