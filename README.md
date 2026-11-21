
# IoT Monitoring Suhu dan Kelembapan Berbasis Node-RED

## Deskripsi
Project ini merupakan sistem monitoring suhu dan kelembapan berbasis Internet of Things (IoT) menggunakan Node-RED.

Data sensor dikirim melalui MQTT, kemudian diproses dan ditampilkan pada dashboard secara real-time.

## Teknologi yang Digunakan
- Node-RED
- MQTT
- Mosquitto
- Python
- SQLite
- HTML, CSS, dan JavaScript
- WebSocket
- REST API

## Fitur
- Monitoring suhu dan kelembapan secara real-time.
- Komunikasi data menggunakan MQTT.
- Dashboard monitoring sensor.
- REST API untuk mengambil data sensor.
- Autentikasi API Key.
- Komunikasi WebSocket.
- Penyimpanan riwayat sensor menggunakan SQLite.

## Database
Database menggunakan SQLite dengan nama `iot_sensor.db` dan tabel `sensor_history`.

## File Project
- `flows.json`: konfigurasi flow Node-RED.
- `simulasi_esp32.py`: program simulasi sensor.

## Cara Menjalankan
1. Jalankan Mosquitto MQTT Broker.
2. Jalankan Node-RED.
3. Import file `flows.json` ke Node-RED.
4. Jalankan program `simulasi_esp32.py`.
5. Buka dashboard untuk melihat data sensor.

## Pengembang
Nikmatul Rizkiyah
