# python
Bu kod, bir PyQt5 arayüzü oluşturarak basit bir hesap makinesi uygulamasını temsil eder. Kullanıcı arayüzünde bir grup içinde sayılar, operatörler ve ekran bulunmaktadır. Kullanıcı arayüzünde bir grup içinde sayılar, operatörler ve ekran bulunmaktadır. Kullanıcı bu düğmelere tıkladığında veya operatörleri kullandığında ekranın içeriği değişir ve kullanıcı tarafından girilen ifadeleri gösterir.

Bu kodun açıklaması şu şekildedir:
Öncelikle QT Designer kullanarak arayüzün taslağını oluşturdum. Daha sonra CMD ye bazı komutlar yazarak .ui uzantılı dosyayı .py koduna çevirdim. 
setupUi: Kullanıcı arayüzünü oluşturan PyQt5 UI kodunu içerir. Butonlar, ekran ve grup kutuları gibi arayüz öğeleri burada tanımlanır ve düzenlenir.
retranslateUi: Arayüzdeki metinleri yerelleştirmek için kullanılır. Bu metinler, kullanıcı arabirimindeki düğme etiketleri ve grup kutusu başlığı gibi öğelerdir.
Butonlara tıklama olayları, kullanıcının sayıları ekran alanına eklemesini veya operatörleri eklemesini sağlar.
clear_screen: Ekran alanını temizler, yani içeriğini siler.
on_operator_click: Operatör düğmelerine tıklandığında çağrılır ve ilgili operatörü ekran alanına ekler.
calculate_result: Kullanıcının girdiği ifadeyi değerlendirir ve sonucu ekran alanına yazar. Bu işlem eval fonksiyonu kullanılarak gerçekleştirilir. Ancak, eval fonksiyonunun güvenlik riskleri olabileceği için dikkatli kullanılmalıdır.








