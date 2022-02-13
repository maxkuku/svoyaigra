Программа создана по просьбе о. Александра (Нарушева) для ежегодного конкурса среди учеников московских воскресных школ. Разработчик Максим Кукушкин (maxkuku@gmail.com, https://maxkuku.ru). Предлагаю использовать бесплатно для некоммерческих проектов. Окажу посильное содействие в организации.


Программа работает в онлайн доступе по логин/паролю <font color="#069875">admin/q12345Q</font> и в оффлайн-режиме.



Если в онлайне, то последний адрес приложения <font color="lightblue">http://svoyaigra.tk </font>
Для оффлайн-режима нужно скопировать (распаковать) все файлы архива svoyaigra.tk.zip в отдельную папку и запустить файл index.html




Перед запуском в любом режиме нужно сформировать и заменить в папке приложения 3 текстовых файла:
<ul><li>list1.txt (30 вопросов от 100 до 500 баллов),</li>
<li>list2.txt (30 вопросов от 100 до 500 баллов),</li>
<li>list3.txt (5 вопросов от 200 до 1000 баллов).</li></ul>

<font color="red">В каждом файле должны быть вопросы по одному в каждой строке, без переноса строки –  звездочка (*) – и в той же строке ответ.</font> 



Отступ слева в каждой строке не важен. Порядок вопросов должен соответствовать порядку ячеек: <font color="red">слева направо сверху вниз.</font> Для проверки вопросов можно вызвать в консоли переменную window.questions 



Для запуска в полноэкранном режиме в каждом окне из 3-х нужно нажимать кнопку F на клавиатуре. Чтобы выйти из режима fullscreen – кнопка Esc.


Из картинки логотипа убран год, так как не хотелось перерисовывать каждый год логотип. Год добавляется текущий Яваскриптом.


В оффлайн-режиме перед каждым раундом всплывает окно загрузки файла list...txt с номером раунда. Нужно указать файл для загрузки с вопросами и закрыть окно.


Кликом по ячейке открываем вопрос. Запускаеся таймер с "тиком" часов и сигналом по окончании минуты. За это время нужно прочесть вопрос и дать ответ. Ответ показывается кнопкой-буквой O латинской клавиатуры. Окно с ответом закрывается кнопкой Q или крестиком в окне. Нужно следить, <font color="lightgreen">чтобы случайно не закрыть окно с вопросом крестиком</font>, тогда ответ не увидим.


Для второго раунда обычно убирают одну из тем, нажимая соответствующую цифру на клавиатуре, но можно просто закрыть окно крестиком и использовать все темы. Но вопросов должно быть все-равно 30, так как мы заранее не знаем какую тему исключат из конкурса.


Переход в следующий раунд происходит по клику по стрелке вправо в нижнем правом углу экрана. <s>Внизу экрана идет счетчик общего количества вопросов и счетчик общего количества очков за заданные вопросы.</s> Счетчик можно сбросить, щелкнув букву С внизу экрана. Счетчик закомментирован и не работает. Кнопка С используется также для сброса отвеченных вопросов в раунде. Мало ли ошибка какая.

