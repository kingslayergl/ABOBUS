## **Базовые теги**

| ТЕГ | Описание |
|:-----:|:----------:|
| `<!--...-->` | тег для добавления комментариев в документ<br>Помещённые внутри него теги не интерпретируются браузером. |
| `<!DOCTYPE>` | показывает браузеру тип документа, сообщает его версию и язык. |
| `<html></html>` | корневой тег, который сообщает браузеру, что это HTML-документ. Все остальные элементы помещаются внутри него. |
| `<head></head>` | контейнер, в который помещаются метаданные документа, не видимые пользователям, но считываемые поисковыми роботами:<br> например, `<title>` или `<style>`. |
| `<meta>` | тег для оформления метаданных документа, используемых браузером для обработки страницы, а поисковиками — для индексации. |
| `<body></body>` | тег, обрамляющий видимую пользователям часть документа. Всё, что вы укажите внутри этого контейнера, отобразится на странице. Тег `<body>` имеет несколько атрибутов, позволяющих управлять **цветами**. |
| `<body bgcolor=?>` | цвет фона документа в формате RGB. |
| `<body text=?>` | цвет текста. |
| `<body link=?>` | цвет гиперссылок. |
| `<body vlink=?>` | цвет гиперссылок, по которым уже переходили. |
| `<body alink=?>` | цвет гиперссылок при нажатии. |
| `<title></title>` | метатег, который задаёт название страницы, отображаемое на вкладке браузера. |
| `<header></header>` | определяет содержимое блока с вводной информацией сайта или группой ссылок. |

## **Форматирование текста**

| ТЕГ | Описание |
|:-----:|:----------:|
| `<h1></h1>......<h6></h6>.` | теги заголовков, от самого большого к самому маленькому. |
| `<b></b>` | жирный текст без придания важности выделенному фрагменту. |
| `<strong></strong>` | расставление акцентов в тексте путём выделения его фрагментов полужирным начертанием. |
| `<i></i>` | выделение текста курсивом без придания важности. |
| `<del></del>` | зачёркивает текст, помечая его удалённым. |
| `<s></s>` | отображает перечёркнутый текст. |
| `<ins></ins>` | подчёркивает текст, визуально выделяя внесённые изменения. |
| `<u>` | подчёркивание без дополнительного акцентирования внимания. |
| `<em></em>` | расставление акцентов путём выделения фрагментов текста курсивом. |
| `<mark></mark>` | выделение частей текста жёлтым маркером. |
| `<tt></tt>` | имитация текста, набранного на печатной машинке. |
| `<small></small>` | отображение фрагмента с меньшим кеглем шрифта, чем у остального текста. |
| `<sub></sub>` | подстрочное начертание символов. |
| `<sup></sup>` | надстрочное начертание символов. |
| `<cite></cite>` | оформление цитат. |
| `<address>` | добавление контактов или подписи автора. При открытии в вею-браузере выделяется курсивом. |
| `<pre></pre>` | вывод неформатированного текста с сохранением пробелов и особенностей переносов. |
| `<p></p>` | контейнер для абзаца. |
| `<br>` | переносит текст на другую строку без создания абзаца. |
| `<blockquote> </blockquote>` | отступы с обеих сторон для оформления цитаты или врезки. |
| `<q></q>` | краткое цитирование. |
| `<dl></dl>` | контейнер для размещения термина и его определения. |
| `<dt>` | добавление термина. |
| `<dd>` | добавление определения понятия |
| `<dfn>` | выделение термина курсивом. Последующий текст должен раскрывать понятие. |
| `<abbr> ` | указывает, что текст является аббревиатурой или акронимом. Для добавления пояснения используется атрибут `title`. |
| `<ol></ol>` | список с цифрами. |
| `<ul></ul>` | список со значками. |
| `<li>` | отметка каждого элемента перечня (цифра или значок в зависимости от типа списка). |
| `<a></a>` | добавление гиперссылки в текст. Имеет обязательный атрибут href, в котором указывается ссылка или якорь. Внутри контейнера помещается текст, при нажатии на который происходит переход на другую страницу или другое место на этой же странице. |
| `<code></code>` | выделение фрагмента кода с помощью шрифта monospace.  |


## **Встраивание элементов**

| ТЕГ | Описание |
|:-----:|:----------:|
| `<img></img>` | вставка изображения. Имеет атрибут src, который указывает на адрес нужного файла. Есть и другие атрибуты: |
| `<img src="name" align=?>` | выравнивание к одной из сторон документа. Например, значение right переместит рисунок в правый край, а left — в левый. |
| `<img src="name" border=?>` | позволяет настроить в пикселях толщину рамки вокруг изображения. |
| `<hr>` | размещает на странице горизонтальную линию. Имеет несколько атрибутов. |
| `<hr size=?>` | устанавливает высоту линии. |
| `<hr width=?>` | устанавливает ширину линии. |
| `<hr noshade>` | убирает тень у линии. |
| `<hr color=?>` | задаёт цвет линии. |

## **Работа с таблицами**

| ТЕГ | Описание |
|:-----:|:----------:|
| `<table></table>` | размещает таблицу. Все остальные теги для форматирования таблиц должны находиться внутри это контейнера. |
| `<thead></thead>` | определяет заголовок. |
| `<tbody></tbody>` | отмечает тело таблицы. |
| `<td></td>` | создаёт одну ячейку. |
| `<th></th>` | указывает на заголовок ячейки. |
| `<tr>` | создание одной строки.   |
| `<tfoot></tfoot>` | показывает нижний колонтитул. |
| `<caption></caption>` | определяет название (заголовок) таблицы. |
| `<col>` | позволяет указать ширину и другие параметры одной или нескольких колонок. |
# Система контроля версий Git
![jj](![image](https://img2.reactor.cc/pics/post/full/%D0%BF%D0%B8%D0%B2%D0%BA%D0%BE-%D0%B1%D1%83%D1%85%D0%BB%D0%BE-%D1%83%D0%B4%D0%B0%D0%BB%D1%91%D0%BD%D0%BD%D0%BE%D0%B5-5185982.jpeg)


- [X] **Первоначальная настройка Git**
  
> Первое, что вам следует сделать после установки Git — указать ваше имя и адрес электронной почты.
  ```
    git config --global user.name ""
    git config --global user.email ""
  ```

> Создать локально новый репозиторий
  ```
    git init
  ```

- [X] **Просмотр конфигураций удаленных репозиториев**

> Список ваших удаленных подключений к другим репозиториям.
  ```
    git remote
  ```

> Аналогично команде выше, но включает URL-адрес каждого подключения.
  ```
    git remote -v
  ```

> Создание нового подключения к удаленному репозиторию.
  ```
    git remote add <name> <url>
  ```

> Удаление подключения к удаленному репозиторию с именем.
  ```
    git remote rm <name>
  ```

- [X] **Работа с удалёнными репозиториями**
  
> Клонировать существующий репозиторий
  ```
    git clone <url>
  ```

- [X] **Загрузка репозитория на сайт/локальный сервер**
  
+ Локальный
  
> Добавить все измененные файлы в индекс репозитория.
  ```
    git add .
  ```

> Запись индексированных изменений в репозиторий Git.
  ```
    git commit -m "Первый коммит"
  ```

> Переимновать индексированные изменения

  ```
    git commit --amend -m "Новый коммит"
  ```
- Сайт

>Отправка изменений
  ```
  git push -u origin main
  ```

> Извлечь из указанного удаленного репозитория копию текущей ветки и немедленно слить ее с локальной копией. 

  ```
  git pull
  ```

- [X] Работа с ветками в Git
> Команда git branch — главный инструмент для работы с ветвлением. С ее помощью можно добавлять новые ветки, перечислять и переименовывать существующие и удалять их.
>> Список всех существующих веток
  ```
    git branch -av
  ```

> Переключение в ветки
  ```
    git checkout <ветка>
  ```

> Создать новую ветку
  ```
    git branch <новая-ветка>
  ```

> Создать новую ветку и сразу переключится в нее
  ```
    git checkout -b <новая-ветка>
  ```

> Удалить локальную ветку
  ```
    git branch -d <ветка>
  ```

- [X] **Локальные изменения**
  
> Файлы в рабочей директории были изменены
  ```
    git status
  ```

> Изменения в отслеживаемых файлах
  ```
    git diff
    git diff <commit1> <commit2>
  ```

- [X] **История коммитов**

> Показать всю историю коммитов начиная с последних
  ```
    git log
  ```
> Показать историю изменений определенного файла
  ```
    git log -p <файл>
  ```
> Кто, какие и когда изменения вносил в <файл>
  ```
    git blame <файл>
  ```

- [x] **Отмена**

> Удалить все локальные изменения в рабочем каталоге
>> Это самый прямой, ОПАСНЫЙ и часто используемый вариант. При использовании аргумента `--hard` указатели в истории коммитов обновляются на указанный коммит. Затем происходит сброс раздела проиндексированных файлов и рабочего каталога до указанного коммита. Все предыдущие ожидающие изменения в разделе проиндексированных файлов и рабочем каталоге сбрасываются в соответствии с состоянием дерева коммитов. Это значит, что любая работа, находившаяся в состоянии ожидания в разделе проиндексированных файлов и рабочем каталоге, будет потеряна.
  ```
  git reset --hard <хэшcommit>
  ```

> Это режим работы по умолчанию. Указатели ссылок обновляются. Раздел проиндексированных файлов сбрасывается до состояния указанного коммита. Любые изменения, которые были отменены в разделе проиндексированных файлов, перемещаются в рабочий каталог.

  ```
  git reset --mixed <хэшcommit>
  ```

> При передаче аргумента `--soft` выполняется обновление указателей, и на этом операция сброса останавливается. Раздел проиндексированных файлов и рабочий каталог остаются неизменными. Четко продемонстрировать такое поведение довольно сложно. 

  ```
  git reset --soft <хэшcommit>
  ```

> Сбрасывает раздел проиндексированных файлов и рабочий каталог до состояния последнего коммита. Флаг `--hard` говорит Git, что нужно не только отменить изменения в разделе проиндексированных файлов, но и перезаписать все изменения в рабочем каталоге. Другими словами, эта команда уничтожит все неотправленные изменения, поэтому перед ее использованием убедитесь, что вы действительно хотите удалить ваши локальные наработки.

```
  git reset --hard
```

> Вернуть файл из стейджинга, но оставить изменения в нем неприкосновенными.

```
  git restore --staged myFile.txt
```

> Отменить локальные изменения в конкретном файле

```
  git restore myFile.txt
```

![ababa](c.gif)

