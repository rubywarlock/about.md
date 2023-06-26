### Ruby on Rails  
* github: github.com/rubywarlock

#### О себе.  
Пишу код исключительно с тестами, так как это позволяет не только в будущем поддерживать код проще и понимать, но и вообще на этапе работы с чем-то новым, проверять и тестировать любые вещи которые я хочу использовать, и это проще и быстрее, чем тыкать и что-то руками через консоль.  Не люблю Dry-rb, так как приходится с ним работать на данный момент. Dry-rb плох тем, что он ухудшает код делая его более большим и громоздник(да-да, не смотря на противоположное мнение в некоторых кругах), он повышает порог вхождения в проект, он ухудшает понимание и поддержку кода. А некоторые вещи тестировать в dry-rb очень сложно, приходится делать слишком много моков в итоге эти части кода до конца не могут быть протестированы. Dry-rb короче говоря, "учит" писать плохой код.
Если что есть прекрасная замена Dry-rb, и это ActiveInteraction.

Предпочитаю Minitest, хотя на данный момент используется RSpec. Не смотря на то что RSpec собраны просто куча гемов уже вместе для большинства нужд, я вижу как люди использующие RSpec часто любят делать там слишком большие моки.
Minitest это самый необходимый набор для тестирования без излишков, его проще понять и изучить.
И для него всегда можно подтянуть гемы необходимые если чего-то не хватает.

Хороший опыт в написании плагинов для Redmine разной сложности. Не смотря на то, что его многие ругают и что самое забавное ругают Рубисты(он же может давать им работу), его можно менять так как захочешь потому что это open source.

#### Основной стек Backend:
✪ Ruby / Ruby on Rails  
✪ Redmine / plugins  
✪ Kafka  
✪ Docker / Docker-Compose  
✪ Sidekiq / ActiveJob / Sidekiq-Scheduler / Cron  
✪ ActiveAdmin  
✪ Devise  
✪ GraphQL / RESTful  
✪ Nokogiri / Parsing  
✪ Git / Github / GitLab / CI DI / Capistrano / Mina  
✪ Heroku / ssh / Puma / Unicorn / Nginx  
✪ RVM / Rbenv  
✪ Minitest / RSpec  
✪ MongoDB / NoSQL  
✪ MySQL / PostgreSQL  

#### Опыт во frontend:
✪ html5 / html / haml / slim / pug  
✪ css / scss / sass / bootstrap  
✪ Vue.js (не большой опыт)  
✪ Angular (не большой опыт)  
✪ JavaScript / TypeScript  

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

#### ООО "Центр обработки фискальных данных", аналитика данных, .
Сбор фискальных данных. Обработка, вычисления и хранения.  
стек: Ruby on Rails, MongoDB, Sidekiq, ActiveInteraction(что-то типа dry-rb, только лучше), Gitlab CI, Pundit, Minitest, Docker.

#### SFXDX.
Backend Ruby on Rails. Создание и поддержка плагинов для redmine.  
стек: Ruby on Rails, PostgreSQL, Sidekiq, Gitlab / CI, Minitest, rvm, Redmine, Docker.
