# 🌐 map-fi data

### ALL WI-FI POINTS LISTED ARE CONSENTUAL, SUGGEST ONLY PERSONAL OR FULLY PUBLIC NETWORKS
### ВСЕ WI-FI ТОЧКИ УКАЗАНЫ С РАЗРЕШЕНИЯ, ДОБАВЛЯЙТЕ ТОЛЬКО ЛИЧНЫЕ ИЛИ ПОЛНОСТЬЮ ПУБЛИЧНЫЕ СЕТИ
---
## JSON structure/ Структура JSON

| Field     | Type    | Description                 | Описание                                   |
|-----------|---------|-----------------------------|--------------------------------------------|
| `id`      | string  | Unique Identifier (UUID v4) | Уникальный идентификатор (UUID v4)         |
| `name`    | string  | Wi-Fi Network name (SSID) | Название Wi‑Fi сети (SSID)                   |
| `password`| string  | Password, leave empty `""` for open networks | Пароль, пустая строка `""` - для открытых сетей |
| `rating`  | number  | Rating from 0.0 to 5.0, fractional values | Рейтинг от 0.0 до 5.0, дробные значения |
| `lat`     | number  | Latitude in WGS‑84 format, range -90 … +90 | Широта в формате WGS‑84, диапазон −90 … +90 |
| `lng`     | number  | Longitude in WGS‑84 format, range -180 … +180 | Долгота в формате WGS‑84, диапазон −180 … +180 |
---
github requests support soon | поддержка запросов с гитхаба скоро
