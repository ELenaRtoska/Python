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
<br />
## Информирано пребарување
### Подвижни препреки
Предложете соодветна репрезентација и напишете ги потребните функции во Python за да се реши следниот проблем за кој една можна почетна состојба е прикажана на слика 1:<br />
![Screenshot (158)](https://user-images.githubusercontent.com/48455819/82221115-d97b6500-991f-11ea-9068-014811b38539.png)<br />
**Слика 1** <br />
“Потребно е човечето безбедно да дојде до куќичката. Човечето може да се придвижува на кое било соседно поле хоризонтално или вертикално. Пречките 1, 2 и 3 се подвижни, при што пречката 1 се движи хоризонтално, пречката 2 се движи дијагонално, пречката 3 вертикално. Секоја од пречките се придвижува за едно поле во соодветниот правец и насока со секое придвижување на човечето. Притоа пречката 1 на почетокот се движи во лево, пречката 2 на почетокот се движи горе десно и пречката 3 на почетокот се движи надолу (пример за положбата на пречките после едно придвижување на човечето е прикажан на слика 2). Кога некоја пречка ќе дојде до крајот на таблата при што повеќе не може да се движи во насоката во која се движела, го менува движењето во спротивната насока. Доколку човечето и која било од пречките се најдат на исто поле - човечето ќе биде уништено.”<br />
![Screenshot (156)](https://user-images.githubusercontent.com/48455819/82220630-2c085180-991f-11ea-8207-83226e038e0c.png)<br />
**Слика 2** <br />
За сите тест примери изгледот и големината на таблата се исти како на примерот даден на сликите. За сите тест примери почетните положби, правец и насока на движење за препреките се исти. За секој тест пример почетната позиција на човечето се менува, а исто така се менува и позицијата на куќичката.<br />

Во рамки на почетниот код даден за задачата се вчитуваат влезните аргументи за секој тест пример. Во променливите CoveceRedica и CoveceKolona ги имате редицата и колоната во која на почетокот се наоѓа човечето (ако таблата ја гледате како матрица). Во променливите KukaRedica и KukaKolona ги имате редицата и колоната во која се наоѓа куќичката (ако таблата ја гледате како матрица).<br />

Движењата на човечето потребно е да ги именувате на следниот начин:<br />
Desno - за придвижување на човечето за едно поле надесно<br />
Levo - за придвижување на човечето за едно поле налево<br />
Gore - за придвижување на човечето за едно поле нагоре<br />
Dolu - за придвижување на човечето за едно поле надолу<br />
Вашиот код треба да има само еден повик на функција за приказ на стандарден излез (print) со кој ќе ја вратите секвенцата на движења која човечето треба да ја направи за да може од својата почетна позиција да стигне до позицијата на куќичката. Треба да примените информирано пребарување. Искористете Менхетен растојание за имплементација на евристичката функција.<br />

### Црно-бело
Предложете соодветна репрезентација и напишете ги потребните функции во Python за да се реши следниот проблем за кој една можна почетна состојба е прикажана на Слика 1:<br />
![Screenshot (160)](https://user-images.githubusercontent.com/48455819/82221846-cddc6e00-9920-11ea-90e1-0c0db0d2af05.png)
<br />
**Слика 1**<br />
"Tабла со димензии N x N се состои од бели и црни полиња. Со избор (кликнување) на едно поле се прави промена на бојата на тоа поле и на сите полиња кои што се наоѓаат во истата редица (лево или десно) и во истата колона (долу или горе), во спротивната боја, како што е прикажано на Слика 2. Целта е сите полиња на таблата да бидат обоени во црна боја. Потребно е проблемот да се реши во најмал број на потези т.е. со избирање (кликнување) на најмал можен број на полиња."<br />
![Screenshot (161)](https://user-images.githubusercontent.com/48455819/82222046-109e4600-9921-11ea-9380-82a6d6f229a2.png)<br />
**Слика 2**<br />
За сите тест примери обликот на таблата е ист како на примерот даден на Слика 1. За секој тест пример се менува големината N на таблата, како и распоредот на црни и бели полиња на неа, соодветно.<br />

Во рамки на почетниот код даден за задачата се вчитуваат влезните аргументи за секој тест пример. Во променливата n ја имате големината на таблата (бројот на редици односно колони); во променливата polinja ја имате бојата на сите полиња на таблата (по редослед: одлево - надесно, редица по редица, ако таблата ја гледате како матрица), каде 1 означува дека полето е обоено во црна, а 0 означува дека полето е обоено во бела боја.<br />

Изборот на полиња (потезите) потребно е да ги именувате на следниот начин:<br />
x: redica, y: kolona<br />
каде redica и kolona се редицата и колоната на избраното (кликнатото) поле (ако таблата ја гледате како матрица).<br />
Вашиот код треба да има само еден повик на функција за приказ на стандарден излез (print) со кој ќе ја вратите секвенцата на потези која треба да се направи за да може сите полиња на таблата да бидат обоени во црна боја. Треба да примените информирано пребарување. Врз основа на тест примерите треба самите да определите растојание за имплементација на евристичката функција.

## Пребарување низ конечен граф
### Граф
На сликата е даден просторот на состојби на некој проблем, претставен како граф.<br />
![Screenshot (163)](https://user-images.githubusercontent.com/48455819/82224078-b9e63b80-9923-11ea-9b07-e4539e252ab0.png)
<br />
Јазлите во просторот на состојби ги имаат следните локации:<br />

A (2,1) ; B (2,4) ; C (2,10)<br />

D (2,15) ; E (2,19) ; F (5,9)<br />

G (4,11) ; H (8,1) ; I (8,5)<br />

J (8,8) ; K (8,13) ; L (8,15)<br />

M (8,19)<br />

Во рамки на почетниот код имате почетна дефиниција за дадениот граф. Забележете дека должините на ребрата во графот се дадени како променливи. Вредностите кои ќе ги добијат овие променливи треба да ги определите самите. При определувањето на должината на ребрата да не се прави целобројно заокружување на резултатот.<br />

Треба да го решите проблемот на наоѓање на најкратката патека во графот (секвенца од јазли кои се посетуваат) од даден почетен до даден краен јазел, меѓутоа патеката задолжително мора да посети само една попатна станица од двете кои исто така ви се дадени.<br />

Појаснување: Постојат две можни најкратки патеки, едната поминува низ првата, а втората поминува низ втората попатна станица. Вие треба од двете да ја вратите пократката. Ако двете патеки се со иста должина да се врати патеката која поминува низ првата попатна станица (Stanica1).<br />

За секој тест пример се менуваат почетниот и крајниот јазел како и двете попатни станици. Во рамки на почетниот код даден за задачата се вчитуваат влезните аргументи за секој тест пример. Во променливите Pocetok и Kraj ги имате почетниот и крајниот јазел за најкратката патека која треба да ја најдете, а во променливите Stanica1 и Stanica2 ги имате двете можни попатни станици од кои мора да се посети точно една.<br />

Вашиот код треба да има само еден повик на функција за приказ на стандарден излез (print) со кој ќе ја вратите најкратката патека помеѓу почетниот и крајниот јазел со посетена само една попатна станица.<br />

### Патека во граф
На сликата е даден ненасочен граф со неговите јазли и нивните меѓусебни растојанија. <br />
![Screenshot (165)](https://user-images.githubusercontent.com/48455819/82224666-6b856c80-9924-11ea-87e9-095b114ea483.png)<br />
За јазлите во графот не се познати локациите. Во рамки на вашиот код, јазлите дефинирајте ги точно со имињата дадени на сликата.
<br />
Треба да го решите проблемот на наоѓање на должината на најкратката патека помеѓу два јазли од графот. Притоа важи следното: Во графот постои специјален јазел кој ако се измине (е дел од патеката) ја намалува вкупната должина на патеката за 9.
<br />
За секој тест пример се менуваат јазлите помеѓу кои треба да се најде најкратката патека и специјалниот јазел. Во рамки на почетниот код даден за задачата се вчитуваат влезните аргументи за секој тест пример. Во променливите Pocetok и Kraj ги имате почетниот и крајниот јазел за најкратката патека која треба да ја најдете, а во Stanica го имате специјалниот јазел.
<br />
Вашиот код треба да има само еден повик на функција за приказ на стандарден излез (print) со кој ќе ја вратите должината на најкратката патека помеѓу почетниот и крајниот јазел.<br />

## Дрва на одлука. Невронски мрежи 
### Дрва за одлучување
Дадено е податочно множество од риби кое ги содржи следните видови:
```
 Code Finnish  Swedish    English        Latin      

     1   Lahna    Braxen     Bream          Abramis brama
     2   Siika    Iiden      Whitewish      Leusiscus idus
     3   Saerki   Moerten    Roach          Leuciscus rutilus
     4   Parkki   Bjoerknan  ?              Abramis bjrkna
     5   Norssi   Norssen    Smelt          Osmerus eperlanus
     6   Hauki    Jaedda     Pike           Esox lucius
     7   Ahven    Abborre    Perch          Perca fluviatilis
```
Дадени се следните атрибути:
```
    0  Weight      Weight of the fish (in grams)
    1  Length1     Length from the nose to the beginning of the tail (in cm)
    2  Length2     Length from the nose to the notch of the tail (in cm)
    3  Length3     Length from the nose to the end of the tail (in cm)
    4  Height%     Maximal height as % of Length3
    5  Width%      Maximal width as % of Length3
```
Класата е дадена во последната колона.<br />
Да се направи модел за класификација за даденото податочно множество. За тренинг да се земат само првите 5 примероци од секоја од класите во множеството. Притоа ова да се направи во програмата, а не со рачно копирање! Да се класифицира елементот од податочното множество даден на влез и да се испечати предвидувањето. Елементот е даден со индексот од податочното множество.
