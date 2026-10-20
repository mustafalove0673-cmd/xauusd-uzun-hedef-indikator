# MARK XAUUSD UZUN HEDEF - TradingView Indicator

XAUUSD (altin) icin UZUN HEDEFLI AL/SAT sinyalleri ureten Pine v6 indikatoru.

## Amac
- Yalniz buyuk hareket baslangicinda sinyal uretir.
- Kisa yerel (lokal) sinyaller filtrelidir.
- Her sinyal uzun hedefe (TP2) ulasmayi hedefler.
- Repaint YOK (barstate.isconfirmed + lookahead_off).

## Filtreler
- 4H trend (EMA200) hizasi
- Sikisma (compression) onayi
- Hacim onayi
- Derin sweep (bariz likidite supurmesi)
- Buyuk govde
- Sinyaller arasi minimum bar mesafesi

## Kurulum
1. TradingView'da Pine Editor ac.
2. Bu dosyanin icerigini yapistir.
3. "Add to Chart" ile ekle.

## Parametreler
- ATR periyodu, sikisma esigi, govde carpani, hacim carpani, min sweep derinligi
- TP1/TP2/SL carpanlari
- 4H trend, hacim, sikisma, derin sweep filtreleri ac/kapat
