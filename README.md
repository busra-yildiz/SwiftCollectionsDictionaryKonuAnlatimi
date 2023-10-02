# SwiftCollectionsDictionaryKonuAnlatimi
Dictionary, anahtar-değer çiftlerini depolayan bir koleksiyon türüdür. Her bir anahtarın bir değeri vardır ve bu anahtarlar benzersiz olmalıdır. 
Dictionary'ler genellikle çeşitli verileri gruplamak, depolamak ve erişmek için kullanılır. Swift'in Dictionary türü, diğer dillere göre oldukça 
güçlüdür ve çok çeşitli kullanım senaryolarına uyar.

Bir Swift Dictionary örneğini aşağıda bulabilirsiniz:
var meyveFiyatlari = ["Elma": 2.0, "Muz": 1.0, "Portakal": 1.5]

Bu örnekte, meyveFiyatlari adlı bir Dictionary oluşturduk. Dictionary, köşeli parantezler içinde anahtar ve değer çiftlerinden oluşur. 
Her bir anahtar, bir değerle ilişkilendirilir. Yukarıdaki örnekte, "Elma" anahtarı 2.0 değeriyle, "Muz" anahtarı 1.0 değeriyle ve "Portakal" 
anahtarı 1.5 değeriyle ilişkilendirilmiştir.

Dictionary'ye değer eklemek, bir anahtarın karşılığına değer atamak veya bir anahtara erişmek için aşağıdaki gibi yöntemler kullanılabilir:
// Dictionary'ye yeni bir anahtar-değer çifti eklemek
meyveFiyatlari["Üzüm"] = 2.5

// Dictionary'den bir değeri okumak
let elmaFiyati = meyveFiyatlari["Elma"] // elmaFiyati şimdi 2.0 değerini içerir

// Dictionary'den bir anahtarı kaldırmak
meyveFiyatlari.removeValue(forKey: "Muz")

Dictionary'lerde dikkat edilmesi gereken birkaç önemli nokta:

Anahtarlar benzersiz olmalıdır: Bir Dictionary içinde her bir anahtarın yalnızca bir kez bulunması gerekir. Aynı anahtara sahip birden fazla değer 
eklemek mümkün değildir.
Değerler farklı türlerde olabilir: Dictionary içindeki değerler aynı türde olmak zorunda değildir. Örneğin, bir Dictionary içinde hem sayılar hem de
metin dizeleri depolayabilirsiniz.
Dictionary'ler sırasızdır: Swift Dictionary'ler, anahtar-değer çiftlerini eklediğiniz sırayı korumaz. Yani, Dictionary içindeki öğeler sıralı değildir.
Dictionary'ler, veri organize etmek ve hızlı bir şekilde erişmek için kullanışlıdır. Özellikle çeşitli bilgileri gruplamak veya sözlük benzeri veri 
yapıları oluşturmak için idealdirler. Swift dilinin bu veri yapısı, programlama projelerinizi daha etkili bir şekilde yönetmenize yardımcı olabilir.
