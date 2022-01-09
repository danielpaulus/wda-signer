This repo can be used to sign webdriveragent for any device. 

1. Fork the repo
2. run base64 -i p12file.p12 and base64 -i testdata/profile.mobileprovision and add the output
   to github repo the secrets. Call the secrets P12 and PROFILE 
3. add the p12 password to repo secrets and call it P12PASSWORD
4. Run workflow manually using workflow dispatch
5. download your signed wda

I use a precompiled wda.ipa
If you want to comile your own, visit github.com/appium/WebDriverAgent for learning how to build. 