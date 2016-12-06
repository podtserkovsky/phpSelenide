# phpSelenide

[![Build Status](https://travis-ci.org/Enapiuz/phpSelenide.svg?branch=master)](https://travis-ci.org/Enapiuz/phpSelenide)


## Collection
* find(By $locator) - поиск одного элемента
* findAll(By locator) - поиск множества элементов
* click() - клик по элементу
* doubleClick() - двойной клик по элементу
* exists() - проверяет существование элемента на странице
* isDisplayed() - проверяет, что элемент виден на странице
* attribute($attrName) - получить значение атрибута элемента
* val() - получить значение элемента (для input - @value, для select - @value выбранного option)
* get($index) - получить элемент коллекции
* getCollection() - получить все найденные элементы
* getCollectionNotEmpty - получить все найденные элементы, с проверкой что хотя бы один элемент найден

## Condition list
* size($size)
* sizeGreaterThen($size)
* sizeGreaterThenOrEqual($size)
* sizeLessThen($size)
* sizeLessThenOrEqual($size)
* text($text)
* withText($text)
* value($value)
* attribute($attrName, $value)
* visible()
* checked()
* child(By $locator)

## ToDo
* Execute Javascript
* Get element html source
* ArrayIterator for ElementsCollection
* Wait()
* Element locator for assertion error
