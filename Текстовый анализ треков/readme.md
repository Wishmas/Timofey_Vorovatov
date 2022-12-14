# Текстовый анализ песен классических Metal-групп

---

Этот проект является логическим продолжением <a href="https://github.com/Wishmas/Timofey_Vorovatov/tree/main/Исследование%20Heavy%20Metal%20групп">другой моей работы</a>, посвященной исследованию мировой металической сцены как таковой. На этот раз я решил пойти дальше и изучить не просто группы, а тексты их песен. Наибольший интерес для меня представляло словоупотребление, то есть наиболее часто встречающиеся в песнях слова и различие в выборе таких слов между коллективами. Кроме этого, ставилась также цель провести более детальный лингвистический разбор текстов, в частности, выделить пропорцию употребления различных частей речи.

---

Для анализа я выбрал пять групп приблизительно одного жанра и одной эпохи: Judas Priest, Iron Maiden, Manowar, Mercyful Fate и Dio. Эти команды разделяют много общих черт, однако все же отличаются тематически и поют несколько о разном. Оттого еще интереснее было разобраться, насколько велики будут отличия. В качестве источника данных я выбрал известный сайт <a href="https://genius.com/">genius</a>, откуда, при помощи библиотек beautiful soup и requests, достал и собрал в текстовые файлы тексты большинства песен рассматриваемых групп. Подготовку и очистку данных я осуществил при помощи pandas, а часть работы, связанную с обработкой естественного языка, реализовал при помощи библиотеки NLTK. Для визуализации результатов были использованы matplotlib и seaborn. 

--- 

**Результаты** исследования оказались крайне показательными. Удалось установить, что...
- самые популярные существительные в треках представленных групп - это night, time, world, fire и way
- самые популярные глаголы - come, know, see, go, die
- самые популярные прилагательные - black, free, dead, last, evil
- у каждой группы свой уникальный набор наиболее употребляемых слов, однако есть множество пересечений
- распределение разных частей речи практически идентично у всех рассмотренных групп
- музыканты конца 20 века обожали слово 'oh'
- и многое другое

Все итоги исследования наглядно представлены в конце работы.

<div>
<img src="https://upload.wikimedia.org/wikipedia/commons/a/a4/DIO_%28band%29_logo.svg" title="dio" alt="dio" width="90" height="60"/>&nbsp;
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/60/Judas_priest_logo.png" title="jp" alt="jp" width="90" height="60"/>&nbsp;
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ea/ManowarLogo.svg/2560px-ManowarLogo.svg.png" title="mw" alt="mw" width="90" height="60"/>&nbsp;
    <img src="https://1000logos.net/wp-content/uploads/2017/02/logo-iron-maiden.png" title="im" alt="im" width="90" height="60"/>&nbsp;
    <img src="https://static.spacecrafted.com/ff1f5d4331b44f98b9df1c6548941a7b/i/ea6d69779dff4e74972467bea7883ef8/1/5feFb8zhrk/mercy-logo.png" title="mf" alt="mf" width="90" height="60"/>&nbsp;
</div>



