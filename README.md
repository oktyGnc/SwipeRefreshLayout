# <p align="center"> SWIPE-TO-REFRESH APP </p>

## Uygulama Özellikleri

**Çekme Yenileme**: Kullanıcılar, listeyi aşağı kaydırarak verileri hızlı ve kolay bir şekilde yenileyebilir.

**Dinamik Veri Güncelleme**: Uygulama, her yenileme işleminde yeni öğeler ekleyerek listeyi günceller.

**Kullanıcı Dostu Arayüz**: Basit ve sezgisel bir arayüz ile kullanıcıların kolayca listeyi yenilemesine olanak tanır.

**Hızlı Performans**: Liste güncellemeleri hızlı bir şekilde gerçekleştirilir.


## 🎬 Video
https://drive.google.com/file/d/1VIL3wrqjdt79IDVh0vkmUEoiqCoThA0d/view?usp=sharing
<br>


## :point_down: Kullanılan Teklonojiler

**AndroidX SwipeRefreshLayout**
androidx.swiperefreshlayout:swiperefreshlayout:1.1.0: Kullanıcıların listeyi aşağı kaydırarak yenileme işlemi gerçekleştirmesine olanak tanır.

**ListView**: Verilerin görüntülenmesi için kullanılan bir bileşendir.

**ArrayAdapter**: Liste verilerini bağlamak için kullanılan bir adaptördür.

**Kotlin**
Uygulama, Android uygulama geliştirmek için Kotlin programlama dili ile yazılmıştır.


## :pencil2: Dependency

app build.gradle
```
plugins {
    alias(libs.plugins.android.application)
    alias(libs.plugins.kotlin.android)
}
```
```

    
    dependencies {

    implementation(libs.androidx.core.ktx)
    implementation(libs.androidx.appcompat)
    implementation(libs.material)
    implementation(libs.androidx.activity)
    implementation(libs.androidx.constraintlayout)
    testImplementation(libs.junit)
    androidTestImplementation(libs.androidx.junit)
    androidTestImplementation(libs.androidx.espresso.core)

    implementation (libs.androidx.swiperefreshlayout)

}
```
project build.gradle

```
plugins {
    alias(libs.plugins.android.application) apply false
    alias(libs.plugins.kotlin.android) apply false
}
```

## :pencil2: Kurulum Talimatları

Projeyi bilgisayarınıza klonlamak için aşağıdaki komutu kullanın:

```bash
git clone https://github.com/oktayGnc/SwipeRefreshLayout
```