Этот текст
будет
отображаться
в одну
строку

Новый параграф отделяется пустой строкой

*курсивное начертание текста*

_еще один способ курсивного начертания_

**полужирное начертание текста**

__ещё один способ полужирного начертания__

~~зачеркнутый текст~~

# Заголовок первого уровня

Еще один заголовок первого уровня
===

## Заголовок второго уровня

Еще один заголовок второго уровня
---

### Заголовок третьего уровня
###### Заголовок шестого уровня

Эта гиперссылка, но по ней можно кликнуть:
https://github.com

Это универсальное оформление для гиперссылки, и по ней можно кликнуть:
<https://github.com>

[Это гиперссылка, которая ведет на GitHub](https://github.com)

[Это гиперссылка с всплывающей подсказкой-тегом](https://github.com/DAlam6er "Мой профиль на ГитХабе")

Убедитесь, что [веб-сайт][1] доступен для обращения.

Среду разработки [IntelliJ IDEA][IDE] используют при разработке приложений на Java.


![Замещающий текст](https://unsplash.it/500/500?random "Всплывающее сообщение")

![Милый пёсель][cute dog]

Вложенная ссылка:

[![При нажатии откроется большая версия](https://unsplash.it/50/50?image=1012)](https://unsplash.it/500/500?image=1012)

Еще один пример вложенной ссылки, оформленной иначе:

[<img src="https://unsplash.it/50/50?image=1000">](https://unsplash.it/500/500?image=1000)

Markdown поддерживает обычный синтаксис HTML, например тег &lt;src>:

<img src="resources/dog.jpg" width="300" height="300" alt="">

## Unordered list, using asterisk

* milk
* eggs
* bread

## Unordered list, using minus
- milk
- eggs
- bread

## Unordered list, using plus
+ milk
+ eggs
+ bread

## Ordered list
1. Combine ingredients
    * Sift the flower
        This is inline string

        This is a nested paragraph and nested image inside bullet
        
        ![](https://unsplash.it/200/150?random)
2. Gently Stir together
3. Bake at 350 for 20 minutes

## Разрывы строк 
I don't like beans.<br>
Beans are evil.

## Горизонтальные линейки
Something

---

# Блоки цитат
>You miss 100% of the shots you don't take. -
>
>**Wayne Gretzky**
>
>Or maybe another author

# Блоки кода
```java
private static final String DB_NAME = "postgres";
public void setName(String name) {
    this.name = name;
}
```

```php
$age = 50;
$name = "wes";
echo stroupper($name);
```

```bash
echo "hello"
```

`int` in java usually initialized with 0:<br>
`int x = 0;`

The following code was changed:
```diff
var x = 100;
- var y = 200;
+ var y = 300;
```

Пример таблицы:

| Dog's Name | Dog's Age |
|:-----------|----------:|
| Snickers   |         2 |
| Prudence   |         8 |

Пример с checkboxes:

* [x] Get milk
* [ ] Crack eggs
* [ ] Cook bacon

[1]: https://google.com
[IDE]: https://www.jetbrains.com/ru-ru/idea/
[cute dog]: https://unsplash.it/500/500?image=1012
