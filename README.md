# IoT Sensor Event Web App (Dask + FastAPI)

Aplikasi web sederhana berbasis FastAPI yang menampilkan data event sensor IoT
menggunakan pemrosesan paralel dengan Dask DataFrame.

## Fitur
- 1 tabel database: iot_sensor_events
- Parallel SQL processing menggunakan `dask.dataframe.read_sql_query`
- Output HTML table
- Dockerized (App + MySQL)
- Endpoint: `/list`

## Teknologi
- FastAPI
- Dask
- MySQL
- Docker & Docker Compose

## Menjalankan Aplikasi
```bash
docker compose up --build
