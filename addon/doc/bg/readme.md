# Четене на емисии (Read Feeds) #

* Автори: Noelia Ruiz Martínez, Mesar Hameed
* Съвместимост с NVDA: от 2018.3 до 2019.1
* Изтегляне на [стабилна версия][1]
* Изтегляне на [тестова версия][2]

Тази добавка предоставя бърз и лесен начин за четене от източници в Atom или
RSS формат с NVDA.  Източниците няма да бъдат опреснявани автоматично.
Когато споменаваме думата източници, имаме предвид както RSS, така и ATOM
канали.

## Инсталиране или обновяване: ##

Ако сте използвали предишна версия на тази добавка и вече имате папка с име
RSS или personalFeeds във вашата папка с потребителски настройки за NVDA,
когато инсталирате текущата версия, ще попаднете на диалог, който ще ви
попита дали искате да обновите добавката или да инсталирате на чисто.
Изберете обновяване, за да съхраните вашите запазени източници и да
продължите да ги използвате в новоинсталираната версия на readFeeds.

## Команди: ##

### Меню на Read Feeds ###

Можете да достигнете до подменюто на Read Feeds от менюто на nvda, подменюто
"Инструменти", където са налични следните опции:

#### Емисии... ####

Отваря диалогов прозорец със следните контроли:

* Филтриране по: Текстово поле за търсене на предходно запазени емисии.
* Списък на запазените емисии.
* Списък със статиите: Отваря диалогов прозорец, който представя списъка със
  статии от текущата ви емисия. Изберете статията, която искате да
  прочетете, и натиснете ENTER или задействайте бутона "Отвори уеб
  страницата на избраната статия", за да отворите съответната страница във
  вашия браузър. Задействайте бутона "Относно статията", за да отворите
  диалогов прозорец, показващ заглавието и връзката на избраната статия. От
  този диалогов прозорец ще можете да копирате информацията в клипборда.
* Отвори емисията: Отваря избраната емисия в приложението по подразбиране.
* Нов: Отваря се диалогов прозорец с текстово поле за въвеждане адреса на
  нова емисия. Ако адресът е валиден и емисията може да бъде записана, името
  й, въз основа на заглавието на емисията, ще се появи в дъното на списъка с
  информационни канали.
* Преименувай: Отваря диалогов прозорец с текстово поле за преименуване на
  избраната емисия.
* Изтрий: Отваря диалогов прозорец за изтриване на избраните емисии след
  потвърждение.
* Задай по подразбиране: Задава избраната емисия като такава по
  подразбиране, така че нейните статии могат да бъдат достъпвани посредством
  жестовете на NVDA.
* Затвори: Затваря диалоговия прозорец с емисиите.

##### Бележки #####

* Ако бъде създадена емисия с име "tempFeed", моля, преименувайте я, тъй
  като този файл може да бъде заместен при необходимост от създаването на
  емисия с вече съществуващо име.
* Емисията, зададена по подразбиране, не може да бъде премахната. Емисията
  "addressFile" ще бъде използвана като такава по подразбиране при нулиране
  на настройките, затова тя не може да бъде премахната.

####Копирай папката с емисиите... ####

Отваря диалогов прозорец, за да изберете папка, където можете да запишете
папката "personalFeeds" с вашите информационни канали. По подразбиране
избраната папка е директорията с конфигурационния файл на NVDA, където ще се
създаде папката "personalFeeds".

#### Възстанови емисиите... ####

Отваря диалогов прозорец за избор на папка, която заменя вашите емисии в
папката "personalFeeds". Уверете се, че указвате папка, съдържаща URL адреси
на емисии.

### Клавишни команди: ###

* Control+Shift+NVDA+Интервал: Съобщава URL адреса на текущата
  статия. Двукратното й натискане ще отвори уеб страницата.
* Control+Shift+NVDA+8: Опреснява текущо избраната емисия и съобщава
  най-новото заглавие от нея.
* Control+Shift+NVDA+I: Съобщава заглавието и препратката на текущата
  емисия. Двукратното й натискане ще копира заглавието и свързаната
  препратка в клипборда.
* Control+Shift+NVDA+U: Съобщава предишното заглавие в емисията.
* Control+Shift+NVDA+O: Съобщава следващото заглавие в емисията.

## Уведомления: ##

* Когато заглавието или URL адресът са били копирани.
* Когато не може да се осъществи свързване/обновяване на емисиите, или URL
  адресът не съответства на валидна емисия.
* NVDA ще изведе съобщение за грешка, ако не е възможно да се архивира или
  възстанови папката "personalFeeds".
* Заглавието на диалога за списъка със статиите показва името на избраната
  емисия и номера на наличните статии.

## Промени във версия 6.0 ##

* Когато е обновена емисията по подразбиране и тя спре да работи поради
  проблеми със сървъра, предишните статии не биват изтрити и могат да бъдат
  прочетени със съответните клавишни комбинации.
* Отстранен е проявил се отново проблем (регресия): Емисията по подразбиране
  пак може да се актуализира два пъти.

## Промени във версия 5.0 ##

* Диалогът за списъците със статии е подобрен.
* Съвместима с NVDA 2018.3 и по-нови версии (изисква се).
* Ако е необходимо, можете да изтеглите [последната версия, съвместима с
  NVDA 2017.3][3].

## Промени във версия 4.0 ##

* Добавен е бутон за отваряне на избраната емисия от диалоговия прозорец
  "Емисии".

## Промени във версия 3.0 ##

* Диалоговите прозорци за управление на файлове за емисиите са
  премахнати. Сега тяхната функционалност е включена в диалоговия прозорец
  за емисиите.
* Визуалното представяне на прозореца е подобрено, придържайки се към
  стандарта за изглед на прозорците, извеждани от NVDA.
* Емисията по подразбиране е записана в конфигурацията на NVDA. Следователно
  е възможно да зададете различни емисии по подразбиране за различните
  конфигурационни профили.
* Изисква NVDA 2016.4.


## Промени във версия 2.0 ##

* Помощ за добавката е достъпна от мениджъра на добавките.

## Промени във версия 1.0 ##

* Първоначално издание.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=rf

[2]: https://addons.nvda-project.org/files/get.php?file=rf-dev

[3]: https://addons.nvda-project.org/files/get.php?file=rf-o
