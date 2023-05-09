# lecture_39_JS_Document_Styles_and_Сlasses

#  [Задачи ](https://github.com/schoolteacherMP/lecture_39_JS_Document_Styles_and_Classes/blob/main/tasks.md)  

**Для управления классами существуют два DOM-свойства:**  
**className** – строковое значение, удобно для управления всем набором классов.  
**classList** – объект с методами add/remove/toggle/contains, удобно для управления отдельными классами.  

**Чтобы изменить стили:**  
Свойство style является объектом со стилями в формате camelCase. Чтение и запись в него работают так же, как изменение соответствующих свойств в атрибуте "style". Чтобы узнать, как добавить в него important и делать некоторые другие редкие вещи – смотрите документацию.  

Свойство **style.cssText** соответствует всему атрибуту "style", полной строке стилей.  

Для чтения окончательных стилей (с учётом всех классов, после применения CSS и вычисления окончательных значений) используется:  

Метод **getComputedStyle**(elem, [pseudo]) возвращает объект, похожий по формату на style. Только для чтения.  

