# FMF-FlexMixinsFramework v.1.1 by Nio 07.02.2021
### Мой Flex-фреймворк для работы с препроцессорами SASS/SCSS

Основан на добавлении миксинов полноценных флекс-конструкций через import внутри SASS/SCSS препроцессоров.
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

    @import _aic (align-items-center)

    @import fdjc (display: flex, justify content: center)

    @import fdr (display: flex, flex-direction: row)

    @import fdrjc_aic (display: flex, flex-direction: row, justify content: center, align-items: center)

    @import fdcjc_aic (display: flex, flex-direction: column, justify content: center, align-items: center)
