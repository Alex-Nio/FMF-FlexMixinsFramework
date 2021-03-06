# FMF-FlexMixinsFramework v.1.1 by Nio 07.02.2021
### Мой Flex-фреймворк для работы с препроцессорами SASS/SCSS

Основан на добавлении миксинов полноценных флекс-конструкций через include внутри SASS/SCSS препроцессоров.
***
### Основные моменты и обозначения:

**Свойства:**

    fd = (Свойство> display: flex)

    r = (Обозначение flex-direction: row)
    
    c = (Обозначение flex-direction: column)

    j = (Свойство> justify content)

    _ai = (Свойство> align-items)

---
**Состояния justify content:**

    js (Состояние: flex-start) т.е justify+состояние start

    jc (Состояние: center) т.е justify+состояние center

    jsb (Состояние: space-between) т.е justify+состояние space-between

    jsa (Состояние: space-around) т.е justify+состояние space-around

    jse (Состояние: space-evenly) т.е justify+состояние space-evenly

---
**Состояния align-items:**

    _ais (Состояние: align-items: flex-start)

    _aic (Состояние: align-items: flex-center)

    _aie (Состояние: align-items: flex-end)
---
#### Примеры использования:

    @include _aic (align-items: center)

    @include fdjc (display: flex, justify content: center)

    @include fdr (display: flex, flex-direction: row)

    @include fdrjc_aic (display: flex, flex-direction: row, justify content: center, align-items: center)

    @include fdcjc_aic (display: flex, flex-direction: column, justify content: center, align-items: center)


![FMFTemplate](https://user-images.githubusercontent.com/80686716/173562107-d2efd330-1a79-42c1-86ac-6baa1ed12ca8.jpg)
