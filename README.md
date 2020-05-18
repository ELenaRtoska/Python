# Python

## **Неинформирано пребарување**
### Подвижни препреки
Предложете соодветна репрезентација и напишете ги потребните функции во Python за да се реши следниот проблем за кој една можна почетна состојба е прикажана на слика 1:

![Screenshot (158)](https://user-images.githubusercontent.com/48455819/82221115-d97b6500-991f-11ea-9068-014811b38539.png)<br />
**Слика 1** <br />
"Потребно е човечето безбедно да дојде до куќичката. Човечето може да се придвижува на кое било соседно поле хоризонтално или вертикално. Пречките 1, 2 и 3 се подвижни, при што пречката 1 се движи хоризонтално, пречката 2 се движи дијагонално, а пречката 3 се движи вертикално. Секоја од пречките се придвижува за едно поле во соодветниот правец и насока со секое придвижување на човечето. Притоа пречката 1 на почетокот се движи во лево, пречката 2 на почетокот се движи горе-десно и пречката 3 на почетокот се движи надолу (пример за положбата на пречките после едно придвижување на човечето е прикажан на слика 2). Кога некоја пречка ќе дојде до крајот на таблата при што повеќе не може да се движи во насоката во која се движела, го менува движењето во спротивната насока. Доколку човечето и која било од пречките се најдат на исто поле - човечето ќе биде уништено."<br />

![Screenshot (156)](https://user-images.githubusercontent.com/48455819/82220630-2c085180-991f-11ea-8207-83226e038e0c.png)<br />
**Слика 2** <br />
За сите тест примери изгледот и големината на таблата се исти како на примерот даден на сликите. За сите тест примери почетните положби, правец и насока на движење за препреките се исти. За секој тест пример почетната позиција на човечето се менува, а исто така се менува и позицијата на куќичката.<br />

Во рамки на почетниот код даден за задачата се вчитуваат влезните аргументи за секој тест пример. Во променливите choveche_redica и choveche_kolona ги имате редицата и колоната во која на почетокот се наоѓа човечето (ако таблата ја гледате како матрица). Во променливите kukja_redica и kukja_kolona ги имате редицата и колоната во која се наоѓа куќичката (ако таблата ја гледате како матрица).
<br />
Движењата на човечето потребно е да ги именувате на следниот начин:
<br />
Desno - за придвижување на човечето за едно поле надесно<br />
Levo - за придвижување на човечето за едно поле налево<br />
Gore - за придвижување на човечето за едно поле нагоре<br />
Dolu - за придвижување на човечето за едно поле надолу<br />
Вашиот код треба да има само еден повик на функција за приказ на стандарден излез (print) со кој ќе ја вратите секвенцата на движења која човечето треба да ја направи за да може од својата почетна позиција да стигне до позицијата на куќичката. Треба да примените неинформирано пребарување. Врз основа на тест примерите треба самите да определите кое пребарување ќе го користите.


<br />

### Црно - бело
Предложете соодветна репрезентација и напишете ги потребните функции во Python за да се реши следниот проблем за кој една можна почетна состојба е прикажана на Слика 1:<br />
![Screenshot (160)](https://user-images.githubusercontent.com/48455819/82221846-cddc6e00-9920-11ea-90e1-0c0db0d2af05.png)
<br />
**Слика 1**<br />
"Tабла со димензии N x N се состои од бели и црни полиња. Со избор (кликнување) на едно поле се прави промена на бојата на тоа поле и на сите негови непосредни соседи (горе, долу, лево и десно) во спротивната боја, како што е прикажано на Слика 2. Целта е сите полиња на таблата да бидат обоени во црна боја. Потребно е проблемот да се реши во најмал број на потези т.е. со избирање (кликнување) на најмал можен број на полиња."<br />
![Screenshot (161)](https://user-images.githubusercontent.com/48455819/82222046-109e4600-9921-11ea-9380-82a6d6f229a2.png)<br />
**Слика 2**<br />
За сите тест примери обликот на таблата е ист како на примерот даден на Слика 1. За секој тест пример се менува големината N на таблата, како и распоредот на црни и бели полиња на неа, соодветно.
<br />
Во рамки на почетниот код даден за задачата се вчитуваат влезните аргументи за секој тест пример. Во променливата n ја имате големината на таблата (бројот на редици односно колони); во променливата polinja ја имате бојата на сите полиња на таблата (по редослед: одлево - надесно, редица по редица, ако таблата ја гледате како матрица), каде 1 означува дека полето е обоено во црна, а 0 означува дека полето е обоено во бела боја.
<br />
Изборот на полиња (потезите) потребно е да ги именувате на следниот начин:
<br />
x: redica, y: kolona<br />

каде redica и kolona се редицата и колоната на избраното (кликнатото) поле (ако таблата ја гледате како матрица).<br />

Вашиот код треба да има само еден повик на функција за приказ на стандарден излез (print) со кој ќе ја вратите секвенцата на потези која треба да се направи за да може сите полиња на таблата да бидат обоени во црна боја. Треба да примените неинформирано пребарување. Врз основа на тест примерите треба самите да определите кое пребарување ќе го користите.
