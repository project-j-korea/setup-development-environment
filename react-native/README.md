# React Native

- If you haven't done mac os setting, click **[here](../mac-os)**.
- If you haven't done nodejs setting, click **[here](../nodejs)**.
- Install Npm module

  1. Launch the Terminal, Go to `YOUR_PROJECT_LOCATION/ProjectJ/app`
  2. Type the following command string:
     ```bash
     $ yarn install
     ```

- Android setting

  1. Install [Android Studio](https://developer.android.com/studio?hl=ko)
  1. Running Android Studio
  1. For **SDK Components Setup**, Select `Intel®HAXM` and `Android Virtual Device`.
  1. If the setup is complete, Go to **configure/SDK manager**
  1. Click `Show Pacakge Details`, Find and select the following packages from the list:
     ```
     □ Android SDK Platform 29
     □ Intel x86 Atom System Image
     □ Google APIs Intel x86 Atom System Image
     □ Google APIs Intel x86 Atom_64 System Image
     ```
  1. Exit Android Studio
  1. Add the following environments variables to `~/.bash_profile` or `~/.zshrc`.
     ```
     export ANDROID_HOME= $HOME/Library/Android/sdk
     export PATH= $PATH:$ANDROID_HOME/emulator
     export PATH= $PATH:$ANDROID_HOME/tools
     export PATH= $PATH:$ANDROID_HOME/tools/bin
     export PATH= $PATH:$ANDROID_HOME/platform-tools
     ```
  1. Type the following command string:

     ```bash
     $ source ~/.bash_profile
     $ # OR
     $ source ~/.zshrc
     $ adb

     $ brew install watchman
     $ watchman --version

     $ brew tap AdoptOpenJDK/openjdk
     $ brew install --cask adoptopenjdk8
     $ java -version
     $ javac -version
     ```

- IOS setting
  1. Install [Xcode](https://apps.apple.com/kr/app/xcode/id497799835)
  1. Running Xcode, Go to **Xcode/Preferences.../Locations/Command Line Tools**, Select Version `ex) Xcode 12.0.1 (12A345)`
  1. Exit Xcode
  1. Type the following command string:
     ```bash
     $ sudo gem install cocoapods
     $ pod --version
     $ cd YOUR_PROJECT_LOCATION/ProjectJ/app && pod setup && pod init && pod install
     ```
