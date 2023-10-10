# Contact App using Flutter & Firebase

the repository containes the full code to create a contact app in flutter using firebase

## Functionality
- Login / Sign up using email
- Gooogle Login/ Signup
- Firestore create data
- firestore read data
- firestore update data
- firesotre delete data
- search uinsg firestore db
- opening in app dialer

## Watch the full video if you are not able to understand

![Build a Contact App with (5)](https://github.com/Snehasis4321/contacts_app_flutter_firebase/assets/96995340/c7dac1b1-99a7-4d6a-b497-804cae07f2c9)
[Link Here](https://youtu.be/_eVpCZyqjtM)

## Important for google auth

to view sha1 or sha256 key for google auth use this command to 

visit .android folder and then debug.keystore is there run this otherwise generate a debug key and run this command to show sha1 key

Cmd to view 
```
keytool -list -v -keystore debug.keystore -alias androiddebugkey
```

cmd to create new key store file 

Run this to  create first then run above command

```
keytool -genkey -v -keystore debug.keystore -alias androiddebugkey -storepass android -keypass android -keyalg RSA -keysize 2048 -validity 10000
```

make sure to run the command inside .android folder of your username

