Задача от изпит по Java
<strong>Система за управление на доставки</strong>
ЗАДАЧА (70 точки): Напишете сървърната част на система за управление на доставки. Системата е предназначена за барове. Тя трябва да позволява ефективно управление на наличности, подаване на заявка към дистрибутори и зареждане на бара след завършена доставка от дистрибутор. Сървърът трябва да поддържа работа с множество клиенти едновременно на порт 5678 и да предоставя следните функционалности:
Проверка на наличности (10 точки) – Клиентът подава числото 1 (за да достъпи тази функционалност). Системата връща списък с всички напитки, които се предлагат в бара, с тяхното ID, име, тип (алкохолни и безалкохолни, коктейли) и наличното количество. Ако дадена напитка не е налична да се изведе подходящ текст на мястото на наличността.
Подаване на заявка за зареждане (10 точки) – Клиентът подава числото 2 (за да достъпи тази функционалност), ID-то на напитката и желаното количество. Системата създава заявка към дистрибутора за зареждане на съответната напитка. Да се изведе подходящо съобщение, при успешна заявка.
Проверка на текущите заявки с техния статус (15 точки) – Клиентът подава числото 3 (за да достъпи тази функционалност). Системата извежда списък с всички подадени заявки за напитки, като показва следната информация за всяка заявка, номер на заявката, име на напитката, количеството и статус (Подадена, Обработва се, Обработена, Завършена). Статусът на всяка заявка се променя от друга интегрирана програма, а нашата система просто извлича текущите данни и ги подрежда.
Зареждане на бара (15 точки) – Клиентът подава числото 4 (за да достъпи тази функционалност). Системата взима всички напитки от наличните заявки, маркирани със статус „Обработена“, и добавя техните количества към наличността на бара. След като операцията завърши нейният статус трябва да бъде сменен на „Завършена“.
