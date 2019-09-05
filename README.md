## Angular 7 Kurulum:

1) nodejs kurulu olmali (npm nodejs ile birlikte otomatik kurulur)

2) `npm install -g @angular/cli` (angular cli kurulmali)

Not: angular/cli kurulduktan sonra commond line da "ng" komutlari calismaya baslar.

3)Yeni bir proje olusturma: `ng new proje-adi`

4)Projenin ana dizinine gitme: `cd proje-adi`

5)Projeyi calistirma: `ng serve` (emberjs de: " ember s " komutu)

**Not:** Projeyi ozel bir port uzerinden yayina almak istersek: `ng serve --port 8081` komutunu kullanabiliriz (Bu sadece sunucuyu ayaga kaldirir. Tarayicida elle yazarak goruntuleriz)

**Not:** Projeyi dogrudan varsayilan tarayicida calistirmak istersek: `ng serve --open` komutunu kullanabiliriz.

**Not:** Projeyi dogrudan varsayilan tarayicida ve istedigimiz bir port uzerinden calistirmak istersek: `ng serve --open --port 8081` komutunu kullanabiliriz.

**Not:** Angular proje serve olduğu anda **"Angular Live Development Server"** belirttigimiz portu watch eder. Biz herhangi bir degisiklik yaptigimizda bu ekrana otomatik yansir. 

**Not:** Çalışan bir projeyi `CTRL + c`  komutu ile sonlandırabiliriz.

**Not:** Command Prompt da proje ana dizininde iken (Örnek: C:/Angular/YeniProje): `code .`  komutu ile projemizi VSCode editöründe açabiliriz.

**Not:** Bir angular projesinde **"src"** klasörü ana uygulama klasörüdür.

