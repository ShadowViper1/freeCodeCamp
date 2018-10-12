---
id: 5900f4d31000cf542c50ffe6
challengeType: 5
title: 'Problem 359: Hilbert"s New Hotel'
videoUrl: ''
localeTitle: 'Задача 359: Новый отель Гильберта'
---

## Description
<section id="description"> Бесконечное количество людей (пронумеровано 1, 2, 3 и т. Д.) Выстроились в очередь, чтобы получить номер в новейшей бесконечной гостинице Гильберта. Отель содержит бесконечное количество этажей (пронумеровано 1, 2, 3 и т. Д.), И каждый этаж содержит бесконечное количество комнат (число 1, 2, 3 и т. Д.). <p> Первоначально отель пуст. Гильберт объявляет правило о том, каким образом человеку присваивается номер: человек n получает первую свободную комнату на нижнем пронумерованном этаже, удовлетворяющую одно из следующих: пол пуст, пол не пуст, и если последний человек принимает комнату в этом этаже находится человек m, то m + n - идеальный квадрат </p><p> Человек 1 получает комнату 1 в этаже 1, так как пол 1 пуст. Человек 2 не получает комнату 2 в полу 1, так как 1 + 2 = 3 не является идеальным квадратом. Человек 2 вместо этого получает комнату 1 в полу 2, так как этаж 2 пуст. Человек 3 получает комнату 2 в 1 этаже, так как 1 + 3 = 4 - идеальный квадрат. </p><p> В конце концов, каждый человек в очереди получает номер в отеле. </p><p> Определите P (f, r) как n, если человек n занимает комнату r в поле f и 0, если человек не занимает комнату. Вот несколько примеров: P (1, 1) = 1 P (1, 2) = 3 P (2, 1) = 2 P (10, 20) = 440 P (25, 75) = 4863 P (99, 100) = 19454 </p><p> Найдите сумму всех P (f, r) для всех положительных f и r таких, что f × r = 71328803586048 и в качестве вашего ответа укажите последние 8 цифр. </p></section>

## Instructions
undefined

## Tests
<section id='tests'>

```yml
tests:
  - text: ''
    testString: 'assert.strictEqual(euler359(), 40632119, "<code>euler359()</code> should return 40632119.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler359() {
  // Good luck!
  return true;
}

euler359();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>