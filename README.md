# Awesome Gamedev Blogs

Репозиторий содержит коллекцию веб-архивов блогов, посвященных процедурной генерации игровых объектов и разработке игр в целом. Веб-архивы были созданы при помощи [wpull](https://github.com/ArchiveTeam/wpull), метаданные были собраны с использованием [metawarc](https://github.com/datacoon/metawarc). Коллекция содержит результат анализа [ArchiveReady](https://archiveready.com) для каждого веб-архива.

В данном репозитории отсутствуют файлы веб-архивов .warc. Их можно найти на Google Drive, ссылка приведена в [соответсвующем разделе](#Веб-архивы формата .warc). Воспроизвести веб-архивы можно с помощью сервиса [Replay Webpage](https://replayweb.page).

# Краткое описание

Репозиторий содержит веб-архивы следующих сайтов:

* catlikecoding.com - набор туториалов для Unity, созданный независимым разработчиком [Джаспером Фликом](https://catlikecoding.com/jasper-flick/).
* codinglabs.net - набор статей и туториалов по низкоуровневой разработке графических элементов игр, созданный разработчиком из Blizzard Entertainment [Марко Аламиа](https://www.codinglabs.net/Authors.aspx#).
* redblobgames.com - набор статей и туториалов по процедурной генерации и моделированию сложных систем, созданный [Амитом Пателем](http://www-cs-students.stanford.edu/~amitp/)

Более подробное описание каждого веб-архива можно найти в README.md в соответствующих директориях.

# Методология

Для создания веб-архивов последовательно использовались следующие инструменты:

1. [wpull](https://github.com/ArchiveTeam/wpull) - библиотека Python и утилита командной строки для создания локальных веб-архивов. 
2. [Replay Webpage](https://replayweb.page) - сервис и приложение для воспроизведения веб-архивов.
3. [metawarc](https://github.com/datacoon/metawarc) - утилита командной строки для получения и обработки метаданных веб-архивов.
4. [ArchiveReady](https://archiveready.com) - сервис, определяющий индекс архивируемости сайтов по методике [CLEAR](https://purl.pt/24107/1/iPres2013_PDF/CLEAR%20a%20credible%20method%20to%20evaluate%20website%20archivability.pdf).

# Структура проекта

* Отдельные папки, названные в соответствии с доменными именами сайтов, вошедших в коллекцию. В каждой папке представлены следующие файлы:
  * README.md - описание сайта, анализ веб-архива.
  * <доменное имя сайта>.cdx - файл индексации формата (CDX Internet Archive Index)[https://www.loc.gov/preservation/digital/formats/fdd/fdd000590.shtml].
  * <доменное имя сайта>.log - файл журнала, созданный в процессе работы wpull.
  * <доменное имя сайта>.meta.jsonl - файл метаданных веб-архива, собранных с помощью metawarc.
  * <доменное имя сайта>.db - файл базы данных wpull.
  * metawarc.db – файл базы данных metawarc.

# Веб-архивы формата .warc

* [catlikecoding.com.warc.gz](https://drive.google.com/drive/folders/1_H-bb7338sZuzpQCf8aVkK1y6h0Z5T9c?usp=drive_link)
* [codinglabs.net.warc.gz](https://drive.google.com/drive/folders/1yNwSJJ98EjahQ_KtyB6cPIOnHLDCe2L5?usp=drive_link)
​​​​​​​* [redblobgames.com.warc.gz](https://drive.google.com/drive/folders/1Ji0dyAfjTEyKkwKKUIQ7O1eUTFpuX1Ig?usp=drive_link)


