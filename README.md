# CryptoPulse - Live Dashboard

CryptoPulse - это живой дашборд для отслеживания цены Bitcoin (BTC/USDT) в реальном времени. Проект использует React для интерфейса, Chart.js для графиков и WebSocket для получения live данных от Binance API.

## Особенности

- **Живая цена**: Отображение текущей цены BTC/USDT с обновлением в реальном времени через WebSocket.
- **Исторический график**: График цен за последние 50 часов с интервалом 1 час.
- **Статус подключения**: Индикатор статуса соединения (Live/Disconnected/API Error).
- **Адаптивный дизайн**: Использует Tailwind CSS для современного и responsive интерфейса.

## Технологии

- **React**: Для построения пользовательского интерфейса.
- **Chart.js**: Для визуализации исторических данных.
- **WebSocket**: Для live обновлений цен.
- **Binance API**: Источник данных о ценах.
- **Tailwind CSS**: Для стилизации.
- **Babel**: Для трансляции JSX.

## Установка и запуск

1. Клонируйте репозиторий:
   ```
   git clone https://github.com/your-username/dashboard.git
   cd dashboard
   ```

2. Откройте `dashboard.html` в браузере. Поскольку это статический HTML с встроенным JavaScript, нет необходимости в сервере.

## Структура проекта

- `dashboard.html`: Основной файл с HTML, CSS и JavaScript кодом.

## API Использование

- **Исторические данные**: `https://api.binance.com/api/v3/klines?symbol=BTCUSDT&interval=1h&limit=50`
- **Live данные**: WebSocket `wss://stream.binance.com:9443/ws/btcusdt@trade`


