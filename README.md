# Simple-Setup-React-Native
### Intro
Sebenarnya ada banyak pilihan ketika kita ingin membuat aplikasi mobile. Apabila kita ingin membuat aplikasi _Native_ (memakai bahasa yang spesifik untuk platform tertentu), contohnya :

- Android app `=>` bahasa pemrograman Java
- iOS app (apple) `=>` bahasa pemrograman Objective C atau Swift

Nah ada lagi yang namanya _cross-platform_ app. Maksudnya apa _cross-platform_? 

_Cross-platform_ itu mobile apps yang dibuat dengan bahasa pemograman yang tidak spesifik untuk platform tersebut, contohnya bahasa pemograman `JavaScript`. Dulu tidak ada developer yang membuat mobile app memakai `JavaScript`, `JavaScript` dipakai paling banyak untuk website. Tapi setelah perkembangan teknologi, mulailah trend developer memakai `JavaScript` untuk membuat mobile app.

### Berkenalan Dengan React Native
`React Native` merupakan suatu _cross-platform_ framework yang dibuat oleh tim Facebook untuk membuat mobile app (android & ios) dengan menggunakan `JavaScript`.

### Cara Kerja React Native

![rnimages](https://4.bp.blogspot.com/-5iur24ylJbk/WuVaJ2QaqNI/AAAAAAAABUY/gMqpj1WcwMkDt8LfVhQMplJP0mMvgRbYwCLcBGAs/s1600/cara%2Bkerja%2Breact-native.jpeg)


`React Native` bekerja dengan menanamkan file `JavaScript` yang sudah dibundle di dalam aplikasi, dan menjalankan mereka secara local dari aplikasi yang kita buat.
### Pengguna React Native
Perkembangan React Native cukup pesat hingga banyak perusahaan teknologi yang menggunakan framework ini karena kemudahan dan powerfull-nya. Untuk mevalidasi penjelasan ini kita bisa mengeceknya pada link berikut [Who’s using React Native?](https://facebook.github.io/react-native/showcase.html)


![rnimag](https://1.bp.blogspot.com/-33yKrWwGvFM/WuVZeUt24GI/AAAAAAAABUQ/Ds-9uBdP3i0GzNBJccsRu9WyNBR6H6ktACLcBGAs/s1600/penjelasan%2Breact%2Bnative.png)

### Instalasi React Native
1. Install `NodeJs`
```
$ sudo apt update
$ sudo apt install nodejs
$ nodejs -v
```
2. Install `npm`
```
$ sudo apt install npm
$ npm -v
```
3. Install `Java JDK `
```
$ sudo apt install openjdk-8-jdk openjdk-8-jdk-headless openjdk-8-jre
```
4. Cek `JDK`
```
$ javac -version
```
5. Cek `JRE`
```
$ java -version
```
6. Install `Android SDK`
7. Menambahkan direktori `~/Android/Sdk` ke dalam file `~/.bashrc` , agar perintah android dapat digunakan pada terminal.
- Buka file `~/.bashrc` dengan nano
```
$ nano ~/.bashrc
```
- Lalu pada bagian akhir tambahkan baris ini
```
export ANDROID_HOME=$HOME/Android/Sdk
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
export PATH=$PATH:$ANDROID_HOME/platform-tools
```
- Tekan `Ctrl+x` untuk keluar dan pilih `y` untuk menyimpan
8. Cek `Android Version`
```
$ android --version
```
9. Install `React Native`
```
$ sudo npm install -g react-native-cli
```

