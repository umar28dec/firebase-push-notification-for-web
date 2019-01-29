
For Website
```javascript
curl -X POST -H "Authorization: key=AAAAwtwJY6g:APA91bGwf5jjipw3wyMD10xF4vPcYuQAixzQ0iFGa75iTnusw9aYfPLkOHEceHzj_82-eCMrYvsESfDqqWFL_ayGe46hP80JSCZ61wF1FI9Wl_pfZZTcwyZNmyzZ6jpqmtv5OaThr3TL" -H "Content-Type: application/json" -d '{
    "notification": {
    "title": "Allen -Online Test Series",
    "body": "The Quick brown fox jumps over the layz Dog",
    "icon": "https://www.drivespark.com/images/2019-01/yamaha-fz-fz-s-2019-9.jpg",
    "click_action": "https://test.com/"
  },
  "to": "e8dMbwUrjTs:APA91bEtu5wugMSF8hz-DizenLDT52Ueb6q0-VJFJNfZT93opw1WSujxQx6HLu8ODzAtSZm9Nno3-b8UqQhz40nB03T5uSoee6xsQuvQgG2SQq4jBqTPDJ3AqLKzAL7HcuZKRcxamzY4"
}' "https://fcm.googleapis.com/fcm/send"
```


For Android app
```javascript
curl -X POST -H "Authorization: key=AAAAIBVLMZk:APA91bHqCXcstZOPiZLBiwEsfdUSboJ9O0qGdEiFDO4BQ4RbNSdM6CbLFSMj6R6RFZPnyyY6jlYix005ktkivh9gWgxa0bX3O1b3jfLeUyTJ4Yq0E8CROKXIoIvL9QP5IzK47ActtDny" -H "Content-Type: application/json" -d '{
   "data":{
   "message":"The quick brown Fox jumps over the lazy dog",
   "image":"https://www.drivespark.com/images/2019-01/yamaha-fz-fz-s-2019-9.jpg",
   "title":"App new notification"
 },
  "to": "dLHXIPRj0Jg:APA91bF6tDRRhPrRM94rF5wwW4x4vtVzg9sOqHIsC5w92ZN3I9HQNP1jb9Ehjf7sF9GeSodDJlwNSM572LMB_G-4mESVRCpmtlg40CBYl0BJdlOtjxNiEze4LBOG1kmHwRUn7lBQqKUi"
}' "https://fcm.googleapis.com/fcm/send"

```

For multiple token or devices
```javascript
curl -X POST -H "Authorization: key=AAAAIBVLMZk:APA91bHqCXcstZOPiZLBiwEsfdUSboJ9O0qGdEiFDO4BQ4RbNSdM6CbLFSMj6R6RFZPnyyY6jlYix005ktkivh9gWgxa0bX3O1b3jfLeUyTJ4Yq0E8CROKXIoIvL9QP5IzK47ActtDny" -H "Content-Type: application/json" -d '{
   "data":{
   "message":"The quick brown Fox jumps over the lazy dog",
   "image":"https://www.drivespark.com/images/2019-01/yamaha-fz-fz-s-2019-9.jpg",
   "title":"App new notification"
 },
  "registration_ids": ["dLHXIPRj0Jg:APA91bF6tDRRhPrRM94rF5wwW4x4vtVzg9sOqHIsC5w92ZN3I9HQNP1jb9Ehjf7sF9GeSodDJlwNSM572LMB_G-4mESVRCpmtlg40CBYl0BJdlOtjxNiEze4LBOG1kmHwRUn7lBQqKUi","e3y-3H9YbPQ:APA91bGCZK7iXzuQO2c_eTIPOld6lGKUMiuJQPsrKdNF2N0gIkJSV3Hu2vVVRMzfbEZMLEUOeMuwxqRlu8Ls2mZiwf--EWi-wlm8UG3frzTKZvrI1JCgjk0f1u7he14ONTFHUwsYvJvZ"]
}' "https://fcm.googleapis.com/fcm/send"

```
Limit for multiple tokens

https://stackoverflow.com/questions/39997272/fcm-firebase-cloud-messaging-send-to-multiple-device-group

SSl needed for push notification, it could be self signed 

CReate topics for notification and get topic list

https://stackoverflow.com/questions/40389335/how-to-subscribe-to-topics-with-web-browser-using-firebase-cloud-messaging


https://developers.google.com/instance-id/reference/server#get_information_about_app_instances

https://iid.googleapis.com/iid/info/eMqdRJkeAmM:APA91bEVu-e07qqpf6GMCQxd84X4mDMyLXWTaR6IkSdGH1w9AV30oiLss6yk3TRe0Fvf1oolS6dKHc4rxni7v4lt7RGyXT2dEWJQLQ2y9pnpJorEhJltgJz8GjKGHiINCVXAnI2mbU2x?details=true


