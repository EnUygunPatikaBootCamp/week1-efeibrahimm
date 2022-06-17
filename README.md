# Week1Assignment

```
 Soru 1: OOP nedir? Ne amaçlı kullanılır?
 ```
- OOP bir yazılım geiştirme paradigmasıdır.
- Yazılımlar geliştikçe karmaşıklığı ve boyutu artar haliyle kodun bakım ve karmaşılığını azaltmak amacıyla kullanılır
```
Soru 2: Polymorphism ne amaçlı kullanılır?
```
Polimorfizm bir çok forma sahip olma ( çok biçimlilik ) yeteğine sahip anlamına gelir. Yani sınıfın ortak metodlarını paylaşırken methodların değişebileceği (override edileceği) örüntyü ifade eder. 
```
Soru 3: Bir metodun private, protected ya da public olması kavramlarını açıklayınız.
```
- public : bir değişkenin, parametrenin veya methodun her yerden erişilebildiğini kullanılabildiğini temsil eder.
- private :  bir değişkenin, parametrenin veya methodun sadece ilgili classtan erişilebildiğini ve kullanılabildiğini temsil eder.
- protected :  bir değişkenin, parametrenin veya methodun sadece ilgili classtan ve classtan miras alan alt sınıflardan erişilebildiğini ve kullanılabildiğini temsil eder.
 ```
 Soru 4: (Abstraction) Soyutlama nedir?
 ```
- Soyutlama üst sınıfın adlandırılmış bir yöntemi olduğu, ancak görevleri tamamlamak için alt sınıflarına ihtiyaç duyması durumudur. örnek olarak her insanın ses telleri ortaktır fakat frekansları değişiktir veya her marka bir ürün üretir ama slognı farklıdır gibi örneklerde aslında soyutlama kullanılabilir. Soyut sınıfta tanımlanan tüm methodlar aynı olacak şekilde inherit edilen tüm childlarda kullanılmalıdır.

```
Bir e-ticaret projesinde, sisteme giriş yapacak farklı kullanıcı türleri mevcuttur. Bu türler üç başlıkta toplanabilir. Müşteri (Client), Satıcı (Merchant), Sistem Yöneticisi (Admin) Her başlıktaki kullanıcı türleri için aşağıdaki koşullar mevcuttur:

Tüm kullanıcıların TCKN numarası olmalıdır.
Tüm kullanıcıların ad soyad ve e-posta bilgisi olmalıdır.
Müşterilerin eşsiz (unique) müşteri no olmalıdır.
Satıcıların eşsiz (unique) satici no olmalıdır.
Sistem yöneticilerinin kullanıcı idsi olmalıdır.
Satıcıların cep telefonu onaylı olup olmadığı bilgisi olmalıdır.
```
![Alt text](https://github.com/EnUygunPatikaBootCamp/week1-efeibrahimm/blob/main/diagram.jpg?raw=true "UML Diagram")
