# Mobile BIM — Android

Собственный мобильный BIM/CAD-редактор для Android. Проект находится на стадии технического прототипа v0.8.

## Статус

- BIM-ядро и тесты проверены в Kotlin (34 сценария).
- Сборка APK и работа на Android **пока не подтверждены**.
- Импорт/экспорт RVT и интеграция с TARQELIO запланированы позднее; Archicad отложен.

## Загрузка исходников

Архив MobileBIM-Android-v0.8-source.zip подготовлен отдельно. Для сборки исходники должны оказаться в репозитории: `settings.gradle.kts`, `app/` и `core/` в его корне. GitHub Actions собирает APK только после загрузки исходников.

## Сборка

Workflow `Build Mobile BIM Android` запускает проверку core и `:app:assembleDebug`. Debug APK появится в Artifacts **только при успешной сборке**.
