# MobileDefaultDependencies

Набор заготовок конфигурации Gradle для Android-проектов на Kotlin и Jetpack Compose. Это фрагменты для переноса в другой проект, а не самостоятельное приложение.

## Файлы

- `build_gradle.txt` — настройки Android-модуля и зависимости.
- `build_gradle_plugins.txt` — объявления плагинов на уровне проекта.
- `libs_versions.txt` — каталог версий, библиотек и плагинов.

## Использование

Перенесите нужные блоки в `app/build.gradle.kts`, корневой `build.gradle.kts` и `gradle/libs.versions.toml` своего проекта. Замените `namespace` и `applicationId`, согласуйте версии SDK и плагинов, затем выполните синхронизацию Gradle. Используйте только те зависимости, которые нужны приложению.
