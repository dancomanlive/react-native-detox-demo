iOS:
- manual build: 
  - run project on simulator
  - go to project name in the left side menu in XCode
  - open Products folder
  - copy path to DetoxDemo.app
- add path to app binary in .detoxrc.json to "binaryPath" in configurations.ios
- detox test -c ios


Android:
- detox build -c android.emu.debug
- add path to apk binary in .detoxrc.json to "binaryPath" in configurations.android
- detox test -c android.emu.debug