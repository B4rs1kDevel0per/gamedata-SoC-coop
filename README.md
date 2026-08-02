# ⚠️ Unofficial Community Patch for xrMPE SoC Addon / Неофициальный патч от комьюнити для ТЧ Аддона

> **EN:** **There is no ready-made addon here.** This repository is dedicated to the open-source development of a community patch. If you don't know how to use GitHub or have zero modding experience, please move along.
>
> **RU:** **Здесь нет готового аддона.** Этот репозиторий создан для open-source разработки патча силами комьюнити. Если вы не умеете работать с GitHub и ничего не понимаете в моддинге - проходите мимо.

---

## 📦 Latest Dev's Progress / Последние наработки разработчика

* **RU:** **Геймдата Акаси:** [Скачать с Google Drive](https://drive.google.com/file/d/16x7wAvvEnS9nLxdMiJ8R7gowGwYrmnZs) - это последние наработки и фиксы от автора. Скорее всего, это финальный билд от разработчика, но учтите: он сырой и нерабочий.
* **EN:** **Akasi's Gamedata:** [Download from Google Drive](https://drive.google.com/file/d/16x7wAvvEnS9nLxdMiJ8R7gowGwYrmnZs) - these are the latest updates and fixes from the author. This is (most likely) the final build from the developer, but keep in mind: it is raw and broken.

---

## 🚀 Quick Start / Инструкция по запуску

### RU:
1. Скачайте чистый аддон или игру и убедитесь, что она запускается.
2. Скачайте файлы из этого репозитория (или конкретный рабочий форк).
3. **Важно:** Папка репозитория в директории игры должна называться строго `gamedata`, иначе игра её не увидит. Для удобства разработки можно использовать символические ссылки.
4. Скачайте изменённый файл [fsgame.ltx](https://cdn.discordapp.com/attachments/1355564878412255456/1533557373573005374/fsgame_s.zip?ex=6a70ec19&is=6a6f9a99&hm=3fdfa612b325b63904be05f074146391f643ce63503d689e6cf7d750b2f6addf&) (он необходим, чтобы игра читала модифицированную геймдату поверх аддона).
5. Закиньте скачанный `fsgame` и папку `gamedata` в корневую директорию игры с заменой файлов.

### EN:
1. Download the clean addon or game and make sure it runs properly.
2. Download the files from this repository (or a specific working fork).
3. **Important:** The repository folder in the game directory must be named strictly `gamedata`, otherwise the game won't recognize it. For development convenience, you can use symlinks.
4. Download the modified [fsgame.ltx](https://cdn.discordapp.com/attachments/1355564878412255456/1533557373573005374/fsgame_s.zip?ex=6a70ec19&is=6a6f9a99&hm=3fdfa612b325b63904be05f074146391f643ce63503d689e6cf7d750b2f6addf&) file (required for the game to load the modified gamedata over the addon).
5. Drop both the downloaded `fsgame` and the `gamedata` folder into the main game directory, overwriting old files.

---

## 💻 How to contribute / Как поучаствовать

### For Developers / Для разработчиков:
1. **Fork** this repository / Сделайте **Форк** этого репозитория.
2. Clone it and make your tweaks/fixes / Клонируйте его, ковыряйте код и тестируйте изменения.
3. Submit a **Pull Request (PR)** / Отправляйте **Пулл-реквест**. After review, it will be merged into the main branch / После проверки мы вкатаем его в общую ветку.

### For Testers / Для тестеров:
* If you found a bug and can describe it properly, please report it in the [Issues](https://github.com/B4rs1kDevel0per/gamedata-SoC-coop/issues) section.
* Если вы нашли баг и можете подробно его расписать, оформляйте репорт в раздел [Issues](https://github.com/B4rs1kDevel0per/gamedata-SoC-coop/issues).

---

## 💬 Chat & Discussion / Обсуждение

Все обсуждения, идеи и помощь в разборе аддона проходят в нашем [Discord-канале](https://discord.gg/7KmA9aZ72): **Фиксим аддон сами / Fix It Yourself**.

*All discussions, ideas, and help with the addon take place in our [Discord channel](https://discord.gg/7KmA9aZ72): **Фиксим аддон сами / Fix It Yourself**.*

---

## ⚖️ Controversial Tweaks & License / Спорные правки и Лицензия

* **EN:** If your fork is purely a matter of taste, we won't merge it into the main branch. You can keep it as a standalone addon based on our repo. This project is licensed under the [MIT License](LICENSE).
* **RU:** Если ваш форк это вкусовщина, мы не вкатаем его в основную ветку. Но вы можете оставить его жить как отдельный аддон на базе нашего репозитория. Проект распространяется по открытой [Лицензии MIT](LICENSE).

