# Geliştirme kaydı

## 2026-11-16T16:47:31+03:00

Island Controls klasörünü Git çalışma ağacı olarak hazırladım. 7fe506e kaynak dosyasının Windhawk kataloğundaki ve kurulu 1.4.0 dosyasındaki Git nesne kimliğiyle eşleştiğini kontrol ettim. Hedef depo boştu. Derleme ve pencere davranışı henüz kontrol edilmedi.

## 2026-11-16T16:55:35+03:00

Oyun algılama, Windows Game Bar ile tam yürütülebilir dosya yolu eşleşmesi ve hedef monitörü kaplayan ön plan penceresi şartlarıyla uygulandı. Tam ekran oyundaki şerit 5 px (100% ölçek) yüksekliğinde ve tıklama geçiren bir yüzey. PreviousConfigs.txt dosyasındaki 100 ayar varsayılanlara işlendi. x86 ve x64 Windhawk 1.7.3 derlemeleri geçti. Ayrı doğrulama programı gerçek RDR2 penceresinin oyun ve tam ekran koşullarını geçtiğini, normal bir tam ekran pencerenin oyun olarak algılanmadığını, küçük pencerenin ve farklı monitörün dışlandığını doğruladı. Bu kayıt anında mod Windhawk'ta etkinleştirilmedi.
