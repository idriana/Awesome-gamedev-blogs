# Архив сайта catlikecoding.com

Catlikecoding.com - сайт с набором туториалов для Unity, включая:
- Полигональные сетки, их процедурная генерация;
- Псевдослучайный шум;
- Движение персонажа;
- Управление игровыми объектами (создание, загрузка, хранение, удаление);
- Рендеринг;
- Алгоритм движущихся квадратов (Marching squares);

Сайт создан независимым разработчиком Джаспером Фликом в качестве коммерчиского проекта. Сайт находится в открытом доступе, и собирает пожертвования для монетизации.

# Веб-архив

В данном репозитории отсутствует файл .warc, его можно найти на [GoogleDrive](https://drive.google.com/drive/folders/1_H-bb7338sZuzpQCf8aVkK1y6h0Z5T9c?usp=drive_link).

# Воспроизведение веб-архива

Веб-архив можно воспроизвести с помощью сервиса [Replay Webpage](https://replayweb.page).

Содержимое веб-архива выглядит следующим образом:

<img width="1918" height="1035" alt="image" src="https://github.com/user-attachments/assets/fb43e088-35aa-44c9-852d-b377d43373e1" />


<img width="1920" height="996" alt="image" src="https://github.com/user-attachments/assets/56ab3741-60fd-44c6-abc9-e6c5256a6aad" />

# Анализ ArchiveReady

<img width="454" height="260" alt="image" src="https://github.com/user-attachments/assets/1c71afa6-dbf8-48cc-abdd-2e6d0d9508bf" />

* Низкая доступность обусловлена:
  * Медленным соединением
  * Ошибками RSS
  * Политиками robots.txt
  * Отсутствием sitemap.xml
  * Наличием кода JavaScript в HTML документе
* Высокая целостность обусловлена отсутствием удаленных файлов CSS
* Высокий показатель метаданных обусловлен строгой типизацией контента и корректно указанными заголовками
* Низкий показатель соответствия стандартом обусловлен:
  * Ошибками RSS
  * Ошибками CSS

Данные ошибки не повлияли на качество архивации.

# Анализ metawarc

* Файл метаданных сохранен как catlikecoding.com.meta.jsonl.
* База данных metawarc сохранена как metawarc.db
* Извлеченные метаданные не включены в репозиторий, для их извлечения необходимо использовать metawarc на веб-архиве.

## Общая сводка

``` metawarc analyze catlikecoding.com.warc.gz ```

| mimes                     | files |     size     |    share      |
|---------------------------|-------|--------------|---------------|
| application/pdf           | 178   | 718701387    | 33.2009       |
| *(empty mime)*            | 326   | 572600172    | 26.4517       |
| video/mp4                 | 455   | 450949193    | 20.8319       |
| image/png                 | 4424  | 330772815    | 15.2803       |
| image/jpeg                | 608   | 51798910     | 2.39289       |
| application/javascript    | 10    | 22027791     | 1.01759       |
| text/html                 | 557   | 14027431     | 0.648008      |
| image/webp                | 241   | 3603606      | 0.166471      |
| font/woff2                | 3     | 66009        | 0.00304933    |
| text/css                  | 7     | 49487        | 0.00228609    |
| application/atom+xml      | 2     | 49031        | 0.00226502    |
| image/x-icon              | 3     | 47674        | 0.00220234    |
| image/svg+xml             | 6     | 7450         | 0.000344158   |
| application/xml           | 1     | 505          | 0.0000233288  |
| text/plain                | 1     | 333          | 0.0000153832  |
| **#total**                | **6822** | **2164701794** | **100** |

## Mime-типы

``` metawarc stats -m mimes ```

| mime                          | size      | count |
|-------------------------------|-----------|-------|
| None                          | 572600172 |   326 |
| application/atom+xml          | 49031     |     2 |
| application/javascript        | 22027791  |    10 |
| application/pdf               | 718701387 |   178 |
| application/xml               | 505       |     1 |
| font/woff2                    | 66009     |     3 |
| image/jpeg                    | 51798910  |   608 |
| image/png                     | 330772815 |  4424 |
| image/svg+xml                 | 7450      |     6 |
| image/webp                    | 3603606   |   241 |
| image/x-icon                  | 47674     |     3 |
| text/css                      | 49487     |     7 |
| text/html; charset=iso-8859-1 | 15458     |    28 |
| text/html; charset=utf-8      | 14011973  |   529 |
| text/plain; charset=utf-8     | 333       |     1 |
| video/mp4                     | 450949193 |   455 |

## Расширения файлов

``` metawarc stats -m exts ```

| extension    | size      | count |
|--------------|-----------|-------|
|              | 11462703  |   326 |
| assets       | 415       |     1 |
| atom         | 49031     |     2 |
| css          | 49487     |     7 |
| html         | 2554743   |   209 |
| ico          | 48191     |     4 |
| jpg          | 51804773  |   621 |
| js           | 22028222  |    11 |
| map          | 60117     |     3 |
| mp4          | 450949193 |   455 |
| pdf          | 718701387 |   178 |
| png          | 330774221 |  4427 |
| svg          | 7967      |     7 |
| txt          | 333       |     1 |
| unitypackage | 572539371 |   322 |
| webmanifest  | 684       |     1 |
| webp         | 3604014   |   242 |
| woff2        | 66009     |     3 |
| xml          | 933       |     2 |

