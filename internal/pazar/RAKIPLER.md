# Rakipler

Şirket içi. Public değil. Tarama: 16 Ağustos 2026.

## Ticari UEBA / SIEM içi

| Ürün | Site | Aktif | Kapalı ağ | CLI vs konsol |
|------|------|-------|-----------|----------------|
| Exabeam | https://www.exabeam.com/ | Evet. 2025 Gartner SIEM Lideri | New-Scale GCP. LogRhythm SIEM yalnız on-prem | SOC konsol |
| Splunk UBA (standalone) | Splunk help EOS notu | **Satışa kapalı** (EOS 12 Ara 2025, EOL 31 Oca 2027) | Eski on-prem | Ayrı UBA UI |
| Splunk ES Premier UEBA | https://www.splunk.com/en_us/products/user-and-entity-behavior-analytics.html | Evet | On-prem ES mümkün | SOC + SPL |
| Microsoft Sentinel UEBA | Azure docs | Evet, Sentinel’e dahil | **Bulut. Air-gap yok** | Azure portal |
| Securonix | https://www.securonix.com/ | Evet | SaaS / BYO-AWS. Saf air-gap yok | SOC + ajan |
| Gurucul | https://gurucul.com/products/user-and-entity-behavior-analytics-ueba/ | Evet | SaaS, cloud, on-prem, hibrit iddiası | SOC konsol |
| Varonis | https://www.varonis.com/platform/data-centric-ueba | Evet | Self-hosted 31 Ara 2026 EOL → SaaS | Konsol; **otomatik düzeltme** |
| Cortex XSIAM | https://www.paloaltonetworks.com/cortex/cortex-xsiam | Evet | Sunucu on-prem yok. Tam air-gap yok | SOC, XQL |
| CrowdStrike Falcon UEBA | https://www.crowdstrike.com/en-us/platform/next-gen-identity-security/ueba/ | Evet | %100 cloud-native. Kapalı LAN native yok | Falcon konsol |
| Elastic Security | https://www.elastic.co/security/siem | Evet | **Air-gap resmi destek** | Kibana; CLI mümkün, konsol-öncelikli |
| ManageEngine Log360 | https://www.manageengine.com/log-management/ueba-threat-detection.html | Evet | On-prem, KOBİ | Web konsol |

## OSS / NDR

| Ürün | Site | Aktif | Not |
|------|------|-------|-----|
| Wazuh | https://wazuh.com/ | Evet | OSS XDR/SIEM. UEBA değil. Nisan 2026 #35422: kullanıcı tam UBA istiyor |
| OpenSearch Security Analytics | OpenSearch docs | Evet | Sigma + korelasyon; UEBA değil |
| Vectra | https://www.vectra.ai/ | Evet | NDR. Komşu |
| Darktrace | https://www.darktrace.com/ | Evet | NDR/OT, appliance, air-gap iddiası, **Autonomous Response** |

## Komşu (kapalı ağ / TR)

| Ürün | Site | Not |
|------|------|-----|
| Exeon.UEBA | https://exeon.com/ueba/ | İsviçre. On-prem/air-gap. En yakın ticari Avrupa komşu |
| SecureVisio | https://securevisio.com/ | Avrupa SIEM+SOAR+UEBA |
| Logsign | https://www.logsign.com/ | TR, SIEM+UEBA+TDIR, konsol |
| LogAlarm | https://www.logalarm.com.tr/ | Yerli SIEM/log; tam UEBA sayfası yok |
| OpenUBA | https://github.com/GACWR/OpenUBA | ~509 yıldız, BETA. CLI-first değil |
| containrrr/Watchtower | https://github.com/containrrr/watchtower | **İsim çarpması.** Docker güncelleyici. 17 Ara 2025 arşiv |
