<div align="center">
  <img src="assets/logo.png" width="100" alt="DARYANTO.ID">
  <h1>DARYANTO.ID EA v1.36</h1>
  <p><b>Anti Double OP + Trailing Profit Runner MT5</b></p>
  <p>
    <img src="https://img.shields.io/badge/Platform-MT5-0075FF?style=for-the-badge">
    <img src="https://img.shields.io/badge/Version-1.36-39FF14?style=for-the-badge">
    <img src="https://img.shields.io/badge/License-Personal_Use-orange?style=for-the-badge">
  </p>
</div>

## 🔥 Fitur Utama
- **Anti Double OP**: GlobalVariable `Daryanto_LastTrade` cegah entry dobel pas refresh chart
- **Trailing Profit Runner**: Close pas profit turun 25% dari puncak. Biarin trend jalan
- **Smart BE + TS**: BE +3 point di +8 point. TS start +12 point step 5 point
- **Filter Ketat**: Jam, news, spread, sinyal basi, SL invalid, STOP_LEVEL
- **Panel Mobile**: Auto compact di HP. Dark mode sultan

## ⚙️ Instalasi Cepat
1. Pasang `DARYANTO.ID Indicator v2.41` dulu
2. Copy `DaryantoEA_v1.36.ex5` ke `MQL5/Experts/`
3. Attach ke XAUUSD M5. Allow Algo Trading
4. Risk default 1%. Cocok modal $500+

## 📊 Input Penting
| Parameter | Default | Keterangan |
| --- | --- | --- |
| `InpRiskPercent` | 1.0 | Risk per trade |
| `InpUseTrailingProfit` | true | Aktifkan Profit Runner |
| `InpTrailProfitStart` | 1500 | Mulai track di +15.0 point |
| `InpTrailProfitDrop` | 25.0 | Close drop 25% dari peak |

## ⚠️ Disclaimer
Trading berisiko. Backtest dulu di demo. Dev tidak tanggung jawab atas loss.

**Support**: [@daryantoid](https://t.me/daryantoid)