---
title: Markdown
subtitle: Легковесный язык разметки для создания форматированного текста с помощью обычного текстового редактора.

# Summary for listings and search engines
summary: О облегченном языке разметки для создания форматированного текста с помощью обычного текстового редактора.

# Link this post with a project
projects: []

# Date published
date: '2022-05-13T14:30:00Z'

# Date updated
lastmod: '2022-05-13T14:30:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Markdown

categories:
  - Theory

---

## <b>Markdown</b>
<hr>

Markdown - это облегченный язык разметки для создания форматированного текста с помощью обычного текстового редактора. Джон Грубер и Аарон Шварц создали Markdown в 2004 году как язык разметки, который привлекателен для читателей-людей в форме исходного кода. Markdown широко используется в блогах, мгновенных сообщениях, онлайн-форумах, программном обеспечении для совместной работы, страницах документации и файлах readme.

Первоначальное описание Markdown содержало двусмысленности и вызывало вопросы без ответов, в результате чего реализации как намеренно, так и случайно отклонялись от первоначальной версии. Эта проблема была решена в 2014 году, когда давние участники Markdown выпустили CommonMark, однозначную спецификацию и набор тестов для Markdown.

## <b>История</b>
<hr>

В 2002 году Аарон Шварц создал atx, "настоящий формат структурированного текста". Затем Шварц и Грубер работали вместе над созданием Markdown language в 2004 году с целью дать людям возможность "писать, используя простой для чтения и записи формат обычного текста, при необходимости преобразовывая его в структурно допустимый XHTML (или HTML)".

Его ключевой целью дизайна была удобочитаемость, чтобы язык был читаемым как есть, не выглядя так, как будто он был помечен тегами или инструкциями по форматированию, в отличие от текста, отформатированного с помощью языка разметки, такого как Rich Text Format (RTF) или HTML, которые имеют очевидные теги и инструкции по форматированию. С этой целью его основным источником вдохновения являются существующие соглашения о разметке обычного текста в электронной почте, хотя он также заимствован из более ранних языков разметки, в частности setext, Textile и reStructuredText.

Грубер написал сценарий на Perl,``Markdown.pl ``, который преобразует выделенный текстовый ввод в допустимый, правильно сформированный XHTML или HTML и заменяет угловые скобки ``(<, >)`` и амперсанды ``(&)`` соответствующими ссылками на символьные сущности. Он может выполнять роль отдельного скрипта, плагина для Blosxom или подвижного типа, или текстового фильтра для BBEdit.

## <b>Подъем и расхождение</b>
<hr>

Поскольку популярность Markdowns быстро росла, появилось много реализаций Markdown, в основном из-за необходимости дополнительных функций, таких как таблицы, сноски, списки определений [примечание 1] и Markdown внутри HTML-блоков.

Поведение некоторых из них отличалось от эталонной реализации, поскольку Markdown характеризовался только неофициальной спецификацией и реализацией Perl для преобразования в HTML.

В то же время внимание привлек ряд двусмысленностей в неофициальной спецификации. Эти проблемы привели к созданию таких инструментов, как Babel mark, для сравнения результатов различных реализаций, а также к усилиям некоторых разработчиков анализаторов Markdown по стандартизации. Однако Грубер утверждал, что полная стандартизация была бы ошибкой: "Разные сайты (и люди) имеют разные потребности. Ни один синтаксис не сделал бы всех счастливыми".

## <b>Стандартизация</b>
<hr>

С 2012 года группа людей, в том числе Джефф Этвуд и Джон Макфарлейн, начали то, что Этвуд охарактеризовал как усилия по стандартизации. Веб-сайт сообщества теперь нацелен на "документирование различных инструментов и ресурсов, доступных авторам и разработчикам документов, а также разработчикам различных реализаций Markdown". В сентябре 2014 года Грубер возразил против использования "Markdown" в названии этого проекта, и он был переименован в CommonMark. CommonMark.org опубликовал несколько версий спецификации, эталонную реализацию, набор тестов и "[планирует] объявить окончательную спецификацию 1.0 и набор тестов в 2019 году". С тех пор не было выпущено ни одной спецификации 1.0, поскольку основные проблемы все еще остаются нерешенными. Тем не менее, следующие сайты и проекты приняли CommonMark: Discourse, GitHub, GitLab, Reddit, Qt, Stack Exchange (переполнение стека) и Swift.

В марте 2016 года были опубликованы два соответствующих информационных интернет-запроса:

В RFC 7763 введен MIME-тип ``text/markdown``.
В RFC 7764 обсуждались и регистрировались варианты MultiMarkdown, GitHub Flavored Markdown (GFM), Pandoc и Markdown Extra, среди прочих.
