# [Vectree - платформа будущего программиста](http://vectree.ru/)

[![license][license-badge]][LICENSE] [![Codacy Badge](https://api.codacy.com/project/badge/Grade/96071bdddd4548eba86b955593671ec4)](https://www.codacy.com/app/vectree/resources?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=vectree/resources&amp;utm_campaign=Badge_Grade) 
[![Join the chat](https://img.shields.io/discord/436599210427547658?color=%23eb4e4e&label=discord&logo=discord&logoColor=white)](https://discord.gg/Qb2fBdR)

![alt text](https://sun9-7.userapi.com/c841624/v841624284/28b96/aJT1-hf8yts.jpg)

Vectree — открытая бесплатная платформа для начинающих разработчиков, помогающая приобрести ключевые навыки для трудоустройства в IT. Наша миссия помочь новичкам структурировать их обучение (направить его в нужное русло), помочь с подготовкой к последующему трудоустроиству. 

> На текущий момент мы создаем контент и переводим статьи для [курса по Java](https://github.com/vectree/resources/issues/38). Присоединяйтесь!

## Векторы и траектории

На платформе присутствуют векторы, траектории, проекты и менторы. Каждый вектор состоит из теории, видео, задач, тестов и ссылок на дополнительный материал, который поможет вам усвоить заданный материал или тему. По сути вектор - это урок. Просто странно названный :)

Траектория в свою очерель - план обучения, который состоит из нескольких векторов.

Образовательный конент мы создаем поэтапно:
- формируем этапы,
- ищем беплатные открытые материалы, что позволит студентам начать учиться на платформе,
- добавляем практическую часть и тесты,
- постепенно дополняем, переписываем и переводим имеющийся материал.

## Проекты

Как только вы получили все необходимые знания, вы закрепляете их на проекте в команде. Вам будет необходимо, используя все стандартные инструменты разработчика (CI, Git, Trello) реализовать аналог реальных проектов.

Проекты создаются:
- самостоятельно,
- на основе технического задания различных компаний,
- на основе предложений студентов или компаний.


## Менторы

Менторы же в свою очередь могут помочь как вам отдельно, так и вашей команде с Code Review (проверкой вашего кода), с объяснением материала и построением самого продукта.

Ментором может стать каждый! Если вы хотели бы стать ментором на платформе, то напишите на почту support@vectree.ru или в telegram @vladthelittleone. В письме укажите специализацию и ваш опыт. 

## Создание нового контента

Если вы хотите добавить курс, перевод, статью на платформу, то для этого был создан [данный репозиторий](https://github.com/vectree/sandbox). Возникли вопросы? Пишите на support@vectree.ru.

## Помощь и поддержка проекта

Любой может помочь нам с развитием данного проекта. На текущий момент мы усердно работаем над контентом по JavaScript, Java, Python, Java и это занимает достаточно много времени, тем более, что делается это на бесплатной основе. Если вам хочется помочь нам, напишите на почту support@vectree.ru или в telegram **@vladthelittleone**, наша команда введет вас в курс дела.

Чем вы можете помочь:
- исправить ошибки,
- проверить ссылки на ресурсы или добавить новые,
- добавить найденный в интернете полезный контент, открытый курс,
- добавить новые уроки, практические задания, тесты,
- перевести статью, курс,
- добавить конспект университетских лекций.

## Как устроен проект

Прежде всего, если вы хотите добавить в проект новый материал или просто помочь, [создайте issue](https://github.com/vectree/resources/issues/new). Мы в свою очередь отпишем вам в ближайшее время.

Сердцем данного репозитория является папка `vectors`, в которой лежат траектории, вектора, проекты (в последующем все это обозначаем, как **вектор**). Для каждого такого элемента создается отдельная папка в порядке нумерации. Например, в папке [0](https://github.com/vectree/resources/tree/master/vectors/0) лежит вектор `Git`. Сама папка вектора состоит из нескольких составляющих:

- `info.js` - файл с мета информацией о векторе,
- `stages` - папка с этапами вектора,
- `text.md` - текст, описывающий вектор.

**Stages** хранит информацию о этапах вектора (Для Git - ["Введение в Git"](https://vectree.ru/video/0/0/0), ["Основы Git"](https://vectree.ru/video/0/1/0) и т.д.). Каждый этап имеет свой тип и в зависимости от данного типа забирается соответствующий контент из папок `text`, `tasks`, `topics`, `digests`, `quizzes`, `code-tasks`.

Все картинки, используемые в уроках, лежат в данном [репозитории](https://github.com/vectree/images).


## License 

Материал распространяется под [Attribution-NonCommercial-ShareAlike 4.0 International](LICENSE.md).

[LICENSE]: ./LICENSE.md
[license-badge]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
