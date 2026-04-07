# 2D Racing Game 🚗

Полноценная 2D гоночная игра для Android с машинами, монетами и врагами!

## 🎮 Возможности

- 🚗 **Управление машиной** - касайтесь экрана для движения
- 🪙 **Сбор монет** - накапливайте деньги
- 🚓 **Враги** - избегайте столкновений
- 💥 **Система столкновений** - игра заканчивается при контакте
- 🏁 **Система очков** - набирайте очки за прошедшие препятствия

## 📦 Сборка APK через GitHub Actions

1. Пуш кода в `main` бранч
2. Перейди в **Actions** вкладку
3. Выбери последний workflow run
4. Скачай **app-release.apk** из Artifacts

## 🛠️ Структура проекта

```
2d-racing-game/
├── app/
│   ├── src/main/
│   │   ├── java/com/example/minigtarace/
│   │   │   └── MainActivity.java
│   │   └── AndroidManifest.xml
│   └── build.gradle
├── .github/workflows/
│   └── build.yml
├── settings.gradle
└── README.md
```

## 🚀 Как запустить локально

1. Клонируй репо: `git clone https://github.com/minimixail2013-collab/2d-racing-game.git`
2. Открой в Android Studio
3. Запусти на эмуляторе или устройстве

## 📝 Лицензия

MIT License