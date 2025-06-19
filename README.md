# CRTY GameLoop Optimizer

**CRTY GameLoop Optimizer**, Windows üzerinde Tencent GameLoop için FPS artışı ve performans iyileştirmesi sağlayan, kullanımı kolay bir PowerShell tabanlı optimizasyon aracıdır.

---

## Özellikler

- CPU güç planını yüksek performansa ayarlar.
- Superfetch (SysMain) servisini kapatarak gereksiz arka plan işlemlerini azaltır.
- Gereksiz sistem servislerini devre dışı bırakır.
- GameLoop işlem önceliğini yüksek yaparak daha akıcı oyun deneyimi sağlar.
- TCP autotuning'i kapatarak ağ gecikmesini azaltmaya yardımcı olur.
- Kolayca yapılan optimizasyonları geri alma imkanı.

---

## Kullanım

1. PowerShell'i **Yönetici olarak** açın.
2. `CRTY_GameLoop_Optimizer.ps1` dosyasını indirin veya içeriği kopyalayın.
3. Scripti çalıştırın:
   ```powershell
   .\CRTY_GameLoop_Optimizer.ps1
