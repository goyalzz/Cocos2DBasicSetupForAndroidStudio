# First Cocos Tutorial for Android #
> Demo tutorial with commands to setup cocos 2dx

#### Steps to Setup ####
1. Download cocos 2dx and goto inside the dir.
2. Run command ```python ./setup.py ```. It can set some environment variables edit if you want.
3. Run command to execute env variables ```source ~/.bash_profile```.
4. To create a sample project use command ```cocos new TutorialV3CPP -p com.tutorial -l cpp -d <PATH TO OUTPUT PROJECT DIRECTORY>```
5. To compile code use below commands:
    - For Mac ```cocos compile -s <Path of Project> -p mac -m release -o <Path of Project compilation output>```
    - For Android ```cocos compile -s <Path of Project> -p android -m release -o <Path of Project compilation output>```
    - For iOS ```cocos compile -s <Path of Project> -p ios -m release -o <Path of Project compilation output>```
    - For WEB ```cocos compile -s <Path of Project> -p web -m release -o <Path of Project compilation output>```
    - For WIN32 ```cocos compile -s <Path of Project> -p win32 -m release -o <Path of Project compilation output>```
    - For Android-Studio Project ```cocos compile -s <Path of Project> -q -p android -m debug --android-studio  --ap android-25```

    - ADD ```-q``` to reduce the output to the console like ```cocos compile -q -s <Path of Project> -p android -m release -o <Path of Project compilation output>```


#### Sample Environment Variables ####
```
export JAVA_HOME=$(/usr/libexec/java_home)
export JRE_HOME=$(/usr/libexec/java_home)
export ANDROID_HOME=/Users/aakashsharma/Library/Android/sdk
export ANT_HOME=/usr/local/opt/ant
export MAVEN_HOME=/usr/local/opt/maven
export GRADLE_HOME=/usr/local/opt/gradle
export ANDROID_NDK_HOME=/Users/aakashsharma/AndroidGameDevelopment/android-ndk-r14b
export PATH=$ANT_HOME/bin:$PATH
export PATH=$MAVEN_HOME/bin:$PATH
export PATH=$GRADLE_HOME/bin:$PATH
export PATH=$ANDROID_HOME/tools:$PATH
export PATH=$ANDROID_HOME/platform-tools:$PATH
export PATH=$ANDROID_HOME/build-tools/19.1.0:$PATH
export KAFKA_HOME=/Users/aakashsharma/Downloads/kafka_2.11-0.10.0.1
export SPARK_HOME=/Users/aakashsharma/Downloads/spark-2.0.2-bin-hadoop2.7
export CASSANDRA_HOME=/Users/aakashsharma/Downloads/apache-cassandra-3.10


# Add environment variable COCOS_CONSOLE_ROOT for cocos2d-x
export COCOS_CONSOLE_ROOT=/Users/aakashsharma/AndroidGameDevelopment/cocos2d-x-3.15/tools/cocos2d-console/bin
export PATH=$COCOS_CONSOLE_ROOT:$PATH

# Add environment variable COCOS_X_ROOT for cocos2d-x
export COCOS_X_ROOT=/Users/aakashsharma/AndroidGameDevelopment
export PATH=$COCOS_X_ROOT:$PATH

# Add environment variable COCOS_TEMPLATES_ROOT for cocos2d-x
export COCOS_TEMPLATES_ROOT=/Users/aakashsharma/AndroidGameDevelopment/cocos2d-x-3.15/templates
export PATH=$COCOS_TEMPLATES_ROOT:$PATH

# Add environment variable ANDROID_SDK_ROOT for cocos2d-x
export ANDROID_SDK_ROOT=$ANDROID_HOME # /usr/local/Cellar/android-sdk/24.4.1_1
export PATH=$ANDROID_SDK_ROOT:$PATH
export PATH=$ANDROID_SDK_ROOT/tools:$ANDROID_SDK_ROOT/platform-tools:$PATH

export ANT_ROOT=$ANT_HOME
export NDK_ROOT=$ANDROID_NDK_HOME
```