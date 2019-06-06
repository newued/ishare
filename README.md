# ishare
react-native-ishare rn模板项目<br/>
####  使用方法：
- 创建缺失的目录
``mkdir android\app\src\main\assets``
-  在创建好的目录添加程序需要的文件
``react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res``
-  androidStadio打开 项目根目录/android/，它会修复项目基本错误
-  执行构建命令
`react-native run-android``
