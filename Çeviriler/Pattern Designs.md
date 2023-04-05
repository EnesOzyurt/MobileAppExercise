# Tasarım Desenleri (Design Patterns)

>   Yazılım mühendisliğinde bir **tasarım deseni**, yazılım tasarımında yaygın olarak ortaya çıkan bir soruna yönelik tekrarlanabilir genel bir çözümdür. Bir tasarım deseni doğrudan koda dönüştürülebilen bitmiş bir tasarım değildir. Birçok farklı durumda kullanılabilecek bir sorunun nasıl çözüleceğine ilişkin bir açıklama ya da taslaktır.

## Tasarım Desenlerinin Kullanım Alanları (Uses of Design Patterns)

>   Tasarım desenleri, sınanmış, kanıtlanmış geliştirme örnekleri sağlayarak geliştirme sürecini hızlandırabilir. Etkili yazılım tasarımı, uygulamanın ilerleyen aşamalarına kadar görünür hale gelmeyebilecek sorunların dikkate alınmasını gerektirir. Tasarım desenlerinin yeniden kullanılması, büyük sorunlara neden olabilecek ince sorunların önlenmesine yardımcı olur ve desenlere aşina olan kodlayıcılar ve mimarlar için kodun okunabilirliğini artırır.

>   Çoğu zaman, insanlar yalnızca belirli yazılım tasarım tekniklerinin belirli sorunlara nasıl uygulanacağını anlarlar. Bu tekniklerin daha geniş bir yelpazedeki sorunlara uygulanması zordur. Tasarım desenleri, belirli bir soruna bağlı ayrıntılar gerektirmeyen bir formatta belgelenmiş genel çözümler sağlar.

>Buna ek olarak, desenler geliştiricilerin yazılım etkileşimleri için iyi bilinen, iyi anlaşılan isimler kullanarak iletişim kurmalarını sağlar. Yaygın tasarım desenleri zaman içinde geliştirilebilir, bu da onları geçici tasarımlardan daha sağlam hale getirir.

## Yaratıcı tasarım desenleri (Creational design patterns)

>   Yazılım mühendisliğinde, oluşturma tasarım desenleri, nesne oluşturma düzenekleriyle ilgilenen, nesneleri duruma uygun bir şekilde oluşturmaya çalışan tasarım desenleridir. Nesne oluşturmanın temel biçimi, tasarım sorunlarına veya tasarıma ek karmaşıklığa neden olabilir. Oluşturma tasarım desenleri, bu nesne oluşumunu bir şekilde denetleyerek bu sorunu çözer.

### Soyut İmalat (Abstract Factory)

### Niyet

>  * Somut sınıflarını belirtmeden ilgili veya bağımlı nesne aileleri oluşturmak için bir arayüz sağlayın.
>  * Birçok olası "altyapıyı" ve bir "ürün" torbasını kapsayan bir düzen.
>  * `new` işleçinin zararlı olduğu kabul edilir.

### Sorun (Problem)

>   

>   **Translated with www.DeepL.com/Translator (free version)**