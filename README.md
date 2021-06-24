# FMF-FlexMixinsFramework v.1.1 by Nio 07.02.2021
Мой Flex-фреймворк для работы с препроцессорами SASS/SCSS

Основан на добавлении миксинов полноценных флекс-конструкций через import внутри SASS/SCSS препроцессоров.

Основные моменты и обозначения:

Свойства:
df = (Свойство> display: flex)
j = (Свойство> justify content)
_ai = (Свойство> align-items)

Состояния justify content:

js (Состояние: flex-start) т.е justify+состояние start
jc (Состояние: center) т.е justify+состояние center
jsb (Состояние: space-between) т.е justify+состояние space-between
jsa (Состояние: space-around) т.е justify+состояние space-around
jse (Состояние: space-evenly) т.е justify+состояние space-evenly

Состояния align-items:
_ais (Состояние: align-items: flex-start)
_aic (Состояние: align-items: flex-center)
_aie (Состояние: align-items: flex-end)


Примеры использования:
@import _aic (align-items-center)
@import dfjc (display: flex, justify content: center)
