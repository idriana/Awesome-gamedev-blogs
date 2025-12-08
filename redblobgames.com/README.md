# Архив сайта redblobgames.com

Redblobgames.com - набор статей и туториалов по процедурной генерации и моделированию сложных систем, включая:
* Алгоритмы нахождения кратчайшего пути
* Работа с графами
* Работа со сплайнами
* Процедурная генерация ландшафта из шума
* Работа с функциями вероятности
* Построение зоны видимости

Сайт создан Амитом Пателем в качестве хобби.

# Веб-архив

В данном репозитории отсутствует файл .warc, его можно найти на [GoogleDrive](https://drive.google.com/drive/folders/1Ji0dyAfjTEyKkwKKUIQ7O1eUTFpuX1Ig?usp=drive_link).

# Воспроизведение веб-архива

Веб-архив можно воспроизвести с помощью сервиса [Replay Webpage](https://replayweb.page).

Содержимое веб-архива выглядит следующим образом:

<img width="1920" height="1038" alt="image" src="https://github.com/user-attachments/assets/9226ea43-be09-4508-bb31-5e32273fb535" />

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/cec39ff4-36df-4e2b-b6b5-d84ede6fb249" />


# Анализ ArchiveReady

<img width="469" height="266" alt="image" src="https://github.com/user-attachments/assets/b5c51019-77ed-4e08-a89f-d450fdda0fa2" />

* Низкая доступность обусловлена:
  * Ошибками RSS
  * Политиками robots.txt
  * Отсутствием sitemap.xml
  * Наличием неработающих ссылок на сайте
  * Наличием кода JavaScript в HTML документе
* Высокая целостность обусловлена отсутствием ссылок на изображения других сайтов.
* Высокий показатель метаданных обусловлен наличием метаданных на каждом изображении.
* Пониженный показатель соответствия стандартом обусловлен:
  * Ошибками HTML
  * Ошибками RSS

Данные ошибки не повлияли на качество архивации.

# Анализ metawarc

* Файл метаданных сохранен как catlikecoding.com.meta.jsonl.
* База данных metawarc сохранена как metawarc.db
* Извлеченные метаданные не включены в репозиторий, для их извлечения необходимо использовать metawarc на веб-архиве.

## Общая сводка

``` metawarc analyze redblobgames.com.warc.gz ```

| mimes                             | files |    size    |   share     |
|-----------------------------------|-------|------------|-------------|
| image/png                         | 1035  | 260388300  | 61.3276     |
| text/javascript                   | 581   | 30647622   | 7.21823     |
| text/html                         | 1496  | 28973901   | 6.82403     |
| video/webm                        | 13    | 22010704   | 5.18404     |
| video/quicktime                   | 2     | 17025583   | 4.00992     |
| video/mp4                         | 15    | 14048077   | 3.30865     |
| image/gif                         | 11    | 11101130   | 2.61458     |
| text/plain                        | 51    | 10684387   | 2.51642     |
| image/jpeg                        | 110   | 7325631    | 1.72536     |
| application/octet-stream          | 27    | 6731748    | 1.58548     |
| application/wasm                  | 7     | 5473894    | 1.28923     |
| application/zip                   | 6     | 4345181    | 1.02339     |
| application/pdf                   | 1     | 2511756    | 0.591578    |
| image/svg+xml                     | 13    | 985802     | 0.23218     |
| application/json                  | 6     | 753145     | 0.177383    |
| application/vnd.ms-fontobject     | 11    | 308715     | 0.0727096   |
| image/webp                        | 3     | 287598     | 0.0677361   |
| application/xml                   | 1     | 258181     | 0.0608077   |
| text/xml                          | 2     | 186100     | 0.0438309   |
| font/woff                         | 11    | 183795     | 0.043288    |
| font/woff2                        | 11    | 153165     | 0.036074    |
| image/avif                        | 2     | 103921     | 0.0244758   |
| text/css                          | 13    | 74472      | 0.0175399   |
| image/x-icon                      | 1     | 15486      | 0.00364732  |
| image/x-ms-bmp                    | 6     | 7080       | 0.00166751  |
| application/manifest+json         | 1     | 726        | 0.00017099  |
| **#total**                        | **3436** | **424586100** | **100** |

## Mime-типы

``` metawarc stats -m mimes ```

| mime                            | size      | count |
|-|-|-|
| application/json; charset=UTF-8 | 753145    |     6 |
| application/manifest+json       | 726       |     1 |
| application/octet-stream        | 6731748   |    27 |
| application/pdf                 | 2511756   |     1 |
| application/vnd.ms-fontobject   | 308715    |    11 |
| application/wasm                | 5473894   |     7 |
| application/xml                 | 258181    |     1 |
| application/zip                 | 4345181   |     6 |
| font/woff                       | 183795    |    11 |
| font/woff2                      | 153165    |    11 |
| image/avif                      | 103921    |     2 |
| image/gif                       | 11101130  |    11 |
| image/jpeg                      | 7325631   |   110 |
| image/png                       | 260388300 |  1035 |
| image/svg+xml; charset=UTF-8    | 985802    |    13 |
| image/webp                      | 287598    |     3 |
| image/x-icon; charset=UTF-8     | 15486     |     1 |
| image/x-ms-bmp                  | 7080      |     6 |
| text/css; charset=UTF-8         | 74472     |    13 |
| text/html                       | 116069    |   321 |
| text/html; charset=UTF-8        | 28857832  |  1175 |
| text/javascript; charset=UTF-8  | 30647622  |   581 |
| text/plain; charset=UTF-8       | 10684387  |    51 |
| text/xml; charset=UTF-8         | 186100    |     2 |
| video/mp4                       | 14048077  |    15 |
| video/quicktime                 | 17025583  |     2 |
| video/webm                      | 22010704  |    13 |

## Расширения файлов

``` metawarc stats -m exts ```

| extension         | size      | count |
|-|-|-|
|                   | 19878746  |  1023 |
| 3                 | 16796     |     1 |
| 3m                | 16796     |     1 |
| 3m-i386-linux-gnu | 16796     |     1 |
| a                 | 33592     |     2 |
| abc               | 50388     |     3 |
| align             | 3803899   |     1 |
| asdl              | 16796     |     1 |
| avif              | 103921    |     2 |
| bin               | 4466      |     1 |
| bmp               | 7080      |     6 |
| box               | 201552    |    12 |
| bsd               | 16796     |     1 |
| bxml              | 155341    |     2 |
| c                 | 50388     |     3 |
| cpp               | 40856     |     3 |
| cs                | 39716     |     2 |
| css               | 124860    |    16 |
| csv               | 45939     |     3 |
| db3               | 520565    |     1 |
| eot               | 308715    |    11 |
| exe               | 16796     |     1 |
| gif               | 11101130  |    11 |
| graphdata         | 204341    |     1 |
| h                 | 67184     |     4 |
| html              | 4109436   |   176 |
| hx                | 71859     |     5 |
| ico               | 15486     |     1 |
| java              | 40112     |     2 |
| jpg               | 7459999   |   118 |
| js                | 32410287  |   687 |
| json              | 770250    |     8 |
| jsx               | 10449     |     2 |
| key               | 16796     |     1 |
| lua               | 28469     |     2 |
| m                 | 16796     |     1 |
| map               | 1832545   |     6 |
| mod               | 33592     |     2 |
| mov               | 17025583  |     2 |
| mp4               | 14048077  |    15 |
| o                 | 33592     |     2 |
| org               | 602007    |    17 |
| pdb               | 16796     |     1 |
| pdf               | 2511756   |     1 |
| png               | 260741016 |  1056 |
| program           | 16796     |     1 |
| py                | 271490    |    24 |
| pyc               | 16796     |     1 |
| rs                | 34207     |     2 |
| so                | 33592     |     2 |
| svg               | 1187354   |    25 |
| text              | 16796     |     1 |
| ts                | 1155164   |    67 |
| ttf               | 323338    |    12 |
| txt               | 9946654   |    18 |
| types             | 134368    |     8 |
| wasm              | 5524282   |    10 |
| webm              | 22010704  |    13 |
| webmanifest       | 726       |     1 |
| webp              | 287598    |     3 |
| woff              | 183795    |    11 |
| woff2             | 153165    |    11 |
| xml               | 305736    |     2 |
| zip               | 4345181   |     6 |




