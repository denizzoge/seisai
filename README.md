# SeisAI

AI destekli gerçek zamanlı sismik analiz ve erken uyarı MVP'si.

## Problem

Türkiye yüksek deprem riski taşıyan bir ülke olmasına rağmen, kritik altyapılar için erişilebilir ve düşük gecikmeli erken uyarı sistemleri sınırlıdır.

## Çözüm

SeisAI, sismik zaman serisi verilerini analiz ederek P-wave başlangıcını tespit etmeyi ve S-wave gelmeden önce erken uyarı üretmeyi hedefleyen AI destekli bir sismik analiz platformudur.

## Mevcut MVP

- Sentetik sismik sinyal simülasyonu
- P-wave / S-wave modelleme
- Threshold tabanlı event detection
- Erken alarm zamanı hesaplama
- Türkiye sismik risk görselleştirmesi
- Streamlit tabanlı dashboard

## Teknolojiler

- Python
- Streamlit
- NumPy
- Pandas
- Matplotlib

## Yol Haritası

1. ObsPy ile gerçek miniSEED veri okuma
2. STA/LTA tabanlı P-wave detection
3. Machine learning tabanlı event classification
4. Canlı sismik istasyon verisi entegrasyonu
5. Kritik altyapılar için API ve alarm sistemi

## Hedef Kullanım Alanları

- Sanayi tesisleri
- Veri merkezleri
- Enerji altyapıları
- Metro ve raylı sistemler
- Akıllı şehir sistemleri
- Sigorta ve risk analitiği

## Kurucu

İTÜ Jeofizik Mühendisliği öğrencisi tarafından geliştirilen erken aşama teknik MVP.
