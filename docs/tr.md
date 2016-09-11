Nedir?
---
Hyper sass alt yapısını kullanan bir css frameworktür. Takım çalışmalarında ve kişisel projelerde ortak düzen ile hareket etmek için yaratılmıştır.Düzeni koruyarak projeye göre genişletilebilir.  

Nasıl Kullanılır?
---
1. Clone/Download yaparak dosyaları bilgisayarınıza indirin.
2. hyper klasörünü projenize taşıyarak `hyper.scss` dosyasını uygulamanız içerisindeki ana `.scss` dosyasına `@import` ediniz.
3. Derleyicinizi çalıştırarak çalışmaya başlayabilirsiniz. Mutlu kodlamalar. :sunglasses:

Klasör Yapısı Detayları
---
1. [Helpers](#helpers)
2. [Base](#base)
3. [Layout](#layout)
4. [Components](#components)
5. [Pages](#pages)
6. [Vendors](#vendors)

>Projenizin yapısına göre bu klasörlere aşağıdaki açıklamaları dikkate alarak yeni `.scss` dosyaları ekleyebilirsiniz.

## Helpers
Değişkenler, mixinler, fonksiyonlar vb. özelliklerin bulunduğu klasördür. Projenizde kullanabileceğiniz mixin, fonksiyon ve değişkenler için örnek kodlar mevcuttur.

#### Dosya Listesi
* _variables.scss (Sass Değişkenleri)
* _function.scss (Sass Fonksiyonları)
* _mixin.scss (Sass Mixins)


## Base
Siteye ait ana kodların bulunduğu klasördür. Başlangıçta standart olarak belirlenen kodlar burada bulunur(normalize,typography vs.)

#### Dosya Listesi
* _normalize.scss
* _animations.scss
* _typography.scss
* _print.scss
* _reboot.scss


## Layout
Siteye ait ana parçaların stil dosyaları bu klasörde bulunur.

#### Dosya Listesi
* _header.scss
* _nav.scss
* _breadcrumbs.scss
* _sidebar.scss
* _footer.scss




## Components
Küçük tamamlayıcılara ait stil dosyaları bu klasörde bulunur.

#### Dosya Listesi
* _accordion.scss
* _carousel.scss
* _alert.scss
* _button.scss
* _label.scss
* _slider.scss
* _table.scss
* _modal.scss
* _tab.scss
* _video.scss



## Pages
Sayfalara özel stil dosyaları bu klasörde bulunur. Eğer bir sayfa için birde fazla sass dosyası oluşturmak istenirse klasör yapısı oluşturulabilir.

#### Dosya Listesi
* _home.scss
* _contact.scss
* folder/__all -> Örnek klasör yapısı


## Vendors
Framework ve dışarıdan eklenen kütüphanelere ait stil dosyaları burada bulunur.

#### Dosya Listesi
* _bx-slider.scss
* _jquery-ui.scss


## hyper.scss
Ana sass dosyasıdır. Projenize gerekli yolları yazarak `@import` edebilirsiniz. Örnek kullanımı `tests` klasöründen inceleyebilirsiniz.
