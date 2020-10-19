# **myDrive: An App for Auto Synchronization on Google Drive**
### Download APK: app/relese/myDrive_1.0.apk
## *Problem Statement: <br>
### There is possibilies that electronic files/folders might be erase or misplaced from your device. So in this scenario portability is an issue. But we can save our important data on **Google drive**. So make an app to solve this issue.<br>
## **Overview of Solution:* <br>
### We develope an App which will sync internal and external data with scheduled time and day on your device.The App has provision where user can select a specific folder or file and shedule a particular time & day to synchronize it over Google drive.
## *Solution:
### 1) Google Sign In:https://developers.google.com/identity/sign-in/android/start-integrating<br>Reffering to this documentation you can create Sign In method where user can choose one account from all accounts that have linked to his/her device's google account
### 2) Enabling Drive Api: https://developers.google.com/drive/api/v3/quickstart/java<br>
### Using this website we can enable an API for Google drive. To enable this API we have to generate a **SHA-1 Key** using Android Studio.
### 3) Syncing Data:https://developer.android.com/training/sync-adapters/creating-sync-adapter?authuser=1 for syncing data to drive.
### 4) Schedule repeating method: https://developer.android.com/training/scheduling/alarms Reffering this documentation we made a schedule for uploding data to drive.
### 5) Background Processing: https://developer.android.com/guide/background
### 6) We enabled all required permission in manifest of Android studio.
## *Snippets:
### **Video:** https://youtu.be/Snaqh23gDB4
### i) *After opening App you have to give permission to your google account for syncing*
![Sign In](https://user-images.githubusercontent.com/58518903/96398088-a1d35a80-11e8-11eb-94c6-3f526c843c62.jpg)
### ii) *Then allow permission to give access of your device storage*
![Access Allow](https://user-images.githubusercontent.com/58518903/96398151-c7f8fa80-11e8-11eb-84b0-ce1b5db8ce6c.jpg)
### iii) *Then click on plus button on bottom right.The window like below image will open.From there select the folder/file which has to upload*
![Folder selec](https://user-images.githubusercontent.com/58518903/96398241-fe367a00-11e8-11eb-903f-bbfa695a77dd.png)
### iv) *Schedule for the upload.Set day and time(24Hrs clock)*
![Schedule](https://user-images.githubusercontent.com/58518903/96398232-f7a80280-11e8-11eb-8079-d04c444bd2ad.png)
### v) *If the schedule time and day is achieved then folder/file will be uploaded to drive and selected folder/file will be displayed in App*
![Uploaded](https://user-images.githubusercontent.com/58518903/96398252-04c4f180-11e9-11eb-9692-cb28cde50f9c.png)
### vi)Folder/file is uploaded to Google drive
![7](https://user-images.githubusercontent.com/58518903/96399987-48b9f580-11ed-11eb-89cb-3020f2bf1828.jpg)
