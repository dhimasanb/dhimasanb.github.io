## Install Yii2 Advanced di Windows dengan Composer

![image](https://2.bp.blogspot.com/-caWN1sa63tM/WMKcAre2XAI/AAAAAAAABeE/IPEavKyUP3wR0mR2dJeyz0YEvGaGX-_VQCLcB/s640/yii-banner.jpg?raw=true "Logo Yii")

#### Assalamu'alaikum Wr. Wb.

Pada artikel kali ini kita akan melakukan install Yii2 Advanced di Windows dengan Composer, saya menggunakan Windows 8.1 64 bit. Ada dua cara menginstall Yii, untuk instalasi yii2 ini bisa melalui Composer atau Manual (Download). Namun disini kita akan menginstall cara melalui composer. Kita asumsikan composer sudah terinstall di komputer, Jika belum dapat mengikuti di halaman resmi composer https://getcomposer.org/.

Setelah composer terinstall , kita akan menggunakan Laragon untuk menjalankan Yii, oleh karena itu kita harus menginstall Laragon terlebih dahulu, Jika sudah kita lanjut ke step berikutnya.

##### Berikut cara instalasi Yii2 versi Advanced di Windows melalui Composer:

1. Pertama kita buka CMDer aplikasi bawaan dari Laragon sejenis Command Prompt Windows, Lalu ketik composer global require "fxp/composer-asset-plugin:^1.2.0": 
![alt text](https://github.com/dhimasanb/dhimasanb.github.io/blob/master/resources/web-lanjutan-prak2/1.PNG?raw=true "Composer Require")


2. Ketik composer create-project --prefer-dist yiisoft/yii2-app-advanced (nama-folder): 
![alt text](https://github.com/dhimasanb/dhimasanb.github.io/blob/master/resources/web-lanjutan-prak2/2.PNG?raw=true "Composer Create Project")

3. Setelah terinstall Yii2, pada versi Yii2 Advanced terdapat dua environment, yaitu untuk backend dan frontend.: 
![alt text](https://github.com/dhimasanb/dhimasanb.github.io/blob/master/resources/web-lanjutan-prak2/3.PNG?raw=true "Folder Install")

4. Akses browser frontend melalui url: http://(nama-folder).web/frontend/web, Maka belum bisa muncul halaman web yii, karena belum dikonfigurasi 
![alt text](https://github.com/dhimasanb/dhimasanb.github.io/blob/master/resources/web-lanjutan-prak2/4.PNG?raw=true "Akses sebelum Konfigurasi")

5. Konfigurasi Yii2 advanced dengan ketik 'php init' dan pilih development: 
![alt text](https://github.com/dhimasanb/dhimasanb.github.io/blob/master/resources/web-lanjutan-prak2/5.PNG?raw=true "Composer Require")

6. Akses browser frontend melalui url: http://(nama-folder).web/frontend/web, Maka sudah terlihat frontend Yii2 : 
![alt text](https://github.com/dhimasanb/dhimasanb.github.io/blob/master/resources/web-lanjutan-prak2/6.PNG?raw=true "Composer Require")

7. Begitu juga ketika akses browser frontend melalui url: http://(nama-folder).web/frontend/web, Maka sudah terlihat backend Yii2: 
![alt text](https://github.com/dhimasanb/dhimasanb.github.io/blob/master/resources/web-lanjutan-prak2/7.PNG?raw=true "Composer Require")

Sekian, Terima Kasih.
Wassalamu'alaikum Wr. Wb

<hr>

#### Daftar Pustaka

[Yii2 Framework](http://www.yiiframework.com/doc-2.0/guide-start-installation.html/ "Permalink to Pemakaian Git sehari-hari · Living life and Make it Better")