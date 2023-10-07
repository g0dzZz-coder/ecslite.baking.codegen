# LeoECS Lite Baking Code Generation

![License](https://img.shields.io/github/license/g0dzZz-coder/ecslite.baking.codegen?style=rounded-square)
![Last Commit](https://img.shields.io/github/last-commit/g0dzZz-coder/ecslite.baking.codegen?style=rounded-square)
![Code Size](https://img.shields.io/github/languages/code-size/g0dzZz-coder/ecslite.baking.codegen?style=rounded-square)

<div>
    <strong><a href="README.md">English</a> | <a href="README.RU.md">Русский</a></strong>
</div>

<details>
<summary>Содержание</summary>

- [Введение](#-введение)
    - [Особенности](#-особенности)
- [Установка](#-установка)
- [Примеры использования](#-примеры-использования)
- [Зависимости](#-зависимости)
- [Сотрудничество](#-сотрудничество)
- [Поддержка](#-поддержка)
- [Лицензия](#-лицензия)

</details>

## 🧾 Введение

**Leopotam.EcsLite.Baking.CodeGen** - расширение для [Leopotam.EcsLite.Baking](https://github.com/g0dzZz-coder/ecslite.baking),
которое внедряет кодогенерацию,
сделав процесс создания авторских компонентов более эффективным и избавив вас от рутины.

### 💡 Особенности

- **Открытый исходный код**: Эта библиотека с открытым исходным кодом и бесплатна для использования.
- **Прост в использовании**: Добавьте атрибут `DefaultBaking` к вашим компонентам и получите
  готовый `AuthoringComponent`.

## 📥 Установка

### 📦 С использованием **UPM**:

1. Откройте окно **Unity Package Manager**.
2. Нажмите кнопку **+** в верхнем правом углу окна.
3. Выберите **Add package from git URL...**.
4. Введите [ссылку на репозиторий Leopotam.EcsLite.Baking](https://github.com/g0dzZz-coder/ecslite.baking.git).
5. Нажмите **Add**.
6. Повторите шаги 2-5 для [Depra.CodeGen.Unity](https://github.com/Depra-Inc/CodeGen.Unity.git).
7. Повторите шаги 2-5 для [этого репозитория](https://github.com/g0dzZz-coder/ecslite.baking.codegen.git).

### ⚙️ Вручную:

Добавьте следующие строки в `Packages/manifest.json` в раздел `dependencies`:

```
"com.leopotam.ecslite": "https://github.com/Leopotam/ecslite.git",
"com.leopotam.ecslite.baking": "https://github.com/g0dzZz-coder/ecslite.baking.git",
"com.depra.codegen": "https://github.com/Depra-Inc/CodeGen.Unity.git",
"com.leopotam.ecslite.baking.codegen": "https://github.com/g0dzZz-coder/ecslite.baking.codegen.git"
```

## 📋 Примеры использования

1. Добавьте атрибут `DefaultBaking` к вашим компонентам **ECS**.
2. Нажмите `Generate Authoring Components` в меню `Leopotam/Ecs`.
3. Вы великолепны! Сгенерированные компоненты будут лежать в папке `Assets/Generated/AuthoringComponents`.

## 🖇️ Зависимости

- [Leopotam ECS Lite](https://github.com/Leopotam/ecslite) - базовая ECS библиотека.
- [Leopotam ECS Lite Baking](https://github.com/g0dzZz-coder/ecslite.baking.git) - пакет для конвертации **GameObject** в **Entity**.
- [Depra.CodeGen.Unity](https://github.com/Depra-Inc/CodeGen.Unity) - пакет для кодогенерации.

## 🤝 Сотрудничество

Я рад приветствовать запросы на добавление новых функций и сообщения об ошибках
в разделе [issues](https://github.com/g0dzZz-coder/ecslite.baking.codegen/issues)
и также принимать [pull requests](https://github.com/g0dzZz-coder/ecslite.baking.codegen/pulls).

## 🫂 Поддержка

Я независимый разработчик, и большая часть разработки этого проекта выполняется в свободное время.
Если вы заинтересованы в сотрудничестве или найме меня для проекта,
ознакомьтесь с моим [портфолио](https://github.com/Depra-Inc)
и [свяжитесь со мной](mailto:g0dzZz1lla@yandex.ru)!

## 🔐 Лицензия

Этот проект распространяется под лицензией
**[Apache-2.0](https://github.com/g0dzZz-coder/ecslite.baking.codegen/blob/main/LICENSE.md)**

Copyright (c) 2023 Николай Мельников
[n.melnikov@depra.org](mailto:n.melnikov@depra.org)