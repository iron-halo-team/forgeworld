# Скачать Forge World Launcher

Актуальная версия лаунчера публикуется в GitHub Releases:

[Скачать последнюю версию](https://github.com/iron-halo-team/forgeworld/releases/latest)

## Как работает проверка обновлений

Лаунчер читает файл `updates/metadata.json` по ссылке из `launcher.config.json`.

Если `latestVersion` в этом файле больше, чем `launcherVersion` внутри установленного лаунчера, игрок увидит уведомление о новой версии и кнопку скачивания.

## Что менять при новом релизе

1. Загрузите новый установщик в GitHub Releases.
2. Обновите `latestVersion`.
3. Обновите `title`, `notes` и `publishedAt`.
4. Если нужна прямая ссылка на конкретный файл, замените `downloadUrl`.

Если `downloadUrl` не указан, лаунчер откроет страницу `downloadPage` из `launcher.config.json`.
