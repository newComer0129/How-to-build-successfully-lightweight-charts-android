1. 下載TradingView提供的 lightweight-charts-android
   git@github.com:tradingview/lightweight-charts-android.git

2. lightweightlibrary/build.gradle    36行新增
   compileOptions {
        sourceCompatibility = 11
        targetCompatibility = 11
    }

3. Android Studio => Settings => Preference => Build Tools => Gradle
   => Gradle JDK 設定成 JAVA 11

4. Andriod Studio 編譯專案 => 成功安裝 TradingView 提供測試 APP

5. 截圖
![image](https://github.com/newComer0129/How-to-build-successfully-lightweight-charts-android/blob/main/screenshot_1.jpg)
![image](https://github.com/newComer0129/How-to-build-successfully-lightweight-charts-android/blob/main/screenshot_2.jpg)
