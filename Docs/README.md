# LeoECS Lite Baking Code Generation

![License](https://img.shields.io/github/license/g0dzZz-coder/ecslite.baking.codegen?style=rounded-square)
![Last Commit](https://img.shields.io/github/last-commit/g0dzZz-coder/ecslite.baking.codegen?style=rounded-square)
![Code Size](https://img.shields.io/github/languages/code-size/g0dzZz-coder/ecslite.baking.codegen?style=rounded-square)

<div>
    <strong><a href="README.md">English</a> | <a href="README.RU.md">Русский</a></strong>
</div>

<details>
<summary>Table of Contents</summary>

- [Introduction](#-introduction)
    - [Features](#-features)
- [Installation](#-installation)
- [Usage Examples](#-usage-examples)
- [Dependencies](#-dependencies)
- [Contributing](#-contributing)
- [Support](#-support)
- [License](#-license)

</details>

## 🧾 Introduction

**Leopotam.EcsLite.Baking.CodeGen** is an extension for [Leopotam.EcsLite.Baking](https://github.com/g0dzZz-coder/ecslite.baking),
which introduces code generation,
making the process of creating custom components more efficient and freeing you from routine.

### 💡 Features

- **Open Source**: This library is open-source and free to use.
- **Easy to Use**: Add the `DefaultBaking` attribute to your ECS components and get ready-made `AuthoringComponent`.

## 📥 Installation

### 📦 Using **UPM**:

1. Open the **Unity Package Manager** window.
2. Click the **+** button in the upper-right corner of the window.
3. Select **Add package from git URL...**.
4. Enter the link to the [Leopotam.EcsLite.Baking repository](https://github.com/g0dzZz-coder/ecslite.baking.git).
5. Click **Add**.
6. Repeat steps 2-5 for [Depra.CodeGen.Unity](https://github.com/Depra-Inc/CodeGen.Unity.git).
7. Repeat steps 2-5 for [this repository](https://github.com/g0dzZz-coder/ecslite.baking.codegen.git).

### ⚙️ Manual:

Add the following lines to `Packages/manifest.json` in the `dependencies` section:

```
"com.leopotam.ecslite": "https://github.com/Leopotam/ecslite.git",
"com.leopotam.ecslite.baking": "https://github.com/g0dzZz-coder/ecslite.baking.git",
"com.depra.codegen": "https://github.com/Depra-Inc/CodeGen.Unity.git",
"com.leopotam.ecslite.baking.codegen": "https://github.com/g0dzZz-coder/ecslite.baking.codegen.git"
```

## 📋 Usage Examples

1. Add the `DefaultBaking` attribute to your **ECS** components.
2. Click `Generate Authoring Components` in the `Depra/Ecs` menu.
3. You're all set! The generated components will be located in the `Assets/Generated/AuthoringComponents` folder.

## 🖇️ Dependencies

- [Leopotam ECS Lite](https://github.com/Leopotam/ecslite) - the base ECS library.
- [Leopotam ECS Lite Baking](https://github.com/g0dzZz-coder/ecslite.baking.git) - a package for converting **GameObject** to **Entity**.
- [Depra.CodeGen.Unity](https://github.com/Depra-Inc/CodeGen.Unity) - a package for code generation.

## 🤝 Collaboration

I welcome feature requests and bug reports in
the [issues section](https://github.com/g0dzZz-coder/ecslite.baking.codegen/issues),
and I also accept [pull requests](https://github.com/g0dzZz-coder/ecslite.baking.codegen/pulls).

## 🫂 Support

I am an independent developer, and most of the development of this project is done in my free time. If you are
interested in collaborating or hiring me for a project, please check out
my [portfolio](https://github.com/Depra-Inc) and [contact me](mailto:g0dzZz1lla@yandex.ru)!

## 🔐 License

This project is distributed under the
**[Apache-2.0 license](https://github.com/g0dzZz-coder/ecslite.baking.codegen/blob/main/LICENSE.md)**

Copyright (c) 2023 Nikolay Melnikov
[n.melnikov@depra.org](mailto:n.melnikov@depra.org)