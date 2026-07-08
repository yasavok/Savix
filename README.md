<p align="center">
  <img src="https://raw.githubusercontent.com/yasavok/Savix/main/assets/logo.png" width="120" alt="Savix">
</p>

<h1 align="center">Savix</h1>

<p align="center">
  <strong>Премиальный VPN-клиент на базе Sing-box</strong>
  <br>
  Минималистичный дизайн. Максимальная производительность. Полный контроль.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/платформа-Windows%20|%20Android-blue?style=flat-square">
  <img src="https://img.shields.io/badge/ядро-Sing--box-red?style=flat-square">
  <img src="https://img.shields.io/badge/лицензия-MIT-green?style=flat-square">
  <img src="https://img.shields.io/badge/версия-0.1.0-orange?style=flat-square">
</p>

<br>

## Возможности

- **7 протоколов**: VLESS, VMess, Trojan, Shadowsocks, Hysteria2, TUIC, WireGuard
- **Импорт**: по ссылке (vless://, vmess://, trojan://, ss://) и через подписки
- **Автоподключение** при запуске системы
- **Пинг-тест** — автоматический выбор лучшего сервера
- **Split tunneling** — настройка маршрутов обхода по доменам и процессам
- **Два режима подключения**: системный туннель (TUN) и системный прокси
- **Маршрутизация**: выбор DNS, стека TUN (Mixed/System/gVisor), MTU
- **Расширенные настройки**: Multiplex (Mux), уровень логирования ядра
- **Два языка**: русский и английский
- **Тёмная и светлая темы**
- **Лог событий** в реальном времени

## Скриншоты

*(добавьте скриншоты интерфейса)*

## Установка

Скачайте последнюю версию установщика в разделе [Releases](https://github.com/yasavok/Savix/releases).

**Требования:**
- Windows 10/11 (x64)
- Права администратора (для режима TUN)

## Сборка из исходного кода

```bash
git clone https://github.com/yasavok/Savix.git
cd Savix
npm install
npm run build
npm run package
```

## Контакты

- Telegram-канал: [@SavixVPN](https://t.me/SavixVPN)

---

<p align="center">
  <sub>Сделано с ❤️ для тех, кто ценит приватность.</sub>
</p>
