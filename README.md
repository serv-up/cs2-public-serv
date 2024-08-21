# Public сервер для CS2 от ServUp

Добро пожаловать в официальный репозиторий готового к использованию публичного сервера для Counter-Strike 2 (CS2) от проекта ServUp. Эта сборка сервера предварительно настроена и включает широкий спектр плагинов и улучшений для обеспечения оптимального игрового процесса.

## Возможности

На сервере установлены следующие плагины и инструменты:

- **Metamod**: [Metamod:Source](https://www.metamodsource.net/downloads.php/?branch=master) - Мощный фреймворк для плагинов для игр на движке Source.
- **CounterStrikeSharp**: [CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp) - Обширный API для разработки плагинов для CS2.
- **ServerListPlayersFix**: [ServerListPlayersFix](https://github.com/Source2ZE/ServerListPlayersFix) - Исправляет проблемы с отображением количества игроков в списке серверов.
- **VoiceFix**: [CS2VoiceFix](https://github.com/Source2ZE/CS2VoiceFix) - Решает проблемы с голосовой связью.
- **FakeRanks**: [FakeRanks-RevealAll](https://github.com/Cruze03/FakeRanks-RevealAll) - Добавляет функциональность поддельных рангов на сервере.
- **Реклама в чате**: [cs2-advertisement](https://github.com/partiusfabaa/cs2-advertisement) - Отображает пользовательские рекламные сообщения в игровом чате.
- **AFK Manager**: [AFKManager](https://github.com/NiGHT757/AFKManager) - Автоматически управляет AFK-игроками.
- **Админка**: [Iks_Admin](https://github.com/Iksix/Iks_Admin) - Предоставляет комплексную систему управления администраторами.
- **Показ урона в чате**: [CS2_DamageInfo](https://github.com/KitsuneLab-Development/CS2_DamageInfo) - Отображает статистику урона в игровом чате.
- **Система статистики**: [K4-System](https://github.com/KitsuneLab-Development/K4-System) - Отслеживает и управляет статистикой игроков.
- **MM ранги**: [K4-System-MMRanks](https://github.com/KitsuneLab-Development/K4-System-MMRanks) - Интегрирует ранги матчмейкинга с K4-System.
- **Менеджер меню**: [MenuManagerCS2](https://github.com/NickFox007/MenuManagerCS2) - Упрощает создание и управление игровыми меню.
- **PlayerSettings**: [PlayerSettingsCS2](https://github.com/NickFox007/PlayerSettingsCS2) - Сохраняет и управляет настройками игроков.
- **Обнуление счета**: [SimpleResetScore](https://github.com/stefanx111/cs2-SimpleResetScore) - Легко сбрасывает игровой счет.
- **Ядро VIP с модулями**: [VIPCore](https://github.com/partiusfabaa/cs2-VIPCore) - Система VIP с настраиваемыми модулями.
- **Скины на оружие и агентов**: [WeaponPaints](https://github.com/Nereziel/cs2-WeaponPaints) - Добавляет кастомные скины для оружия и агентов.
- **Ограничение оружия по командам**: [Weapon-restrict-fix](https://github.com/Nip0s/Weapon-restrict-fix) - Ограничивает выбор оружия в зависимости от команды.

## Требования

Для настройки сервера вам потребуется:

- **Хостинг**: Услуга хостинга игровых серверов.
- **MySQL база данных**: Для хранения данных, связанных с плагинами.
- **Веб-хостинг и доменное имя**: Для установки веб-движка, необходимого для выбора скинов на оружие и агентов.

## Руководство по установке

Следуйте этим шагам для установки и настройки вашего CS2 сервера:

1. **Скачайте сервер**:
   - [Скачайте предварительно настроенную сборку сервера](https://github.com/serv-up/cs2-public-serv).
   
2. **Распакуйте архив**:
   - Разархивируйте скачанный архив в нужную директорию.

3. **Настройте файлы сервера**:
   - Отредактируйте следующие конфигурационные файлы под ваши нужды:
     - `cfg/server.cfg` - Основной конфигурационный файл сервера.
     - `addons/counterstrikesharp/configs/plugins/Advertisement/Advertisement.json` - Настройка рекламы в игровом чате.
     - `addons/counterstrikesharp/configs/plugins/IksAdmin/IksAdmin.json` - Настройка админ-системы, включая параметры базы данных.
     - `addons/counterstrikesharp/configs/plugins/IksAdmin_SocietyLogs/IksAdmin_SocietyLogs.json` - Настройка Discord Webhook для логирования.
     - `addons/counterstrikesharp/configs/plugins/K4-System/K4-System.json` - Настройка системы статистики, включая параметры базы данных.
     - `addons/counterstrikesharp/configs/plugins/VIPCore/vip_core.json` - Настройка VIP-системы, включая интеграцию с базой данных.
     - `addons/counterstrikesharp/configs/plugins/WeaponPaints/WeaponPaints.json` - Настройка выбора скинов для оружия и агентов с использованием базы данных.

4. **Запустите сервер**:
   - Запустите сервер и наслаждайтесь полностью функциональным, богатым на функции сервером CS2.

## Заключение

Здесь собрана базовая конфигурация сервера, которую вы можете дополнить различными функциями в зависимости от ваших потребностей. Однако, если вы хотите создать качественную и продуманную сборку сервера, обращайтесь к нам — мы рады помочь каждому. Подробнее на нашем сайте: [servup.net](https://servup.net).

Для того чтобы найти нужный плагин и следить за его обновлениями, присоединяйтесь к нашему Discord-каналу: [https://discord.gg/servup](https://discord.gg/servup).

## Ищем возможности

Если вам нужен опытный разработчик для ваших проектов, свяжитесь со мной:

- **Discord**: [https://discord.gg/servup](https://discord.gg/servup)
- **Telegram**: [https://t.me/serv_up](https://t.me/serv_up)
- **Steam**: [https://steamcommunity.com/id/nex-end/](https://steamcommunity.com/id/nex-end/)

---
Для более подробной инструкции и поддержки обращайтесь к документации отдельных плагинов, ссылки на которые приведены выше, или свяжитесь с сообществом ServUp.

Не стесняйтесь форкать этот репозиторий, отправлять баг-репорты или вносить свой вклад в проект!
