  - [Русификатор для Kritika Global \<v1.6\>
    \[Shooran\#6186\]](#русификатор-для-kritika-global-v1.6-shooran6186)
      - [Установка](#установка)
      - [Использование](#использование)
      - [Обновление](#обновление)
      - [Дополнительные возможности](#дополнительные-возможности)
      - [Диагностика проблем при
        работе](#диагностика-проблем-при-работе)
      - [Способ интеграции в игру](#способ-интеграции-в-игру)
      - [Особенности перевода](#особенности-перевода)
      - [Возможности русификатора](#возможности-русификатора)
      - [FAQ](#faq)
          - [Q: Ты мне наверное вирус хочешь подложить\! Как я могу быть
            уверенным, что русификатор делает то, что ты
            обещаешь?](#q-ты-мне-наверное-вирус-хочешь-подложить-как-я-могу-быть-уверенным-что-русификатор-делает-то-что-ты-обещаешь)
          - [Q: У меня антивирус нашёл вирус, хоть ты и говоришь, что
            там всё
            нормально\!](#q-у-меня-антивирус-нашёл-вирус-хоть-ты-и-говоришь-что-там-всё-нормально)
          - [Q: Меня наверняка забанят за использование сторонних
            программ\!](#q-меня-наверняка-забанят-за-использование-сторонних-программ)
          - [Q: Говоришь никак в игру не вмешиваешься, тем временем и
            русификатор запускается вместо патчера и патчер сам
            закрывается](#q-говоришь-никак-в-игру-не-вмешиваешься-тем-временем-и-русификатор-запускается-вместо-патчера-и-патчер-сам-закрывается)
          - [Q: Ты хочешь украсть мой игровой
            аккаунт\!](#q-ты-хочешь-украсть-мой-игровой-аккаунт)
          - [Q: Ты меня не убедил. Как мне узнать, что русификатор не
            делает ничего
            лишнего?](#q-ты-меня-не-убедил.-как-мне-узнать-что-русификатор-не-делает-ничего-лишнего)
          - [Q: Зачем вообще нужен этот русификатор? Надо убедить
            разработчиков сделать официальную RU локализацию. А
            пока можно просто из RU-версии копировать текстовый файлик
            немного поменяв и
            все.](#q-зачем-вообще-нужен-этот-русификатор-надо-убедить-разработчиков-сделать-официальную-ru-локализацию.-а-пока-можно-просто-из-ru-версии-копировать-текстовый-файлик-немного-поменяв-и-все.)
          - [Q: Я нажал в патчере Game Start до того как он закрылся и
            получил какую-то
            ошибку](#q-я-нажал-в-патчере-game-start-до-того-как-он-закрылся-и-получил-какую-то-ошибку)
          - [Q: Хочу помочь с переводом. Что для этого
            надо?](#q-хочу-помочь-с-переводом.-что-для-этого-надо)
          - [Q: Как работает включение японской озвучки (с)
            MoonShi?](#q-как-работает-включение-японской-озвучки-с-moonshi)
          - [Q: У меня обновление останавливается на файле
            `resource\Common\database\FontConfig_ja-JP.txt` и выдаёт
            ошибку. Что
            делать?](#q-у-меня-обновление-останавливается-на-файле-resourcecommondatabasefontconfig_ja-jp.txt-и-выдаёт-ошибку.-что-делать)
          - [Q: Ты обещал, что имена и названия будут в оригинале, а у
            меня всё на
            русском?](#q-ты-обещал-что-имена-и-названия-будут-в-оригинале-а-у-меня-всё-на-русском)
          - [Q: Как удалить русификатор?](#q-как-удалить-русификатор)
          - [Q: Можно на время включить английский язык, проверить
            кое-что?](#q-можно-на-время-включить-английский-язык-проверить-кое-что)
          - [Q: Где всё-таки взять 32-битную
            версию?](#q-где-всё-таки-взять-32-битную-версию)
          - [Q: Что такое и для чего нужен
            blake3\_dotnet.dll?](#q-что-такое-и-для-чего-нужен-blake3_dotnet.dll)
          - [Q: Русификатор еще что-то распаковал и видимо запускает
            (tesseract51.dll, leptonica-1.83.0.dll, eng.traineddata).
            Что
            это?](#q-русификатор-еще-что-то-распаковал-и-видимо-запускает-tesseract51.dll-leptonica-1.83.0.dll-eng.traineddata.-что-это)
          - [Q: Зачем вообще такие сложности с распознаванием текста
            (OCR)?](#q-зачем-вообще-такие-сложности-с-распознаванием-текста-ocr)
          - [Q: Что вообще за куча папок и файлов создается при
            работе?](#q-что-вообще-за-куча-папок-и-файлов-создается-при-работе)
          - [Q: Куда смотреть в случае
            проблем?](#q-куда-смотреть-в-случае-проблем)
          - [Q: Как с тобой связаться?](#q-как-с-тобой-связаться)
      - [История версий](#история-версий)



-----

## Русификатор для Kritika Global \<v1.6\> \[Shooran\#6186\]

**Спасибо за помощь в работе над локализацией**: `MoonShi`, `SmO.Oke`

**Отдельное спасибо за идеи и улучшение перевода:** `FeniXkiller`

-----

### Установка

  - Ссылка на данное руководство в PDF формате:
    https://github.com/ShooranT/K-Ru-Localizer/raw/main/Kritika-Localizer.pdf
  - Скачайте архив русификатора по постоянной ссылке:
    https://github.com/ShooranT/K-Ru-Localizer/raw/main/KritikaLocalizer.zip
      - **Данная ссылка всегда будет указывать на текущую актуальную
        версию**
      - **НЕ скачивайте из других мест, там может быть что угодно**
      - Проверить скачанное на вирусы можно тут:
        https://www.virustotal.com/gui/home/upload
  - **Внимание\! Для корректной работы требуются оригинальные файлы
    игры, если вы до этого “русифицировали” за счет подмены
    `FontConfig_en-EN.txt` файлом из RU-Kritika, то потребуется вернуть
    его обратно, иначе русификатор будет работать некорректно**
      - Если вы забыли сделать бэкап перед экспериментами с
        локализацией, то надо либо переустановить игру (или
        дождаться очередного обновления), либо можно скачать [вот эту
        версию](https://github.com/ShooranT/K-Ru-Localizer/raw/main/FontConfig_en-EN.zip)
        (внимание\! может быть устаревшей)
          - Файл нужно будет распаковать сюда:
            `Kritika_Global\resource\Common\database`
  - **Внимание\! Для работы русификатора НЕ нужны никакие данные
    аккаунта, ничего не надо активировать и т.п.**
  - **Данная версия русификатора предназначена для 64-битных Windows**,
    если у вас версия 32-битная, то загляните в FAQ там есть вариант и
    для нее.
  - Распакуйте архив в папку, где русификатор будет работать
      - На рабочий стол этого делать не стоит, так как в процессе работы
        создаются дополнительные файлы и в итоге рабочий стол
        замусорится
          - Оптимально куда-нибудь поближе, например к играм, `C:\Games`
  - Запускать русификатор вручную потребуется в трех случаях:
    **установка**, **удаление** или **переключение параметров**
  - Запускаемый файл русификатора: `KritikaLocalizer.exe`
  - **После подготовки (распаковки в нужную папку) запустите в первый
    раз, убедитесь что путь к игре верный (если нет введите
    правильный, а лучше переустановите игру, так как
    русификатор определяет установленную игру тем же способом,
    что и обычный патчер и если он показывает неверный путь, то и
    Kritika Global сама по себе не заработает) и нажмите `Enter`**

![image-20220614031143297](/img/625c09aa1c7d59096769df527cf6be55d98998ec.png)

  - **Дальше русификатор подготовит необходимые локальные файлы,
    запустит для проверки стандартный патчер Kritika Global и
    выйдет**

-----

### Использование

  - Просто играйте как обычно с **авторизацией на сайте** и **запуском
    игры через сайт** (если вдруг русификатор у вас попросит какие-то
    данные для входа, то это **НЕ оригинал**, для работы русификатору
    **НЕ** нужны никакие логины и пароли). Русификатор будет
    автоматически запускаться, при необходимости обновлять
    файлы русского языка, запускать штатный патчер и игровой клиент.

-----

### Обновление

  - Русификатор обновляет файлы переводов автоматически и если
    существенных изменений в механике локализации не будет, то
    обновлять сам русификатор не обязательно.
  - Обновить русификатор можно для доступа к новым возможностям, если
    такие будут появляться.
  - Обновление выполняется **вручную** по желанию: для этого нужно
    скачать русификатор по [обычной
    ссылке](https://github.com/ShooranT/K-Ru-Localizer/raw/main/KritikaLocalizer.zip)
    и распаковать с заменой файлов в то место, куда вы его установили в
    первый раз. Предварительно **удалять НЕ надо** ничего, так как тем
    самым вы сотрете конфигурацию и что самое главное свои бэкапы.
  - Начиная с версии `v1.2` русификатор будет показывать при запуске,
    оповещение о том, что доступна новая версия. Проверка выполняется
    раз в неделю.

-----

### Дополнительные возможности

  - Запуск русификатора из папки, где он был сохранен после
    первоначального конфигурирования покажет дополнительное
    меню:
    
    ![image-20220614224433684](/img/0b429b66c469766e06e5974d8583f1cf986b2acb.png)

  - Для выбора вводите число с нужным пунктом и `Enter`

  - **Даёт возможность удаления русификатора, повторной установки и
    переключения языка игрового клиента обратно на английский без
    удаления русификатора (игра будет запускаться на английском как
    обычно), а также с версии 1.1+ включение японской озвучки**

-----

### Диагностика проблем при работе

  - Если в работе русификатора возникнут проблемы, то мне для
    диагностики желательно получить скриншот (если возможно)
    и из каталога, откуда запускается русификатор файл:
    **`KritikaLocalizerLog.txt`**

-----

### Способ интеграции в игру

  - Русификатор **НЕ** использует никаких “хитрых” способов для своей
    интеграции, никак **НЕ** модифицирует исполняемые файлы игры. Всё
    что он делает, создает **недостающие** файлы локализации (по
    аналогии с другими языками) и запускает игровой клиент,
    после этого **завершает** свою работу. Во время игры
    русификатор **НЕ** работает.
  - Для локализации используется **штатный** способ игрового клиента с
    нужным языком
  - Таким образом русификатор никак не пересекается с работой защитной
    системы (XignCode) и никак на нее не влияет. Создаваемые файлы
    являются текстовыми и стандартными файлами ресурсов.

-----

### Особенности перевода

  - За основу берётся **английская** локализация
  - Имена, названия, идентификаторы и т.п. **НЕ переводятся**, чтобы не
    создавать разночтений при общении с другими игроками
  - Для остального берётся официальный RU-перевод, различными
    эвристическими методами сопоставляется возможность
    использования каждой из строк перевода (например, **если
    различаются числовые значения в RU и EN локализациях, то будет
    оставлена EN-локализация, чтобы не вводить в заблуждение**)
  - **Таким образом, переведено будет не больше, чем есть в RU версии.
    По факту - меньше, так как часть строк совершенно новые или
    отличаются значениями**
  - Перевод (по факту объединение RU и EN локализаций) делается
    автоматически по определённому алгоритму, никакого ручного
    или автоматического **перевода** (например, через Google Translate)
    **НЕ делается.**

-----

### Возможности русификатора

  - Перевод автоматически обновляемый - при обновлении игры, русский
    вариант автоматически перестроится с учётом изменений английской
    версии. **Дополнительно делать ничего не нужно.**
  - Русский перевод из RU-версии обновляется пока мною вручную, при
    обновлении русификатор при очередном запуске так же обновится
    на обновлённую версию, то есть если RU-версия будет в каком-то
    виде получать схожий контент и переводить его, то в
    полуавтоматическом режиме (через меня) это можно будет
    получать и в Global версии. **Дополнительно делать ничего не
    нужно.**
  - **Помимо автоматического перевода, так же есть возможность вручную
    сделать перевод недостающего, можно выборочно, либо
    целенаправленно все перевести. Если найдутся
    желающие, то свяжитесь со мной расскажу детали. В
    русификатор уже заложена такая возможность, если будут
    появляться дополнительные файлы перевода, то я смогу их
    выкладывать для всех и русификатор автоматически подхватит
    при очередном запуске без каких-либо дополнительных действий**
      - Статистика (на момент версии `v1.0`)
          - Всего строк в файле локализации порядка 200 000 строк.
          - Сейчас совершенно новых строк, требующих перевода - **2852**
            (1.5%)
          - Еще **1032** строки (0.5%) строки требуют ручной вычитки и
            возможной корректировки
      - В целом объемы не очень большие. Для перевода потребуется Excel
        или любая другая программа для работы с Excel таблицами. Сами
        файлы для перевода готовы и автоматизировано их формирование.

-----

### FAQ

#### Q: Ты мне наверное вирус хочешь подложить\! Как я могу быть уверенным, что русификатор делает то, что ты обещаешь?

**A:** В целом никому не навязываю :) Под основной ссылкой, есть ссылка
на результаты тестирования универсальным антивирусом. Можно скачать
проверить чем-то своим доверенным, или закинуть архив опять на тот
же https://www.virustotal.com/gui/home/upload уже самому вручную.

#### Q: У меня антивирус нашёл вирус, хоть ты и говоришь, что там всё нормально\!

**А:** Для начала убедись, что скачал именно по ссылке, которую я
привожу в самом начале. Если все нормально, но антивирус
ругается, то возможно все дело в ложноположительном
срабатывании. Это когда антивирус ошибочно считает (или
подозревает), что в программе вирус. Самый простой способ
убедиться, что все в порядке - это проверить другими
антивирусами. Я сам рекомендую сервис
[VirusTotal](https://www.virustotal.com/) - он проверяет файл
несколькими десятками антивирусов одновременно и дальше можно
сравнить результаты и понять, насколько реальна проблема.

О том, что эта ситуация в порядке вещей, можно почитать например на
сайте Microsoft: [Устранение ложных положительных/отрицательных
срабатываний в Microsoft Defender для конечной
точки](https://docs.microsoft.com/ru-ru/microsoft-365/security/defender-endpoint/defender-endpoint-false-positives-negatives?view=o365-worldwide)
или к примеру тут: [Ложноположительный результат антивируса: его
опасности и как их
избежать](https://itigic.com/ru/false-positive-of-an-antivirus-its-dangers-and-how-to-avoid-them/)

#### Q: Меня наверняка забанят за использование сторонних программ\!

**A:** Никакой гарантии дать не могу, так как в конце концов это не
официальная локализация. Но могу гарантировать, что русификатор
никак не вмешивается в процессы работы игры. Добавляется только три
файла полностью относящиеся к локализации и ничему другому, причем
которые и так были на бета-тесте, но потом их убрали видимо из-за
конфликта с RU-издателем. Поэтому риски минимальны. Кроме того,
исторически ALLM относились достаточно лояльно к подобным
изменениям ресурсов.

#### Q: Говоришь никак в игру не вмешиваешься, тем временем и русификатор запускается вместо патчера и патчер сам закрывается

**А:** Русификатор интегрирует себя вместо патчера как обработчик того
же протокола, что и Kritika Global. Это требуется делать, так как
авторизация Kritika делается на их сайте и необходимо получить
корректные параметры для правильного запуска игрового клиента.
Вторая причина - я хотел минимизировать какое-то взаимодействие с
русификатором. Один раз запустил и забыл. Такой обработчик как раз
хорошее место, чтобы русификатор запускался автоматически и при этом
никак не трогал исполняемые файлы игры, не оставляя там никаких следов
своей работы. Патчер автоматически закрывается для удобства, чтобы не
делать лишний клик. При этом русификатор никак не взаимодействует с
патчером, кроме отправки в нужный момент стандартного запроса с
“просьбой” выхода. Для детекта подходящего момента, делается
периодически скриншот окна патчера и проверяется по сообщениям
закончил ли он обновление.

#### Q: Ты хочешь украсть мой игровой аккаунт\!

**A:** Повторюсь - никому не навязываю использование русификатора :)
Авторизация в игре выполняется через веб, для этого надо зайти на
сайте и ввести свои данные. **Обрати внимание:** русификатор в этот
момент момент **НЕ работает**. Русификатор запускается **после**
завершения авторизации и нажатии на **Game Start** на сайте. В
этот момент русификатору (или патчеру в оригинале) передается
специальный код, который сначала сообщается игровому клиенту, а
игровой клиент серверу, чтобы подтвердить, что это именно нужный игрок
вошел в игру. Код является временным и привязанным к конкретному
компьютеру и браузеру. Его бессмысленно где-то еще использовать.
Сам по себе он не содержит никакой информации о том, кто входит и куда.

**Поэтому у русификатора (и любой другой программы) нет никакой
возможности украсть аккаунт перехватом кода с сайта**.
Теоретически такая возможность есть (никак не относящаяся к
русификатору), если в браузере стоит какое-нибудь вирусное
расширение или что-то перехватывает работу в браузере,
мониторит нажатия и вводимые данные, но это совсем другая тема.
Сам по себе русификатор, повторюсь не работает в момент ввода данных
аккаунта.

Чтобы понять техническую часть и почему код авторизации ничего не дает
другому компу или клиенту можно начать с чтения этой статьи -
https://ru.wikipedia.org/wiki/OAuth или погуглить по ключевому слову
`OAuth`

#### Q: Ты меня не убедил. Как мне узнать, что русификатор не делает ничего лишнего?

**A:** Если сомнения так и остаются, то мне кажется уже пора на этом
месте забить и не использовать :) Русификатор написан на .NET Core,
никакой защиты сверху не накладывалось. Так что можно взять любой
декомпилятор для .NET и изучить декомпилированные исходники, чтобы
понять, что всё в порядке.

#### Q: Зачем вообще нужен этот русификатор? Надо убедить разработчиков сделать официальную RU локализацию. А пока можно просто из RU-версии копировать текстовый файлик немного поменяв и все.

**А:** Пока существует RU-версия (а возможно и потом, прецеденты были),
разработчики (ALLM) даже не могут создать RU-канал на официальном
дискорде. Им это запрещено по контракту с издателем, хотя
формально `Kritika Global` другая игра. Поэтому шансы на то,
что в `Kritika Global` появится официальный русский достаточно
маловероятны. Кроме появления самого языка его еще необходимо
будет кому-то поддерживать (переводить при изменении контента,
параллельно с другими языками), а если уйдет RU-издатель, то это
надо будет делать самим разработчикам, что может быть весьма
проблематично.

С “текстовым файликом” всё неоднозначно - нужно это делать регулярно при
выходе апдейтов (при этом не забывая делать бэкапы оригинальных файлов,
так как иначе патчер не сможет обновиться), заменяется всё, включая
названия, часть перевода не соответствует действительности, так как
изменились числовые значения и т.п. проблемы. Но если в таком виде
устраивает, то почему бы и нет.

#### Q: Я нажал в патчере Game Start до того как он закрылся и получил какую-то ошибку

**A:** Не трогай патчер, пока он сам не закроется. Если он уже
обновился, но не хочет закрываться, то его надо закрыть
(**крестиком**), а **НЕ нажимать** `Game Start`. Причина в том, что
`Game Start` в патчере запустит игровой клиент, тоже самое сделает и
русификатор. Для правильной работы нужно, чтобы это делал только
русификатор.

#### Q: Хочу помочь с переводом. Что для этого надо?

**A:** Свяжитесь со мной (`Shooran#6186`). У меня есть подготовленные
файлы, которые можно перевести и тем самым дополнить перевод. Не
обязательно переводить всё полностью. Можно какие-то ключевые
моменты, которых не хватает в игровом клиенте, найти в файле
перевода, который я дам, и перевести. Дальше присылаете мне этот
файл назад, а я делаю общее обновление.

#### Q: Как работает включение японской озвучки (с) MoonShi?

A: Автор идеи `MoonShi`.

**Для включения запустите русификатор (нужна версия 1.1+) без параметров
и выберите `5й пункт`. Выключить ее можно при повторном выборе.**

**Внимание\! Корректное взаимодействие с патчером реализовано начиная с
версии v1.2+. Если при запуске патчера все равно выдается ошибка, то
выключите на время озвучку, через дополнительное меню русификатора,
после этого обновление должно пройти нормально**

За возможность видеть при включении японской озвучке урон в привычном
виде, `MoonShi` отдельное спасибо за его мучения и предоставленные
текстуры. При этом, к сожалению, есть нюанс:

> Имейте ввиду, что в связи с тем что переключение клиента игры на
> Японский язык, меняет так же и систему вывода урона, при
> использовании упрощенной версии отображения урона на Японский.
> Японская система записи чисел отличается от всем нам привычной, из-за
> чего ваш урон будет отображаться некорректно, с этим ничего нельзя
> поделать, эта цена которую вы платите за Японскую Озвучку **(c)
> MoonShi**

![Image](/img/00e80f5298554ff1cbe557fec361e7b8e0646de9.png)

При работе в этом режиме вместо включения русского языка русификатор при
запуске включает японский язык. В итоге игровой клиент использует
звуковые файлы предназначенные для японской локализации. Чтобы
интерфейс не переключался на японский при этом необходимо заменить
файл перевода на английский или русский.

**Кроме дополнительных стандартных файлов перевода заменяется также файл
с изображением урона, чтобы выводить локализованные значения символов в
конце размера урона (damage.dds) вместо иероглифов.**

**Из особенностей**: в таком режиме игровой клиент запускается с
указанием, что текущий язык японский и текущая локаль японская.
Это может вылезти в самых разных местах.

Кроме того, японская озвучка пока не развивалась (хотя с появлением
японского как официально поддерживаемого языка всё может
улучшиться), поэтому новые NPC, скиллы и т.п. может быть без
озвучки совсем.

#### Q: У меня обновление останавливается на файле `resource\Common\database\FontConfig_ja-JP.txt` и выдаёт ошибку. Что делать?

A: Это последствия использования включения японской озвучки. Для версии
`v1.1` потребуется взять у кого-нибудь оригинальный файл
`FontConfig_ja-JP.txt` (или в крайнем случае перекачать игровой клиент).
Версия `v1.2` делает бэкап этого файла и восстанавливает при отключении
озвучки. Кроме того русификатор пытается мониторить лог обновления и
есть видит ошибки обновления пытается восстановить файлы
автоматически. Если автоматически не работает, то надо
просто отключить озвучку - это восстановит оригинальные файлы.

#### Q: Ты обещал, что имена и названия будут в оригинале, а у меня всё на русском?

A: Скорее всего ты заменял оригинальный файл `FontConfig_en-EN.txt`
русским и оригинальным названиям не откуда взяться. Нужно вернуть
файл и при следующем запуске русификатор построит обещанный вариант
перевода.

За находку спасибо `SmO.Oke`

Если вы забыли сделать бэкап перед экспериментами с локализацией, то
надо либо переустановить игру (или дождаться очередного обновления),
либо можно скачать [вот эту
версию](https://github.com/ShooranT/K-Ru-Localizer/raw/main/FontConfig_en-EN.zip)
(внимание\! может быть устаревшей)

  - Файл нужно будет распаковать сюда:
    `Kritika_Global\resource\Common\database`

#### Q: Как удалить русификатор?

A: Запустите русификатор без параметров и выберите `3й пункт`. При
удалении русификатора, удалятся файлы локализации, но японский
перевод не вернется в норму (не увидел в этом необходимости). Он
восстановится при очередном официальном обновлении. После удаления
русификатора можно спокойно удалить папку, где он находился.

#### Q: Можно на время включить английский язык, проверить кое-что?

A: Запустите русификатор без параметров и выберите `1й пункт`. Это
переключит язык при старте на противоположный. Дальше выходите из
русификатора и запускаете как обычно, игровой клиент запустится с
выбранным языком. Вернуть обратно русский можно по этой же
процедуре, просто еще раз выбрав `1й пункт` при запуске без
параметров.

#### Q: Где всё-таки взять 32-битную версию?

**A:**
https://github.com/ShooranT/K-Ru-Localizer/raw/main/KritikaLocalizer.x86.zip

Но, по-возможности, рекомендую 64-битную, если ПК позволяет и у вас
Windows 64-бита

#### Q: Что такое и для чего нужен blake3\_dotnet.dll?

**А:** Это библиотека для расчета
[хэшей](https://ru.wikipedia.org/wiki/%D0%A5%D0%B5%D1%88-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D1%8F)
файлов. Хэш файла (в двух словах) - это специальное значение (своего
рода контрольная сумма) уникальная для содержимого файла. Позволяет
однозначно определять, что содержимое файла, например, не изменялось.
Русификатор использует эту библиотеку, чтобы быстро проверять не
изменились файлы ресурсов оригинального перевода и не
перестраивать перевод при отсутствии изменений. Кроме того,
эта же библиотека используется для контроля целостности загрузки базы
для перевода и других файлов.

Исходные тексты и описание тут: https://github.com/xoofx/Blake3.NET

#### Q: Русификатор еще что-то распаковал и видимо запускает (tesseract51.dll, leptonica-1.83.0.dll, eng.traineddata). Что это?

**A:** `Tesseract` - это библиотека распознавания текста (OCR) по
изображению. `Leptonica` - это вспомогательная для нее
библиотека, использующаяся `Tesseract` для работы с
изображениями в разных форматах. `eng.traineddata` - это
данные для `Tesseract` для возможности распознавания английского
текста.

Исходные тексты и описание `Tesseract` тут:
https://github.com/tesseract-ocr/tesseract Исходные тексты и описание
`Leptonica` тут: https://github.com/DanBloomberg/leptonica

#### Q: Зачем вообще такие сложности с распознаванием текста (OCR)?

**A:** Причин несколько. Было необходимо, чтобы патчер закрывался
автоматически, так как иначе многие бы нажимали `Game Start` ,
вместо закрытия и получали бы проблемы с запуском. У патчера нет
нормального механизма индикации завершения обновления, о прогрессе
и разных событиях можно получить информацию в логах, а вот
подтверждение завершения - нет. В итоге, подтверждение надо
получать из его интерфейса. Для этого есть несколько вариантов, простой
вариант не подходит, так как патчер рисует свой интерфейс
([Qt](https://ru.wikipedia.org/wiki/Qt)), а не использует стандартные
элементы Windows. При этом я хотел минимизировать вмешательство в
работу патчера. Оптимальным показалось распознавать текст, так как
другие варианты подразумевает встраивание в процесс патчера, что плохо
воспринимается системами защиты, да и может работать нестабильно.

#### Q: Что вообще за куча папок и файлов создается при работе?

A: `Backup` - бэкап реестра и кэш разных вспомогательных данных
(например, хэши базовых файлов переводов)

`Data` - русский перевод и патч к нему во внутреннем формате

`tessdata` - данные для `Tesseract` для распознавания английского языка

`x64` (или `x86` на 32-битной системе) - библиотеки для работы
`Tesseract` (OCR) `KritikaLocalizer.cfg` - текущая конфигурация
русификатора `KritikaLocalizerLog.txt` - лог работы последнего
запуска русификатора

#### Q: Куда смотреть в случае проблем?

A: Разные диагностические сообщения записываются в
`KritikaLocalizerLog.txt` (находится в папке русификатора). Если будете
писать мне, то неплохо бы иметь дополнительно скриншот ошибки, если
есть.

#### Q: Как с тобой связаться?

A: Пишите мне в дисе на `Shooran#6186`, отвечу как будет возможность

-----

### История версий

  - `v1.6`
    
      - Возвращены оригинальные комбинированные названия (например, для
        легендарных кристаллов) (`FeniXkiller`)
    
      - Возвращены оригинальные названия рейдов (`FeniXkiller`)

  - `v1.5`
    
      - обновлена текстура для упрощенного урона при использовании
        японской озвучки (`MoonShi`)
        
        К сожалению, проблему полностью не решить из-за различий в
        системе обозначения чисел, поэтому придется мириться с
        тем, что есть
        
        ![image-20220712005825936](/img/7cf71686f6da4c76d532eb0c84e5915f43757eaf.png)
    
      - добавлен перевод некоторых строк с корейского пока без
        возможности автообновления (`FeniXkiller`)

  - `v1.4`
    
      - **добавлена совместимость с новой версией игрового клиента (патч
        от 6 июля 2022 года)**
      - больше не заменяются на русские названия в печатях (*Imprinting
        Set*) и схожих ситуациях (`FeniXkiller`)
      - сделана обратная замена названий скиллов в русском переводе в
        описаниях эффектов на оригинальные английские, чтобы убрать
        несоответствия (`FeniXkiller`)
      - добавлена настройка: можно регулировать на каком языке будут в
        итоге названия скиллов. По умолчанию - английские. (пункт `6`
        расширенной настройки)
      - русификатор проверяет собственную целостность при старте при
        доступности интернета

  - `v1.3`:
    
      - улучшена логика обработки OCR при запуске патчера

  - `v1.2`:
    
      - уведомление о выходе обновлений русификатора
      - проверка целостности файлов (соответствие оригиналу)
      - корректировка включения японской озвучки (`MoonShi`)

  - `v1.1`:
    
      - добавлена возможность автоматического включения японской озвучки
        (`MoonShi`)

  - `v1.0`:
    
      - начальная версия
