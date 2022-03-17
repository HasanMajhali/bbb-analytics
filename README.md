# BigBlueButton-Analytics</h1>

You can easily access analytics such as attendance, insights into usage of audio/video/chat and activity score of attendees during your BigBlueButton sessions.

BONUS: You can also view all recordings!
  
<a href="https://www.npmjs.com/package/bigbluebutton-analytics">
<img alt="GitHub package.json version" src="https://img.shields.io/github/package-json/v/manishkatyan/bbb-analytics?label=npm&logo=npm">
</a>
<a href="https://www.npmjs.org/package/bigbluebutton-analytics">
<img src="https://img.shields.io/npm/dm/bbb-analytics.svg" alt="Monthly download on NPM" />
</a>

<br/><br/>

## ✨ Features

- **View all learning-dashboard data**
- **Password protected**

<br/><br/>

<img style="width: 100%; height: auto;" src="https://higheredlab.com/wp-content/uploads/bigbluebutton-analytics.png" alt="bbb-class" /> <br/>

<br/><br/>

## 🖐 Requirements
A server with BigBlueButton 2.4.4 installed.

## ⏳ Installation

```bash
# Install bbb-analytics CLI globally
npm i -g bigbluebutton-analytics

#Install dependecies
bbb-analytics --deploy

```


After succussfull installtion you should be able to access **https://<bbb.example.com/analytics/>**
## default login details
**username**: admin
<br />
**password**: admin123

**NOTE:** Be sure to change the password using the below command

```bash
#To create or update username/password
bbb-analytics --add-user --username=<username> --password=<password>
```

Enjoy 🎉

<br/>

## 📝 License

[MIT License](LICENSE.md) Copyright (c) [Asyncweb](https://higheredlab.com/).
