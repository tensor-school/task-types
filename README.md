# Types

Установите зависимости:

```
npm install
```

В файле `src/index.d.ts` типизируйте следующие функции:

1. Функцию `getPersons`, возвращающую массив объектов со следующими свойствами:

-   `name` - строка
-   `age` - число
-   `gender` - `'male'` или `'female'`

2. Функцию `personToString`, возвращающую строку и принимающую объект одного из следующих форматов:
    1. Пользователь:
    - `name` - строка
    - `age` - число
    - `gender` - `'male'` или `'female'`
    2. Сотрудник
    - `name` - строка
    - `age` - число
    - `gender` - `'male'` или `'female'`
    - `company`- строка

Реализацию функций писать не нужно, достаточно просто добавить типы.

Проверить себя можно запустив команду `npm run test`.

После выполнения задания создайте pull request с решением.
