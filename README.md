# otomatik şifre üretici
internette biraz araştırma yapıyodum şunu gördüm charAt dedim bune biraz bakındım misal
var değerler = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789"
diye bişey oluşturdum sonra dedimki değerler.charAt(8) bu değerlerin içinden 8. yi seç sonra dedim neden şifre oluşturucu yapamiyim
sonra araştırdım oraya elle sayı girmek yerine nası rastgele sayı girebilirim diye şöyle bişey öğrendim
-random = random bi değer döndürüyo fakat şöyle 0.1595616 / 0.72123726 
*u dedim u ise u = değerler.length 
-floor = örnek olarak 42.216545 diyebi sayı var floor kullandığımızda 42 çıkıyo ekrana 
bunları birleştirincede ortaya 0 ile 62 arasında rastgele sayı çıkartan bi algoritma çıkmış oluyo
değerler.charAt(Math.floor(Math.random() * u));
dedim acaba misal 16 karakter uzunluğunda nası yapabilirim
    for (var i = 0, u = değerler.length; i < 16; ++i) {
        sonuç += değerler.charAt(Math.floor(Math.random() * u));
    }
dedim(sonucu önceden boş olarak tanımlamıştım)
hepsinin birleşimindede ortaya bu çıktı
