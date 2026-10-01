# Nearby Devices Scanner

Мультипротокольный сканер устройств вокруг: Wi-Fi, Bluetooth Classic, BLE, локальная сеть.
Работает с Python-бэкендом и веб-интерфейсом.

## Что сканирует
- 📡 **Wi-Fi** — окружающие точки доступа (SSID, BSSID, RSSI)
- 🌐 **Локальная сеть** — устройства в вашей подсети (IP, MAC, hostname)
- 📶 **BLE** — Bluetooth Low Energy устройства (имя, RSSI, UUID)
- 🔵 **Bluetooth Classic** — классические BT устройства

## Установка

```bash
git clone https://github.com/ВАШ_НИК/nearby-devices-scanner.git
cd nearby-devices-scanner
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
