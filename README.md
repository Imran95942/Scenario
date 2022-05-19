# A project By TeamScenario

• A star 🌟 from you means a lot please star if you liked this project.
<span style="color:blue">some Hello text</span>. 
<br>

# <mark>Things to be noted</mark>

<mark>1. There are 2 app.json format in repository
   first is named as app it's for pros like you 
   and another one app.json for beginners 
   so if you're a pro person rename app to app.json
   before that delete existing one.

2. To update your app on heroku use /update command if error use /gitpull</mark>

### Most important vars

| Vars | from where to get |
| ----------- | ----------- |
| API_ID | Get it from my.telegram.org |
| API_HASH | Get it from my.telegram.org |
| TOKEN | from @BotFather |
| OWNER_ID | DM @ScenarioXbot and send /id |
| DEV_USERS | same as OWNER_ID |


> Scenario is the most Advanced telegram bot to manage your groups. 
Demo bot - @anonymous_4_robot

## How To Deploy 
<details>
<summary><b>🔗 Deploy to Heroku</b></summary>
<br>

> All vars are already filled and some are optional not filling them will not make big difference.

> <b>First fork this repo!!</b>

• before that please star 🥺

• Click here to fork ↓
<p><a href="https://github.com/TeamScenario/Scenario/fork"><img src="https://telegra.ph/file/8b61f6edc2a35c473ddff.jpg" alt="Press to Takeoff" width="490px"></a></p>
    
<h4>Click the button below to deploy Scenario on Heroku!</h4>    
<p><a href="https://teamscenario.blogspot.com/heroku-deployer"><img src="https://telegra.ph/file/57c4edb389224c9cf9996.png" alt="Press to Takeoff" width="490px"></a></p>
</details>
<details>
<summary>Update heroku app with CLI</summary>
<h4>Download termux!</h4>    
<p><a href="https://download.apkcombo.com/com.termux/Termux_0.118.0_apkcombo.com.apk?ecp=Y29tLnRlcm11eC8wLjExOC4wLzExOC41MThkOGEwNDliMzFlZTI4ZTBkZjczZTVmYTIxZjM4NmZjNDY4ODg4LmFwaw==&iat=1652949767&sig=0ccdc62db780ace69c4e0d363c0a6d80&size=101739523&from=cf&version=latest&lang=en&fp=a981b449f00e83d699ee4aba1f4bcbc3&ip=47.9.1.4"><img src="https://telegra.ph/file/9e955b5952bc0836a6b4b.png" alt="Press to Takeoff" width="490px"></a></p>

Enter this code in termux
```
apt update && apt upgrade && pkg install git && sh -c "$(curl -fsSL https://raw.githubusercontent.com/SKGHD/Termux-heroku-cli/master/install.sh)" && heroku login -i
```
### After heroku login
```
cd /storage/emulated/0 && git clone https://github.com/TeamScenario/Scenario
```
### After clone 
```
cd Scenario 
```
### enter your app name instead of appname
```
heroku git:remote -a yourapp
```
### Final step 
```
git pull https://github.com/TeamScenario/Scenario && git push heroku HEAD:master
```

All done !

<details>
<summary><b>Deploy on Vps / local machine</b></summary>
<br>

> We don't provide support for vps deployment so don't come to us with your problems!
    </br>

```console
    ~$ git clone https://github.com/TeamScenario/Scenario
    ~$ cd scenario
    ~$ cp sample_config.py config.py
```

Edit Config.py with your own Values

Start with ```python -m scenario```

</details>

<details>
<summary>Contact us 🌟</summary>
<p align="center"><a href="https://t.me/The_Arc_Music"><img src="https://telegra.ph/file/50c21b237d00309571e00.jpg" width="2000"></a></p>
 
## <img height="40" src="https://raw.githubusercontent.com/innng/innng/master/assets/kyubey.gif"/>Contact us

[![Group](https://img.shields.io/badge/dynamic/json?logo=telegram&label=%40ScenarioXsupport&labelColor=282c34&suffix=+members&color=2CA5E0&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dtelegram%26queryKey%3DThe_Arc_Music&longCache=true%22)](https://t.me/ScenarioXsupport)
[![Group](https://img.shields.io/badge/dynamic/json?logo=telegram&label=%40TeamScenario&labelColor=282c34&suffix=+members&color=2CA5E0&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dtelegram%26queryKey%3DThe_Arc_Music&longCache=true%22)](https://t.me/TeamScenario)
</details>
  

## TODO
- [ ] Better readme
- [x] Less vars to fill
- [ ] Design improvement

[^TeamScenario]
[^TeamScenario]: ©2022 TeamScenario All rights reserved!

