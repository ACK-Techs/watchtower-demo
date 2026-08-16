# Özet

Şirket içi. Public değil. Tarama: 16 Ağustos 2026.

## Bu pazar nedir

UEBA artık bağımsız bir kutu değil. Gartner SIEM karesinin (8 Eki 2025) iç modülü. Alıcı “SIEM + davranış + SOAR + ajanik AI” paketi görüyor. Anlatı: agentic SOC, otomatik triyaj, otomatik yanıt. Watchtower’ın muhafazakâr duruşu (LLM karar vermez, otomatik müdahale yok) bu anlatının tersi — hem boşluk hem satış riski.

Yeni nesil UEBA çoğunlukla bulut kiracısı + on-prem toplayıcı. Gerçek air-gap seyrek.

## Benzer ürün var mı

Ticari UEBA var ve aktif: Exabeam, Splunk ES Premier, Microsoft Sentinel UEBA, Securonix, Gurucul, Varonis, Cortex XSIAM, CrowdStrike Falcon, Elastic. Splunk standalone UBA **satışa kapalı** (EOS 12 Ara 2025, destek sonu 31 Oca 2027).

**CLI-first ticari UEBA bu taramada yok.** KOBİ on-prem: ManageEngine Log360, Türkiye’de Logsign — ikisi de konsol. Wazuh on-prem ve ucuz ama UEBA değil.

Kapalı ağda en yakın ticari komşu: Exeon.UEBA (İsviçre, air-gap). NDR komşuları Darktrace ve Vectra. Docker Watchtower (containrrr) **başka ürün**; 17 Ara 2025 arşivlendi, ~24.700 yıldız — SEO’yu ezer.

## Watchtower’ın durduğu yer

Boşluk: internetsiz LAN’de, Splunk ES Premier kadar ağır olmayan, Wazuh’un vermediği davranış baseline + açıklanabilir skor; karar LLM’de değil. Nisan 2026 Wazuh tartışması OSS UBA katmanı arıyor — overlay talebi kanıtlı.

Risk: isim çarpması; kategori rafta yok (SIEM yanında satılmalı); 2026 CISO slaytı ajanik SOC; 7545 yerli yetki belgesiz kamu ihalesi kapanır.
