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
