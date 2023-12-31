## Ruby on Rails  
* github: github.com/rubywarlock

### О себе
https://github.com/rubywarlock/about.md  

Командный опыт работы. Jira, Trello. Agile, Scrum. Спринты и ежедневные стендапы.  

#### Пет проекты.

Было несколько демо проектов, хостились на Heroku, но Heroku ввела платные БД и они перестали работать, поэтому по мере свободного времени буду их переносить на новый хост:

array-diff: https://github.com/rubywarlock/Go-diff  
Простая программа на Go, написал в качестве изучения Go, которая сравнивает элементы массивов  
и выводит разницу.  
Планирую туда добавить возможность проходить многомерный массив.  

short-url: https://github.com/rubywarlock/ShortUrls  
Генерирует короткие урлы для внешних ссылок сайтов, есть приватные и публичные урлы.  
Есть временные и пермаментные, временные удалялись джобой которая запускалась  
в планировщике Heroku.  

Блог: https://github.com/rubywarlock/arcane-insland-1595  
В админке можно управлять меню в том числе их расположением на странице, аля мини CMS,  
так-же доступна загрузка файлов, проект старый(9 лет) и заброшенный, в планах есть его снова  
поднять по мере возможностей.  

Категории: https://github.com/rubywarlock/categories  
В проекте демонстрируется вложенность категорий и их отображение относительно  
глубины вложенности. Проект старый и тоже заброшенный.  

Код пишу исключительно с тестами, так как это удобно и быстрее и в будущем потом  
не возникает проблем с кодом. Понимание о необходимости тестов везде и всегда,  
пришло со временем и опытом. И это уже вошло в привычку. Предпочитаю Minitest,  
хотя на данный момент используется RSpec. Не смотря на то что RSpec собрано куча гемов  
для большинства нужд, я вижу как люди использующие RSpec часто любят делать там слишком  
большие моки. Minitest это самый необходимый набор для тестирования без излишков,  
его проще понять и изучить. И для него всегда можно подтянуть все необходимые гемы как в rspec.  

Программированием занимался с 2000 года.  
Прошел через языки:  C/C++, C#, Delphi/Pascal, Assembler, PHP, Python, Go, Java, Kotlin и тд.
Какое-то время, в начале пути, увлекался взломом игр, убирая требования диска или  
извлекая серийные номера, сделал пару "кряков" на этой основе для игр.  
Думаю что к настоящему моменту сложилось архитектурное мышление.  
Стремление к лаконичному, но при этом читаемому коду.  
Люблю оптимизировать код и искать новые алгоритмические решения.  

Хороший опыт в написании плагинов для Redmine разной сложности. Не смотря на то,  
что его многие ругают и что самое забавное ругают Рубисты(он же может давать им работу),  
его можно менять так как захочешь потому что это open source.  

Мнение про удаленную работу, иногда хорошо, но дома сложнее сконцентрироваться на работе.  
Лучше что бы был гибрид.  

Легаси код не пугает. Пугает количество проектов которые могут попасться,  
и не понимание работодателя о сроках, поэтому почасовую работу рассматриваю реже.  

О сложных вещах с которым приходилось сталкиваться. Часто спрашивают и я не понимаю  
чего хотят услышать. Дело в том, что понимание сложности вещей у всех разное - у кого-то это  
долгая и нудная работа над большим проектом, у кого-то это продумывание архитектуры  
оптимальной взаимосвязи моделей и реализация с хорошим алгоритмическим подходом.  
Мне нравится последнее.  

Не люблю Dry-rb. Так как приходится с ним работать на данный момент достаточно много времени,  
сложилось очень плохое мнение и есть с чем сравнивать.  
На мой взгляд Dry-rb плох тем, что он ухудшает код, повышает порог вхождения и понимание  
проекта(не смотря на противоположное мнение в некоторых кругах). Некоторые вещи тестировать  
в dry-rb сложно, люди из-за этого часто делают слишком много моков, в итоге многие  
части кода остаются без тестов. Dry-rb "учит" писать плохой код.  
ActiveInteraction считаю лучшей альтернативой Dry-rb.  

#### Основной стек Backend:
✪ Ruby / Ruby on Rails  
✪ Redmine / plugins  
✪ Kafka  
✪ Docker / Docker-Compose  
✪ Sidekiq / ActiveJob / Sidekiq-Scheduler / Cron  
✪ Dry-rb / ActiveInteractions  
✪ Devise  
✪ GraphQL / RESTful  
✪ Nokogiri  
✪ RVM / Rbenv  
✪ Minitest / RSpec  
✪ MongoDB / MySQL / PostgreSQL  

#### Опыт в других языках:  
✪ Java / Kotlin  
✪ Go  
✪ PHP  
✪ JavaScript  
✪ Python  
✪ C# / C / C++  
✪ Delphi / Object Pascal  
✪ Assembler

#### Опыт во frontend:
✪ html5 / html / haml / slim  
✪ css / scss / sass / bootstrap  
✪ Vue.js / Angular / JavaScript (не большой опыт)  

#### Deploy stack:
✪ Capistrano  
✪ Mina  
✪ ssh  
✪ Apache  
✪ Heroku  
✪ Unicorn  
✪ Nginx  

### Настоящее место работы

#### TDM Tech
Биллинг и геолокация.  
Коммерческие услуги на основе биллинга и сотовой связи.  
Немного приходится касаться серверной стороны: Nginx, Unicorn.  
стек: Ruby on Rails, Kafka, PostgreSQL, Sidekiq, RSpec, Gitlab, Dry-rb(почти весь набор), Docker

### Предыдущие места работы.

#### ООО "Центр обработки фискальных данных"
Сбор фискальных данных. Обработка, вычисления, хранение и аналитика данных.  
стек: Ruby on Rails, MongoDB, Sidekiq, ActiveInteraction(что-то типа dry-rb, только лучше), Gitlab CI, Pundit, Minitest, Docker.

#### SFXDX.
Ruby on Rails, Redmine.  
Создание и поддержка плагинов для.  
стек: Ruby on Rails, PostgreSQL, Sidekiq, Gitlab / CI, Minitest, rvm, Redmine, Docker. 

И др.
