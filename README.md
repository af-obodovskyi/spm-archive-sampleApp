# spm-archive-sampleApp
This is the sample app to verify the solution works for the SPM Xcode 15.3 

In order to reproduce and verify, that the solution works, please do the following:

1. Clone this repository and open the project; 
2. Set the bundle indentifier and your development teaml 
3. Import one of the following packages below for the static, dynamic or strict dependency: 

#### For statically linked library
https://github.com/AppsFlyerSDK/AppsFlyerFramework-Static

#### For dynamically linked library
https://github.com/AppsFlyerSDK/AppsFlyerFramework-Dynamic

#### For Strict (No IDFA colection) library
https://github.com/AppsFlyerSDK/AppsFlyerFramework-Strict

4. Archive the project;
5. After the archive organiser pops up, click **Validate App** or **Distribute App**;
6. Create an app record and modify the name (this will create a record of the application in the AppStore Connect)
7. Wait until validation finish and verify, that there is no error related to **MyApp.app/Frameworks/AppsFlyerLib.framework does not support the minimum OS Version specified in the Info.plist.**