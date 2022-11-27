# Ionic Framework PBP

**Disusun Oleh:**
- Muhammad Farhan Haris Rosidi 24060120140104
- Muhammad Fariz Aditya Pratama 24060120140149
- Yusuf Qisthi Abdul Jabbar 24060120140134
- Rachmad Akbar Ramadan 24060120140137
- Rizal Zeri Subakti 24060120130062

# Cara Instalasi

Clone project
>git clone https://github.com/Faradayy05/PBP-Ionic.git

Install NPM
>npm install

Install Ionic global
>npm install -g @ionic/cli

-   lakukan command ionic start  <nama folder> untuk membuat aplikasi baru.
>ionic start

-   Pilih framework yang digunakan antara Angular, React, atau Vue.Pada kasus ini kami menggunakan angular
-   Pilih template tabs, sidemenu, blank, list, atau my-firstapp
-   Lakukan tahap development sesuai aplikasi yang diinginkan
-   Agar aplikasi dapat berjalan secara cross-platform kita akan memerlukan cordova atau capacitor.
## Run dengan cordova
-   Install cordova terlebih dahulu
>npm -i -g cordova
-   Untuk menambah kompatibilitas pada device, kita lakukan command: 
> cordova platform add  PLATFORM_NAME
-   setelah itu kita bisa run dengan command: 
>cordova run PLATFORM_NAME

## Run dengan capacitor
-   Install capacitor terlebih dahulu
>npm install @capacitor/cli@latest @capacitor/core@latest
-   Initialize capacitor config
>npx cap init
-   Tambahkan platform yang ingin digunakan
>npx cap add PLATFORM_NAME (android/ios)
-   Sync konfigurasi
>npx sync
-   Jika ingin membuka dengan android studio bisa
>npx cap open android
-   Jika ingin run dengan CLI
>npx cap run android
