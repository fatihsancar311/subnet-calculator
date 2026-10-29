# Subnet Calculator (IPv4 / CIDR)

Bağımlılıksız, tarayıcıda çalışan **IPv4 subnet (alt ağ) hesaplayıcı**. / A dependency-free **IPv4 subnet and CIDR calculator** that runs in your browser.

**Canlı demo / Live demo:** https://fatihsancar311.github.io/subnet-calculator/  
**Rehber, CIDR tablosu ve SSS (Türkçe):** https://teknikdigital.com/subnet-hesaplama/

## Özellikler
- `192.168.1.10/24` ya da `192.168.1.10 255.255.255.0` biçiminde giriş
- Ağ adresi, yayın (broadcast), ilk/son kullanılabilir host, alt ağ maskesi, wildcard maskesi
- Toplam adres ve kullanılabilir host sayısı (/31 ve /32 istisnaları dahil)
- IP sınıfı ve türü (özel, loopback, link-local, CGNAT, dokümantasyon, multicast vb.)
- İkili (binary) gösterim: ağ ve host bitleri renkli
- Alt ağlara bölme (ilk 64 alt ağ listelenir)
- Sonuçları panoya kopyalama
- Tek dosya (`index.html`), harici bağımlılık ya da derleme adımı yok; girilen adresler hiçbir yere gönderilmez

## Kullanım
```bash
git clone https://github.com/fatihsancar311/subnet-calculator.git
cd subnet-calculator
# index.html dosyasını tarayıcıda açın
```

## Notlar
- Araç yalnızca **IPv4** içindir. IPv6 için önek planlaması farklı çalışır.
- A/B/C sınıfı gösterimi bilgilendirme amaçlıdır; günümüzde CIDR kullanılır.

## English
Enter an address with a prefix (`10.0.0.0/8`) or a mask (`192.168.1.10 255.255.255.0`). The tool shows network and broadcast addresses, masks, usable host range and counts, an annotated binary view, and can split the network into smaller subnets. No dependencies, no network requests.

## Lisans / License
[MIT](LICENSE) © Teknik Digital

---
Geliştiren: [Teknik Digital](https://teknikdigital.com) — web, yazılım ve SEO çözümleri.
