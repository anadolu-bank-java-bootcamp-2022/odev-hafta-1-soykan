# Liskov Substitution Principle

## Nedir?
Liskov Substitution Principle yani Liskov'un Yer Değiştirme Prensibine göre bir programda üst sınıf nesnesine ait bir referansı, üst sınıfının alt sınıfı olan bir nesne ile değiştirdiğimizde programın olması gerektiği gibi yani bozulmadan çalışmaya devam etmesi gerektiğini ortaya koyan bir prensiptir.
## Ne Amaçla Ortaya Çıkmıştır?
Inheritance (üst sınıftan miras alma) gerçekleştiğinde alt sınıftan (child class) beklenen şey üst sınıfa ait şeyleri (metotlar ve alanları) olduğu gibi miras almasıdır. Alt sınıf (child class) üst sınıfın davranışlarını genişletebilir ama daraltmamalıdır. Ortaya çıkış amacı bu prensibe uyulmadığında farkedilmesi güç hatalar ortaya çıkıyor olmasıdır.
## Nasıl Uygulanır
Miras alan sınıf yani alt sınıf (child class), üst sınıftan aldığı özellikleri, üst sınıfla uyumu bozmayacak şekilde genişletir şekilde kodlanmalıdır. Örneğin parametre olarak üst sınıfı alan bir metota onun alt sınıflarından bir nesnenin referansı parametre olarak verilip gönderildiğinde program uyumlu bir şekilde çalışabilir şekilde tasarlanmalıdır.
