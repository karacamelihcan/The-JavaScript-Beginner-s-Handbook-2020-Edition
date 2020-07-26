
# JAVASCRIPT 
[The-JavaScript-Beginner-s-Handbook-2020-Edition](https://www.freecodecamp.org/news/the-complete-javascript-handbook-f26b2c71719c/#alittlebitofhistory)

![js](https://user-images.githubusercontent.com/51059267/85326923-bb80c180-b4d6-11ea-814d-a6cafdd4a6b7.png)

JavaScript, günümüzde ki en popüler programlama dillerinden biridir.

Programlamaya yeni başlayan kişiler için harika bir seçim olduğunu söyleyebiliriz.

Çoğunlukla JavaScript'i;
- İnternet siteleri
- İnternet uygulamaları
- Node.js kullanan sunucu taraflı uygulamaları oluşturmak için kullanırız.

Fakat JavaScript bunlarla sınırlı değildir. Ayrıca ;
-   React Native gibi uygulamaları kullanarak mobil uygulamalar geliştirmek
-   Mikrokontrolörler ve nesnelerin interneti (IoT) geliştirmeleri
-   Akıllı saat uygulamaları geliştirmek içinde kullanabiliriz.

Esasen JavaScript kullanarak bir çok işlemi gerçekleştirebiliriz. Yeni çıkan neredeyse bütün teknolojilerin bazı noktalarda JavaScript entegrasyonlarının olması da, bu dilin popüler olmasını sağlayan başka bir önemli faktördür.

JavaScript :  
- **High Level**: Bilgisayarın çalışırken ki detaylarını görmezden gelmemize imkan tanıyan soyutlamalar sağlar. *Garbage Collector* ile herhangi bir eylem gerekmeden belleği yönetir. Bu sayede, C benzeri dillerdeki gibi belleği yönetmek yerine yazdığımız koda odaklanabiliriz. Bunun dışında da, oldukça güçlü değişkenler ve objelerle başa çıkmamızı sağlayan birçok *construct* sağlar.
- **Dinamik**: Statik programlama dillerinin aksine dinamik bir programlama dili, statik dillerin *compile time*'da derlediği birçok şeyi *runtime*'da derler. Bunun avantajları olduğu kadar dezavantajları da  bulunmakla birlikte bizlere *dynamic typing*, *late binding*, *reflection*, *functional programming*, *object runtime alteration*, *closures* gibi güçlü özellikleri kullanma imkanı verir. Bu terimleri bilmiyorsanız bile endişelenmenize hiç gerek yok çünkü bu kurs sonunda öğrenmiş olacaksınız.

- **Türden bağımsız değişken**: Bir değişken, türlere bağlı olmadan oluşturulabilir. Herhangi bir türü, bir değişkene yeniden atayabiliriz. Örneğin, *string* tutan bir değişkene bir *integer* değişken atayabiliriz.

- **Loosely typed**: *Strong typing* dillerin aksine, *loosely (or weakly) typed* diller bir nesnenin türünü zorla kabul ettirmez. Tür konusunda esnekliğe izin verir fakat *type safety* ve *type checking (JavaScript'in en üst noktasına inşa edilen bir konu olan TypeScript)* 'e izin vermez. 

- **Interpreted**: C, Java yada Go tarzı dillerin aksine, program çalışmaya başlamadan önce derleme aşamasına ihtiyaç duymayan diller genellikle *interpreted language* olarak bilinir. Pratikte, performans sebeplerinden dolayı tarayıcılar çalıştırmadan önce JavaScript kodlarını derler fakat bu sizi şeffaflaştırmakla beraber herhangi bir ek adım bulundurmaz.
- **Multi-Paradigm**: Java, kullanıcılarını nesne yönelimli programlamaya zorlar. Aynı şekilde C'de bizleri *imperative programlama* kullanmak zorunda bırakır. Bu tarz dillerden farklı olarak JavaScript, bizleri herhangi bir programlama paradigması kullanmaya zorlamaz. Nesne yönelim paradigmasını, *prototype*leri ve yeni (ES6 itibariyle) sınıf söz dizimi kurallarını (syntax) kullanarak da kod yazabilirsiniz. *First-class* fonksiyonlarıyla functional programming tarzında JavaScript yazabileceğimiz gibi, *Imperative* tarzda bile yazabiliriz.

Eğer merak ediyorsanız, *JavaScript'in, Java ile herhangi bir ilgisi yoktur.* Sadece kötü bir isim seçimi fakat bununla yaşamak zorundayız


### Kitabın İçeriği

1. [JavaScript Tarihi](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/master/Turkish/1.JavaScript%20Tarihi.md)
2. [Sadece JavaScript](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/master/Turkish/2.Sadece%20JavaScript.md)
3. [JavaScript Söz Dizimine Giriş](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/master/Turkish/3.JavaScript%20S%C3%B6z%20Dizimine%20Giri%C5%9F.md)
4. [Noktalı Virgül Kullanımı](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/master/Turkish/4.Noktal%C4%B1%20Virg%C3%BCl%20Kullan%C4%B1m%C4%B1.md)
5. [Değerler (Values)](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/master/Turkish/5.De%C4%9Ferler(Values)%20.md)
6. [Değişkenler (Variables)](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/master/Turkish/6.De%C4%9Fi%C5%9Fkenler%20(Variables).md)
7. [Değişken Tipleri](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/master/Turkish/7.De%C4%9Fi%C5%9Fken%20Tipleri.md)
8. [İfadeler (Expressions)](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/master/Turkish/8.%C4%B0fadeler%20(Expressions).md)
9. [İşlemler (Operators)](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/master/Turkish/9.%C4%B0%C5%9Flemler%20(Operators).md)
10. [Öncelik Kuralları](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/master/Turkish/10.%C3%96ncelik%20Kurallar%C4%B1.md)
11. [Karşılaştırma Operatörleri](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Comparison%20operators.md)
12. [Koşullu İfadeler](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/master/Turkish/12.Ko%C5%9Fullu%20%C4%B0fadeler.md)
13. [Diziler (Arrays)](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/master/Turkish/13.%20Diziler%20(Arrays).md)
14. [Stringler](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Strings.md)
15. [Döngüler](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Loops.md)
16. [Fonksiyonlar](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Functions.md)
17. [Ok Fonksiyonları (Arrow functions)](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Arrow%20functions.md)
18. [Objeler](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Objects.md)
19. [Nesne Özellikleri](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Object%20Properties.md)
20. [Nesne Metodları ](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Object%20Methods.md)
21. [Sınıflar](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Classes.md)
22. [Kalıtım (Inheritance)](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Inheritance.md)
23. [Asenkron Programlama ve Geri Dönüşler](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Asynchonous%20Programming%20and%20Callbacks.md)
24. [Promises](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Promises.md)
25. [Async ve Await](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Async%20and%20Await.md)
26. [Değişken Kapsamı (Variable Scope)](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Variable%20scope.md)
27. [Conclusion](https://github.com/karacamelihcan/The-JavaScript-Beginner-s-Handbook-2020-Edition/blob/initial-create/English/Conclusion.md)


Eğer isterseniz kitabı [orijinal](https://www.freecodecamp.org/news/the-complete-javascript-handbook-f26b2c71719c/) dilinde de takip edebilirsiniz.
