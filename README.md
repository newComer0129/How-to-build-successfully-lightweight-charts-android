# How-to-build-successfully-lightweight-charts-android
如何成功安裝 TradingView 所提供的 lightweight-charts-android

1. 下載TradingView提供的專案
   https://github.com/tradingview/lightweight-charts-android.git
   
2. Android Studio
   => Settings
   => Build,Build execuation
   => Build tools => Gradle ＝> Gradle JDK
   => 設定為  JVM11

3. lightweight-charts-android/lightweightlibrary/build.gradle 第36行新增
   compileOptions {
        sourceCompatibility = 11
        targetCompatibility = 11
    }
4. Android Stuid 接上 Device => Run app => 開始使用lightweight-charts-android
