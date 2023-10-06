# amq-adapter

# помощь для разраба

### Обновление пакета

npm version [ <newversion> | major | minor | patch | premajor | preminor ]

npm publish

### Дистрибутивные теги

Человекочитаемые метки, которые помогают организовать и пометить разные версии публикуемого пакета. Являются своеобразным дополнением к семвер

#### npm publish --tag <tag>

npm publish --tag beta

#### npm dist-tag add <package-name>@<version> [<tag>]

npm dist-tag add example-package@1.4.0 stable

### Прекращение поддержки

#### npm deprecate <package-name> "message"

### Депубликация пакета 
Не рекомендуется, т.к. при достижении определенных условий, например, число скачиваний, удалить пакет нельзя

#### npm unpublish <package-name>@<version>