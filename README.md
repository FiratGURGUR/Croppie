# Croppie

Bu uygulamada profil fotoğrafı seçme ve Düzenleme(Crop and Rotate vb.) işlemlerini içeren basit bir uygulamadır.

Crop işlemi için kullanılan kütüphane : https://github.com/ArthurHub/Android-Image-Cropper

Eğer fragment içinde kullanacaksanız 

 CropImage.activity(uri)
                    .setAspectRatio(1,1)
                    .setGuidelines(CropImageView.Guidelines.ON)
                    .start(getContent(), this);
                    
şeklinde "getContent()" kullanmanız gerekir.          

### ScreenShots

<img src="https://github.com/FiratGURGUR/Croppie/blob/master/app/src/main/res/drawable/sch1.png" width="30%"> <img src="https://github.com/FiratGURGUR/Croppie/blob/master/app/src/main/res/drawable/sch2.png" width="30%">
<img src="https://github.com/FiratGURGUR/Croppie/blob/master/app/src/main/res/drawable/sch3.png" width="30%"> <img src="https://github.com/FiratGURGUR/Croppie/blob/master/app/src/main/res/drawable/sch4.png" width="30%">
