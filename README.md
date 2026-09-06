<div align="center">

<img src="assets/icon.png" alt="Blockfield Logo" width="128" height="128" />

# BLOCKFIELD LAUNCHER
### Официальный лаунчер тактического PvP-проекта Blockfield

*«Высадка. Захват. Доминация.»*

[![Latest Release](https://img.shields.io/github/v/release/netherg-io/blockfield-launcher-releases?label=Релиз&style=for-the-badge&color=2ea44f)](https://github.com/netherg-io/blockfield-launcher-releases/releases/latest)
[![Platform](https://img.shields.io/badge/Платформы-Windows%20%7C%20Linux-blue?style=for-the-badge)](https://github.com/netherg-io/blockfield-launcher-releases/releases/latest)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1%20Fabric-orange?style=for-the-badge)](https://fabricmc.net/)
[![Tauri](https://img.shields.io/badge/Движок-Tauri%202%20%2F%20Rust-brightgreen?style=for-the-badge)](https://tauri.app/)

<br />

[**📥 Скачать лаунчер**](#-загрузка-и-установка) • [**О проекте**](#-о-проекте-blockfield) • [**Возможности**](#-ключевые-особенности) • [**Требования**](#-системные-требования) • [**Поддержка**](#-поддержка-и-вопросы)

</div>

---

## 🚀 Загрузка и установка

Выберите подходящий вариант для вашей операционной системы. Установленный лаунчер автоматически проверяет и получает последующие обновления.

| Платформа | Формат | Ссылка на загрузку | Описание |
| :--- | :--- | :--- | :--- |
| **Windows 10 / 11** | `.exe` | [**Скачать Installer (x64)**](https://github.com/netherg-io/blockfield-launcher-releases/releases/latest/download/blockfield-launcher_0.3.0_x64-setup.exe) | Рекомендуемый установщик (NSIS) |
| **Windows 10 / 11** | `.msi` | [**Скачать MSI (x64)**](https://github.com/netherg-io/blockfield-launcher-releases/releases/latest/download/blockfield-launcher_0.3.0_x64_en-US.msi) | Пакет Windows Installer |
| **Linux (Все дистрибутивы)** | `.AppImage` | [**Скачать AppImage**](https://github.com/netherg-io/blockfield-launcher-releases/releases/latest/download/blockfield-launcher_0.3.0_amd64.AppImage) | Универсальный запуск без установки |
| **Ubuntu / Debian / Mint** | `.deb` | [**Скачать DEB**](https://github.com/netherg-io/blockfield-launcher-releases/releases/latest/download/blockfield-launcher_0.3.0_amd64.deb) | Нативный deb-пакет для Debian-систем |
| **Fedora / RHEL / CentOS** | `.rpm` | [**Скачать RPM**](https://github.com/netherg-io/blockfield-launcher-releases/releases/latest/download/blockfield-launcher-0.3.0-1.x86_64.rpm) | Пакет RPM для Red Hat-совместимых ОС |

> [!TIP]
> Все релизы, включая список изменений и цифровые подписи (`.sig`), доступны на странице [**Releases**](https://github.com/netherg-io/blockfield-launcher-releases/releases/latest).

<details>
<summary><b>Инструкция по установке и запуску на Linux</b></summary>

### AppImage (Любой дистрибутив)
```bash
chmod +x blockfield-launcher_*_amd64.AppImage
./blockfield-launcher_*_amd64.AppImage
```

### Ubuntu / Debian
```bash
sudo apt install ./blockfield-launcher_*_amd64.deb
```

### Fedora / RHEL
```bash
sudo dnf install ./blockfield-launcher-*.x86_64.rpm
```
</details>

---

## 🎯 О проекте Blockfield

**Blockfield** — это масштабный тактический PvP-проект на базе Minecraft (1.21.1 Fabric), переносящий командные боевые действия на спорные территории:

- 🚩 **Контроль секторов**: динамический захват и удержание стратегических контрольных точек.
- 🎖️ **6 специализированных классов**: гибкие тактические роли со своим снаряжением и способностями.
- 🚜 **Бронетехника и транспорт**: доставка пехоты и поддержка огнем на передовой.
- ⚡ **Операция «Железный фронт»**: уникальные театры боевых действий, динамические миссии и развитая командная координация.

---

## ⚡ Ключевые особенности лаунчера

- **Мгновенный запуск и легковесность**  
  Создан на базе **Rust** и **Tauri 2** — потребляет минимум оперативной памяти и не нагружает систему во время игры.

- **Всё готово из коробки**  
  Не требуется ручная установка Java. Лаунчер автоматически загружает и настраивает оптимизированную среду выполнения Eclipse Temurin 17 JRE под вашу систему.

- **Умная синхронизация файлов**  
  Благодаря Packwiz клиент проверяет целостность сборки и докачивает только измененные моды без необходимости повторно скачивать всю сборку.

- **Бесшовные автообновления**  
  Встроенная система обновлений с верификацией криптографических подписей поддерживает лаунчер в актуальном состоянии в один клик.

- **Мониторинг сервера в реальном времени**  
  Отображение сетевого статуса, пинга, количества игроков онлайн и региона хостинга прямо в интерфейсе.

- **Гибкие настройки клиента**  
  Удобное распределение оперативной памяти (RAM), поддержка пользовательских скриптов/команд до старта и после завершения игры, автоматическое скрытие лаунчера во время сессии.

---

## 💻 Системные требования

| Параметр | Минимальные | Рекомендуемые |
| :--- | :--- | :--- |
| **Операционная система** | Windows 10/11 (64-bit) или Linux (glibc 2.31+) | Windows 10/11 (64-bit) или современный Linux |
| **Процессор** | 64-bit Dual-Core (Intel / AMD) | 64-bit Quad-Core (Intel Core i5 / Ryzen 5+) |
| **Оперативная память** | 4 ГБ ОЗУ (3 ГБ выделено в лаунчере) | 8+ ГБ ОЗУ (4–6 ГБ выделено в лаунчере) |
| **Видеокарта** | Поддержка OpenGL 4.4 / Vulkan | Дискретная видеокарта NVIDIA / AMD / Intel Arc |
| **Место на накопителе** | ~3 ГБ свободного места | SSD-накопитель, от 5 ГБ свободного места |
| **Подключение к сети** | Широкополосный доступ в интернет | Стабильное соединение с низким пингом |

---

## ❓ Часто задаваемые вопросы

<details>
<summary><b>Нужно ли устанавливать Java вручную?</b></summary>
Нет. Лаунчер самостоятельно загрузит, проверит и настроит подходящую сборку Eclipse Temurin JRE 17 в изолированную директорию.
</details>

<details>
<summary><b>Как проверить целостность или восстановить файлы игры?</b></summary>
В лаунчере перейдите в раздел <b>Настройки</b> и нажмите <b>«Проверить файлы»</b>. Лаунчер сверит клиент с сервером и восстановит поврежденные или недостающие файлы.
</details>

<details>
<summary><b>Куда обращаться при возникновении ошибок?</b></summary>
Если вы обнаружили неполадку в работе лаунчера, откройте обращение в разделе <a href="https://github.com/netherg-io/blockfield-launcher-releases/issues">Issues</a> с описанием проблемы и логами из директории <code>logs/</code>.
</details>

---

<div align="center">

**[Blockfield Project](https://github.com/netherg-io/blockfield-launcher-releases)** • 2026

</div>
