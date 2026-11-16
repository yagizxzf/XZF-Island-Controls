# Devir

Son güncelleme 2026-11-16T21:38:24+03:00

`main` dalı, Windhawk kataloğundaki Dynamic Island for Windows 1.4.0 ile kaynak dosyası birebir eşleşen upstream `7fe506e` commit'inden türetilmiştir. `origin` uzak deposu `yagizxzf/XZF-Island-Controls`, `upstream` uzak deposu `devcode90/Dynamic-Island-for-Windows`.

[Mod kaynağı](../xzf-island-controls.wh.cpp) Windhawk 1.7.3 altında `local@xzf-island-controls` kimliğiyle etkin. Kurulu sürüm `1.4.0.4`. `PreviousConfigs.txt` yerel ayar girdisi. Dosyadaki 100 değer hem varsayılanlara işlendi hem kurulu modda doğrulandı.

Oyun algılama, Island ile aynı monitörü kaplayan ön plan penceresinin dosya yolunu Windows Game Bar kaydıyla eşleştirir. Game Bar kaydı olmayan oyunlar bu davranışı alamaz. Tam ekran oyun 100% ölçekte 5 px şerit bırakır. Fareyle açılan panel, fare ayrıldığında mevcut animasyon stilinde şeride döner. RDR2 açıkken şerit ölçüldü, hover ve dönüş gözlendi ve kullanıcı son kapanış animasyonunu doğruladı. Normal uygulamalar olağan boşta gizlenme ayarını izler.

Genişletilmiş medya panelinin alt satırı, seçili kaynak Windows ses oturumuyla eşleştiğinde kaynak uygulamanın sesini ve sessiz durumunu değiştirir. YouTube Music ve XZF Browse oturum eşleşmeleri doğrulandı. Ayrı Windows ses oturumu testinde uygulama sesi ve sessiz ayarı değişirken ana sesin sabit kaldığı doğrulandı. x86 ve x64 derlemeleri başarılı.

Parça değişiminde otomatik açılma YouTube Music masaüstü uygulamasının Windows kimliğiyle sınırlı. Otomatik açılma düğmesi ve hariç tutma listesi geçerli. Geçiş testi masaüstü istemcisini, tarayıcıyı, ayarları ve elle kaynak değişimini kapsadı.

Kurulum ve derleme için [README.md](../README.md) ile [AGENTS.md](AGENTS.md) dosyalarına bak. Belirlenen işler [ROADMAP.md](ROADMAP.md) dosyasında. Devirde sırasıyla [AGENTS.md](AGENTS.md), bu dosya, [ROADMAP.md](ROADMAP.md) ve [PROGRESSION.md](PROGRESSION.md) son kayıtlarını oku.
