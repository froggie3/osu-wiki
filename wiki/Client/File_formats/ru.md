---
outdated: true
---

# Форматы файлов osu!

## Специальные форматы osu!

### Архив

| Формат | Содержание |
| :-- | :-- |
| [.osz][Osz Link] | Исполняемый файл с картой. |
| [.osk][Osk Link] | Исполняемый файл со скином. |

### Редактор карт

| Формат | Содержание |
| :-- | :-- |
| [.osu][Osu Link] | Ноты, тайминг, настройки песни. |
| [.osb][Osb Link] | Дизайн. |

### Реплей

| Формат | Содержание |
| :-- | :-- |
| [.osr][Osr Link] | Исполняемый файл с реплеем (нераспаковываемый). |

## Создание файлов .osz/.osk

Расширения .osz и .osk созданы специально для osu!.exe. При открытии файлы с этими расширениями будут распакованы osu! и перенесены в соответствующие папки: .osz в папку "Songs", .osk в папку "Skins". По умолчанию все карты, скачанные с официального сайта, имеют расширение .osz. Создание файлов .osz/.osk является основным умением для создателей карт/скинов.

### При помощи архиватора

**Необходимый софт:**

- Архиватор (WinRAR, 7-Zip)
- osu! (для проверки)

**Порядок действий**

1. Соберите все необходимые файлы (.mp3, .flv, .osu и т.д.) в одну папку и назовите её.
   - К примеру назовём эту папку "Amigo Fiesta".
2. Щёлкните по папке правой кнопкой мыши и заархивируйте её (Добавить в архив...).
   - Можно также открыть архиватор отдельно и перетащить в него папку.
3. В настройках архива выберите метод архивации ".zip" (не .7z и не .rar) и переименуйте архив так, чтобы он имел расширение .osz.
   - Amigo Fiesta.zip -> Amigo Fiesta.osz, метод архивации ".zip"
4. Завершите создание архива, тем самым создав нужный .osz файл.

Для скинов используйте расширение .osk.

### Из игры

**Необходимый софт:**

- osu!

**Порядок действий**

1. Соберите все необходимые файлы в одну папку и назовите её.
2. Откройте osu!.
3. Для создания .osz:
   - Перейдите в редактор карт и выберите нужную карту.
   - Выберите меню "Файл", затем "Экспортировать в .osz".
   - .osz будет создан и сохранён в папку "Exports" в папке osu!.
4. Для создания .osk:
   - Перейдите в настройки.
   - Выберите необходимый скин и нажмите "Экспортировать в .osk".
   - .osk будет создан и сохранён в папку "Exports" в папке osu!.

[Osz Link]: /wiki/osu!_File_Formats/Osz_(file_format)
[Osk Link]: /wiki/osu!_File_Formats/Osk_(file_format)
[Osu Link]: /wiki/osu!_File_Formats/Osu_(file_format)
[Osb Link]: /wiki/osu!_File_Formats/Osb_(file_format)
[Osr Link]: /wiki/osu!_File_Formats/Osr_(file_format)