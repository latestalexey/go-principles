# Философия архитектуры ООП, SOLID-принципы, Dry, KISS и YAGNI

## SOLID

За этой аббревиатурой скрываются 5 базовых принципов ООП, предложенные Робертом Мартином. Следование их духу сделает код легко тестируемым, расширяемым, читаемым и поддерживаемым.

Вот шпаргалка по этим принципам:

- (__S__) Single Responsibility Principle (принцип единственности ответственности)
- (__O__) Open/Closed Principle (принцип открытости/закрытости)
- (__L__) Liskov Substitution Principle (принцип подстановки Барбары Лисков)
- (__I__) Interface Segregation Principle (принцип разделения интерфейса) 
- (__D__) Dependency Inversion Principle (принцип инверсии зависимостей) 

Эти принципы были представлены Робертом Мартином в его статье [«Принципы проектирования и шаблоны проектирования»](https://web.archive.org/web/20150906155800/http://www.objectmentor.com/resources/articles/Principles_and_Patterns.pdf).

По словам Роберта С. Мартина, симптомы гниющего дизайна или плохого кода:

- Жесткость (трудно менять код, так как простое изменение затрагивает много мест);
- Неподвижность (сложно разделить код на модули, которые можно использовать в других программах);
- Вязкость (разрабатывать и/или тестировать код довольно тяжело);
- Ненужная Сложность (в коде есть неиспользуемый функционал);
- Ненужная Повторяемость (Copy/Paste);
- Плохая Читабельность (трудно понять что код делает, трудно его поддерживать);
- Хрупкость (легко поломать функционал даже небольшими изменениями);

Но это улучшение, теперь мы можем сказать что то вроде "мне не нравится это потому, что слишком сложно модифицировать", или "мне не нравится это потому, что я не могу сказать, что этот код пытается сделать", но что насчет того, чтобы вести обсуждение позитивно?

Разве это не было бы здорово, если бы существовал способ описать свойства хорошего дизайна, а не только плохого и иметь возможность рассуждать объективными терминами? Для этого нам на помощь спешат принципы проектирования архитектуры и написания программного кода.

Сейчас мы рассмотрим эти принципы на схематичных примерах. Обратите внимание на то, что главная цель примеров заключается в том, чтобы помочь читателю понять принципы SOLID, узнать, как их применять и как следовать им, проектируя приложения. Автор материала не стремился к тому, чтобы выйти на работающий код, который можно было бы использовать в реальных проектах.

В golang в качестве отдельных частей у нас есть - пакаджи, структуры, методы и интерфейсы. Давайте расссмотрим SOLID в этих терминах.

### Single Responsibility Principle (принцип единственности ответственности)


### Open/Closed Principle (принцип открытости/закрытости)


### Liskov Substitution Principle (принцип подстановки Барбары Лисков)


### Interface Segregation Principle (принцип разделения интерфейса) 


### Dependency Inversion Principle (принцип инверсии зависимостей) 


