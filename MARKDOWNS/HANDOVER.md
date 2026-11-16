# Devir

Son güncelleme: 2026-11-16T16:55:35+03:00

`main` dalı, Windhawk kataloğundaki Dynamic Island for Windows 1.4.0 ile kaynak dosyası birebir eşleşen upstream `7fe506e` commit'inden türetilmiştir. `origin`, `yagizxzf/XZF-Island-Controls`; `upstream`, `devcode90/Dynamic-Island-for-Windows`.

Modun yeni kimliği `xzf-island-controls`, yerel Windhawk kaydı `local@xzf-island-controls`. [Kaynak](../xzf-island-controls.wh.cpp), oyunun pencere sınırlarını hedef monitörle karşılaştırır ve çalıştırılabilir dosyasının tam yolunu Windows Game Bar kayıtlarından doğrular. Tam ekran oyunda giriş almayan yaklaşık 5 px yüksekliğinde bir şerit gösterir. Normal uygulamalarda eski boşta gizlenme kuralı kullanılır. Game Bar kaydı olmayan oyunlar sınıflandırılamaz.

`PreviousConfigs.txt` içindeki 100 değer doğrudan modun varsayılanlarına aktarıldı. Kaynak dosyası Windhawk 1.7.3 ile x86 ve x64 olarak derlendi. Açık RDR2 penceresi hem ekranı kaplama hem Game Bar eşleşmesi kontrollerini geçti. Normal çerçevesiz pencere oyun olarak işaretlenmedi. Küçük pencere ve farklı monitör kontrolleri geçti.

Sıradaki adım yerel Windhawk kaydını etkinleştirmek ve gerçek mod çalışırken görünümü doğrulamak. Geliştirme kapsamı [ROADMAP.md](ROADMAP.md) dosyasında.

Devirde sırasıyla [AGENTS.md](AGENTS.md), bu dosya, [ROADMAP.md](ROADMAP.md) ve [PROGRESSION.md](PROGRESSION.md) son kayıtlarını oku.
