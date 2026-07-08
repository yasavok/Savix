<div align="center">
  <img src="assets/logo.png" width="110" alt="Savix">
  <h1>Savix</h1>
  <p><strong>Премиальный VPN-клиент на базе Sing-box</strong></p>
  <p>Минималистичный дизайн. Мощное ядро. Полный контроль.</p>

  <a href="https://github.com/yasavok/Savix/releases/latest">
    <img src="https://img.shields.io/badge/Скачать%20установщик-18181b?style=for-the-badge&logo=windows">
  </a>
  <a href="https://t.me/SavixVPN">
    <img src="https://img.shields.io/badge/Telegram-канал-18181b?style=for-the-badge&logo=telegram">
  </a>

  <br><br>

  <img src="https://img.shields.io/badge/Версия-0.1.0-3b82f6?style=flat-square">
  <img src="https://img.shields.io/badge/Ядро-Sing--box-ef4444?style=flat-square">
  <img src="https://img.shields.io/badge/Платформа-Windows%2010%2F11-22c55e?style=flat-square">
  <img src="https://img.shields.io/badge/Архитектура-x64-8b5cf6?style=flat-square">
</div>

---

## О проекте

Savix — это современный VPN-клиент, объединяющий мощь Sing-box с продуманным интерфейсом. Поддерживает все популярные протоколы, импорт через ссылки и подписки, гибкие настройки маршрутизации и split tunneling.

Просто импортируйте конфигурацию — и защищённое соединение готово за один клик.

## Возможности

| Категория | Что умеет Savix |
|---|---|
| **Протоколы** | VLESS, VMess, Trojan, Shadowsocks, Hysteria2, TUIC, WireGuard |
| **Импорт** | По ссылке (vless://, vmess://, trojan://, ss://) и через подписки |
| **Пинг-тест** | Автоматический выбор сервера с минимальной задержкой |
| **Split tunneling** | Обход VPN для указанных доменов и процессов |
| **Режимы подключения** | Системный туннель (TUN) / Системный прокси |
| **Маршрутизация** | Настраиваемый DNS, стек TUN (Mixed, System, gVisor), MTU |
| **Автозапуск** | Автоматическое подключение при старте |
| **Расширенные** | Multiplex (Mux), уровень логирования ядра (error — trace) |
| **Интерфейс** | Тёмная и светлая темы, русский и английский язык |

## Установка

```
Windows 10 / 11 (x64)
Права администратора (для режима TUN)
```

1. Скачайте `Savix.Setup.0.1.0.exe` из [Releases](https://github.com/yasavok/Savix/releases)
2. Запустите установщик
3. При необходимости запустите Savix от имени администратора

## Быстрый старт

1. Откройте Savix
2. Перейдите на вкладку «Серверы»
3. Импортируйте конфигурацию через ссылку или подписку
4. Нажмите «Подключить»

Savix сам выберет оптимальные настройки маршрутизации.

## Связь

- Telegram: [@SavixVPN](https://t.me/SavixVPN)
