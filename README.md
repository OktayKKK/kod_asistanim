# Proje Yazarı: Oktay KIRBIYIK
# Projenin Adı: Kod-Asistan v0.1
## Projenin Amacı: Kullanıcılara günlük işlerinde (hesaplama, selamlama vb.) yardımcı olacak bir dijital asistan tasarlamak
## Projenin Hedefleri: Bu asistanın ilerleyen zamanlarda hangi özellikleri kazanacağını v1.0 Akıllı Menü, v2.0 Veri Saklama.

**KRİTİK EŞİK ALGORİTMASI**

1. BAŞLA.
2. Saat değişkenini 1 olarak belirle.
3. Su seviyesini sensörden oku.
4. Su seviyesi 50 metreden küçük veya eşitse:
   - Kapakları kapalı tut.
   - Saat değerini 1 artır.
   - Adıma 3 e geri dön.
5. DEĞİLSE:
   - Döngüyü bitir.
   - Tahliye saatini ekrana yazdır.
   - Kritik su seviyesini ekrana yazdır.
6. DUR.

**Elle çalıştırma takip tablosu**
Verilen sensör verileri sırasıyla 42 m, 48 m ve 55 m'dir.

Adım	Saat	Su seviyesi	   Koşul (su_seviyesi <= 50)	         İşlem
1	   1	      42 m	        Doğru	                     Kapaklar kapalı, saat 2 olur.
2	   2	      48 m	        Doğru	                     Kapaklar kapalı, saat 3 olur.
3	   3	      55 m	        Yanlış	                     Döngü kırılır, kritik bilgiler yazdırılır.
