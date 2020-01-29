---?image=img/Android_Robot.png
## About for Android

---

### Androidとは？

Googleが開発したモバイル向けOS

現在はIoTなど組み込み向けもサポート

+++

### その特徴は？

- モバイル向けにパフォーマンス調整されたAndroid Runtime（ART）という仮想マシンで動作
- UIのカスタマイズをサードパーティーに開放している
- Google Play Store という専用のAndroidアプリ配信ストアが存在する

---

### Google Play Store

+++

その他のストア

-AndroidはiOSと異なり、サードパーティーのストアが存在

例：Amazon App Market

---

### Android OS のバージョンとそのシェア

Android 11.0
Andorid 10.0

---

### リリースの流れ

1. APKファイルをAndroid Studioでビルド
2. Google Play Consoleでリリース情報を編集
3. APKファイルをアップロード
4. 公開

---

### Androidのライフサイクル

Activityでアプリケーションが構成されています。
１つのActivityで一つのアプリケーションが基本
１つのアプリケーションに複数のActivityも存在

+++

![ライフサイクル画像](img/android_jitsumu2_6.jpg)

+++



ActivityはGCによっていつ切られるかわからない
