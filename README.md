Malbolge'de Karşılaştıgım İlginç Olay

Merhaba,ben Ömer. Malbolge'yle uğraşırken tamamen şans eseri keşfettiğim bir davranışı paylaşmak istiyorum. Normalde "Hello World!" kelimesini Malbolge'de yazdırmak için 94 karakterli bir kod kullanılıyor, ama benim bulduğum bu yöntem sadece 64 karakterle aynı işi yapıyor! (Yani orjinalden %32 daha kısa!)

Kodum şu şekilde:
```malbolge
(=<`#9]~6ZY32Vx/4Rs+0No-&Jk)"Fh}|Bcy?`=*z]Kw%oG4UUS0/@-ejc(:'8dc
```

Ancak kodda bazı tuhaflıklar var:
Eğer kodun içindeki UUS0 yazan yeri (ki burda sıfır/0 ile yazılmış) değiştirip geleneksel olan "O" harfi ile yazarsanız (yani UUSO) program hata veriyor ve çalışmıyor.

Kendi yorumlarım:

Kw%oG4UUS0 bölümü kritik bir noktada UUSO(O harfi ile) yapınca hata veriyor ve başka rakam,sembol ve harfler ile de çalışmayı reddediyor(1,2,3,4,@,P gibi)

Son kısım ( ejc(:'8dc ) ise cümlenin yapısını koruyor bence çünkü son kısmı değistirirsem cümle bozuluyor ve harflerin yerini değişik semboller alıyor.

Test Ettiklerim:
•malbolge.doleczek.pl sitesinde çalıştırdım
ve çalıştı 🎉

•Zb3's orjinal interpreterını denedim ve onda da calıştı 🎉

🤔Kafamdaki sorular:
Normalde kod,geleneksel UUSO ("O' harfi) ile çalışırken bu kod neden UUS0 (sıfır/0) ile çalıştı?

Acaba bu interpreterların bir bug'ı olabilir mi?

Düşünceleriniz benim için önemli:
Eğer bu kodu önceden gördüyseniz veya bu konu hakkında bir fikriniz varsa lütfen bana ulaşın.

Kodun çalıştığının kanıtını,bir görsel halinde koydum ordan bakabilirsiniz.
