# AAPS
* Check the wiki: https://wiki.aaps.app
*  Everyone who’s been looping with AAPS needs to fill out the form after 3 days of looping  https://docs.google.com/forms/d/14KcMjlINPMJHVt28MDRupa4sz4DDIooI4SrW0P3HSN8/viewform?c=0&w=1

## How to Build

### If your are familiar with Android development:
* Fork this repository.
* Replace `keystore/demokeystore.jks` with your own key store file.
* Add below secrets in the  `Actions secrets and variables` settings of your repository.  
<a href="/Documentation/screen1.png"><img src="/Documentation/screen1.png?raw=true" alt="Screenshot of Actions secrets" width="800"></a>  
  `KEY_ALIAS`:  Key alais of your key store file.
  `KEY_PASSWORD`: key password of your key store file.
  `STORE_FILE`: Path of your key store file in your repository.
  `STORE_PASSWORD`: Store password of your key store file.
* Trigger build in Github Actions
* Download the `aaps.zip` file in `Artifacts`

### If your are NOT familiar with Android development:
You need to get the secerts of the key store file to sign your application. For security reason, all of the passwords are NOT in this repoitory.
**It's really recommanded that you can sign your apk file with your own key store file after learning some Android knowledge.**
Please follow these steps:
* Fork this repository.
* Scan the below QR code and subscribe "一型码农Lex" WeChat Channel.  
<a href="/Documentation/wechat_qr.png"><img src="/Documentation/wechat_qr.png?raw=true" alt="WeChat Channel QR code" width="340"></a>  
* Join the WeChat group and ask for the secrets. (Get the WeChat group QR code form the middle menu of "一型码农Lex" WeChat Channel. Scan to join.)
* Add below secrets in the  `Actions secrets and variables` settings of your repository.  
<a href="/Documentation/screen1.png"><img src="/Documentation/screen1.png?raw=true" alt="Screenshot of Actions secrets" width="800"></a>  
  `KEY_ALIAS`, `KEY_PASSWORD`, `STORE_FILE`, `STORE_PASSWORD`. 
* Trigger build in Github Actions
* Download the `aaps.zip` file in `Artifacts`
