1. apple developer account
    1. 
2. Expo account
    1. 
3. app.json : name of application and slug of the applicatopn
4. install eas cli
5. eas whoami
6. eas login
7. eas build:configure -> ios/andriod
8. build: eas build --platform ios
9. ios bundle identifier
10. log in to apple account
11. distribution certificate
12. push notification
13. app store: app store connect
14. my apps - new app - ios, name of app, bundle id, sku: com.notjust.name


## Google Play
1. eas cli
2. login to expo
3. eas build:onfigure
4. build apk:eas build -p android --profile preview
5. prod build : eas build - aab file and add to google store
6. create app on google play
7. privacy policy genrator

## App Version
1.First version in package json: 
2. import pkg from './package.json''
3. import {coerce} from 'semver';

### CI/CD pipeline
https://medium.com/swlh/expo-react-native-complete-ci-cd-workflow-using-github-actions-4b7bc87616b3