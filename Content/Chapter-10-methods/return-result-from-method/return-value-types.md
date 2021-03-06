### Типове на връщаната от метода стойност

До сега разглеждахме примери, в които при декларация на методи използвахме ключовата дума **`void`**, която указва, че методът **не** връща резултат, а изпълнява определено действие.

![](/assets/chapter-10-images/10.Return-types-01.png)

Ако **заместим** **`void`** с **тип** на променлива, то това ще укаже на програмата, че метода трябва да върне някаква стойност от указания тип. Тази върната стойност може да бъде от всякакъв тип – **`int`**, **`string`**, **`double`** и т.н. 

<table><tr><td><img src="/assets/alert-icon.png" style="max-width:50px" />
</td><td>За да върне един метод <strong>резултат</strong> е нужно да внимаваме да напишем очаквания тип на резултата при декларацията на метода на мястото на <code>void</code>.</td></tr>
</table>

![](/assets/chapter-10-images/10.Return-types-02.png)

Важно е да отбележим, че **резултатът**, който се връща от метода, може да е от **тип, съвместим с типа на връщаната стойност** на метода. Например, ако декларираният тип на връщаната стойност е **`double`**, то можем да върнем резултат от тип **`int`**.
