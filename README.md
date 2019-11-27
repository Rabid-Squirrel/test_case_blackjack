# test_case_blackjack
Test task: test-case for game blackjack



<table style="border-collapse:
 collapse;table-layout:fixed;width:2979pt" width="3969" cellspacing="0" cellpadding="0" border="0">
 <colgroup><col style="mso-width-source:userset;mso-width-alt:4631;width:100pt" width="133">
 <col style="mso-width-source:userset;mso-width-alt:18222;width:392pt" width="522">
 <col style="mso-width-source:userset;mso-width-alt:28602;width:615pt" width="819">
 <col style="mso-width-source:userset;mso-width-alt:41216;
 width:886pt" width="1181">
 <col style="mso-width-source:userset;mso-width-alt:45870;
 width:986pt" width="1314">
 </colgroup><tbody><tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt;width:100pt" width="133" height="19">Номер
  тест-кейса</td>
  <td class="xl1524520" style="width:392pt" width="522">Название тест-кейса</td>
  <td class="xl1524520" style="width:615pt" width="819">Предварительные шаги
  (исходное состояние для теста)</td>
  <td class="xl1524520" style="width:886pt" width="1181">Шаги</td>
  <td class="xl1524520" style="width:986pt" width="1314">Ожидаемый положительный
  результат, либо условие положительного результата</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19" align="right">1</td>
  <td class="xl1524520">Готовность к игре по числу колод</td>
  <td class="xl1524520">Состояние перед игрой, до раздачи колод</td>
  <td class="xl1524520">Проверяем наличие колод с картами(пробуем вариатны где на
  столе 0, 4, 9 колод)</td>
  <td class="xl1524520">Либо использование шаффл-машинки, либо наличие от 1 до 8
  колод</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19" align="right">2</td>
  <td class="xl1524520">Готовность участником к игре</td>
  <td class="xl1524520">Состояние перед игрой, до раздачи колод</td>
  <td class="xl1524520">Проверяем наличие участников(0 дилеров и 0 игроков,1
  дилер и 0 игроков, 0 дилеров и 1 игрок,1 дилер и 1 игрок,2 дилера и 1
  игрока,1 дилер и 5 игроков)</td>
  <td class="xl1524520">Обязательно 1 дилер и хотя бы 1 игрок</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19" align="right">3</td>
  <td class="xl1524520">Соответствие карт в каждой колоде<span style="mso-spacerun:yes">&nbsp;</span></td>
  <td class="xl1524520">Состояние перед игрой, до раздачи колод</td>
  <td class="xl1524520">Проверяем каждую колоду на число карт и соответсвие карт
  колоде</td>
  <td class="xl1524520">Число карт в колоде - 52, отсутствие повторяющихся карт в
  колоде</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19" align="right">4</td>
  <td class="xl1524520">Проверка первоначальных ставок</td>
  <td class="xl1524520">Состояние<span style="mso-spacerun:yes">&nbsp; </span>игры:</td>
  <td class="xl1524520">Делаем ставки игроками (двумя игроками):</td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">до раздачи карт</td>
  <td class="xl1524520">4.1 ставки перед игрой</td>
  <td class="xl1524520">Фиксация ставки от игрока только до начала игры</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">в процессе игры, после раздачи карт</td>
  <td class="xl1524520">4.2 ставки во время игры</td>
  <td class="xl1524520">Ставки не принимаются</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19" align="right">5</td>
  <td class="xl1524520">Проверка значения очков для каждой карты</td>
  <td class="xl1524520">В процессе игры, сумма у игрока или дилера</td>
  <td class="xl1524520">Выдача карт игрокам и дилеру и подсчет новой
  суммы(проверяем на дилере и одном игроке):</td>
  <td class="xl1524520">Увеличение числа очков у игрока и дилера на
  соответствующее значение карты:<span style="mso-spacerun:yes">&nbsp;</span></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">исходная сумма 5</td>
  <td class="xl1524520">5.1 карты от двойки до десятки , новая сумма меньше 21</td>
  <td class="xl1524520">от 2 до 10 соответственно</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">исходная сумма 20</td>
  <td class="xl1524520">5.2 карты от двойки до десятки, новая<span style="mso-spacerun:yes">&nbsp; </span>сумма больше 21</td>
  <td class="xl1524520">от 2 до 10 соответственно</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">исходная сумма 7</td>
  <td class="xl1524520">5.3 карта туз принимая значение туза как 11, исходная
  сумма у пользователя меньше 11</td>
  <td class="xl1524520">увеличение суммы на 11, новая сумма меньше либо равна 21</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">исходная сумма 15</td>
  <td class="xl1524520">5.4 карта туз принимая значение туза как 1, исходная
  сумма у пользователя больше 10</td>
  <td class="xl1524520">увеличение суммы на 1</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">исходная сумма 9</td>
  <td class="xl1524520">5.5 карта "картинка", новая сумма меньше 21</td>
  <td class="xl1524520">увеличение суммы на 10</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">исходная сумма 19</td>
  <td class="xl1524520">5.6 карта "картинка", новая сумма больше 21</td>
  <td class="xl1524520">увеличение суммы на 10</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19" align="right">6</td>
  <td class="xl1524520">Проверка ситуации "пуш"</td>
  <td class="xl1524520">В процессе игры</td>
  <td class="xl1524520">Формируем у дилера и любого игрока одинаковое число очков
  (12 у дилера и 12 у игрока)</td>
  <td class="xl1524520">Все остаются при своих ставках, никто не выигрывает и не
  проигрывает, игра продолжается</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19" align="right">7</td>
  <td class="xl1524520">Проверка раздачи</td>
  <td class="xl1524520">Начало игры, раздача игрокам по две карты каждому игроку
  и дилеру одну открытую (может быть вторая , но закрытая)</td>
  <td class="xl1524520">Создаем следующие ситуации :</td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">у игрока 21, у дилера туз + 7<span style="mso-spacerun:yes">&nbsp;</span></td>
  <td class="xl1524520">7.1 у<span style="mso-spacerun:yes">&nbsp; </span>какого-то
  игрока 21 очко, у дилера карта не 10, не картинка или не туз</td>
  <td class="xl1524520">блек-джек у игрока, игроку выплачивается выигрыш 3 к 2
  (то есть в 1,5 раза превышающий его ставку),игра продолжается</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">у игрока 21, у дилера туз + 8<span style="mso-spacerun:yes">&nbsp;</span></td>
  <td class="xl1524520">7.2 у<span style="mso-spacerun:yes">&nbsp; </span>какого-то
  игрока 21 очко, у дилера<span style="mso-spacerun:yes">&nbsp; </span>карта туз,
  игрок берет выигрыш</td>
  <td class="xl1524520">игрок получает выигрыш 1:1, игра продолжается</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">у игрока 21, у дилера туз + 9</td>
  <td class="xl1524520">7.3 у<span style="mso-spacerun:yes">&nbsp; </span>какого-то
  игрока 21 очко, у дилера<span style="mso-spacerun:yes">&nbsp; </span>карта туз,
  игрок не берет выигрыш, раздаем карты игрокам,в конце игры у дилера не
  блек-джет</td>
  <td class="xl1524520">по завершени игры игрок получает выигрыш 3 к 2,игра
  продолжается</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">у игрока 21, у дилера туз + 10</td>
  <td class="xl1524520">7.4 у<span style="mso-spacerun:yes">&nbsp; </span>какого-то
  игрока 21 очко, у дилера<span style="mso-spacerun:yes">&nbsp; </span>карта(туз,
  игрок не берет выигрыш, в первых двух картах у дилера блек-джек</td>
  <td class="xl1524520">проигрыш всех игроков у кого не блек-джек, не страховка и
  не забранный выигрыш</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">у игрока 21, у дилера 10 + туз</td>
  <td class="xl1524520">7.5 у<span style="mso-spacerun:yes">&nbsp; </span>какого-то
  игрока 21 очко, у дилера<span style="mso-spacerun:yes">&nbsp; </span>карта(туз,
  игрок не берет выигрыш, в первых двух картах у дилера блек-джек</td>
  <td class="xl1524520">проигрыш всех игроков у кого не блек-джек, не страховка и
  не забранный выигрыш</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19" align="right">8</td>
  <td class="xl1524520">блек-джек по двум картам у дилера</td>
  <td class="xl1524520">В процессе игры</td>
  <td class="xl1524520">выдача второй карты дилеру для того чтобы сумма очков
  стала 21 :</td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">у игроков меньше 21</td>
  <td class="xl1524520">8.1 первая карта 10, вторая туз<span style="mso-spacerun:yes">&nbsp;</span></td>
  <td class="xl1524520">проигрыш всех игроков у кого не блек-джек, игроки с
  блек-джеком остаются при своих ставках, если они ранее не выбрали взять
  выигрыш 1 к 1 или если не застраховали свою комбинацию от блек-джека</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">у игроков меньше 21</td>
  <td class="xl1524520">8.2 первая туз, вторая 10</td>
  <td class="xl1524520">проигрыш всех игроков у кого не блек-джек, игроки с
  блек-джеком остаются при своих ставках, если они ранее не выбрали взять
  выигрыш 1 к 1 или если не застраховали свою комбинацию от блек-джека</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19" align="right">9</td>
  <td class="xl1524520">проверка "перебора" очков</td>
  <td class="xl1524520">В процессе игры, у игрока количество очков меньше 21</td>
  <td class="xl1524520">игроку выдается карта соответствующая номиналу большему
  чем ему необходимо до суммы в 21 очко</td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520">исходная сумма у игрока 17</td>
  <td class="xl1524520">выдаем курту 8</td>
  <td class="xl1524520">ситуация "перебор", снятие ставки игрока в
  пользу казино</td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
 </tr>
 <tr style="height:14.5pt" height="19">
  <td class="xl1524520" style="height:14.5pt" height="19"></td>
  <td class="xl1524520" colspan="2">Не описаны тест-кейсы для: разбиения пар,
  удвоения ставок, утроения ставок, отказ от игры, страхование, отказ от карты
  и различных вариаций блек-джека(европейский, американский)</td>
  <td class="xl1524520"></td>
  <td class="xl1524520"></td>
 </tr>
 <!--[if supportMisalignedColumns]-->
 <tr style="display:none" height="0">
  <td style="width:100pt" width="133"></td>
  <td style="width:392pt" width="522"></td>
  <td style="width:615pt" width="819"></td>
  <td style="width:886pt" width="1181"></td>
  <td style="width:986pt" width="1314"></td>
 </tr>
 <!--[endif]-->
</tbody></table>

