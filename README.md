# d2fastmode - beta 1.02

# Идея которую преследовал автор мода:
Повысить сложность сражения с ИИ, добавить больше рандомных факторов в бой, значительно уменьшить время игры одной карты, сделать процесс игры более динамичным.

# -----------Список изменений:--------------

# Скилы:

Все скилы кроме лидерства доступны со 2 уровня.

На 2 уровне ИИ всегда берет "неподкупность".

Лидерство героев увеличено до 4 со старта.

Жезловики получают 3 лидерства со старта.

У всех героев, жезловиков, воров очки хода увеличены вдвое.

При использовании GLabi.dbf (лежит в папке notForCampaing, предназначен только для сценариев, некоторые <компании, сценарии> с этим файлом не запускаются, всегда держите оригинальнал файла под рукой, если используете этот файл)
{
герой воин - знаменоносец, знание артефактов, знание талисманов, инструктор /
герой маг - знание сфер, талисманов, знание артефактов, свитки, посохи, книги/
герой лучник - знание артефактов, походное снаряжение, талисманы
}

# Общие характеристики:

надбавка рандомного урона сменена с 0-5 до 0-15

надбавка рандомной инициативы с 10 до 15

при уходе в защиту снижаеться урона на 30% в место 50%

получения опыта ИИ и нейтралов для уровней сложности были (0-2-4-6 стали 2-6-10-15) это во сколько раз комп получает больше опыта в зависимости от сложности.

Опыт для апа рассовых юнитов уменьшен вдвое.

# Економика:

Замок в день приносит 150з в место 100з ранее.

Цена постройки всех зданий снижена вдвое.

Цена покупки героев - 350з, жезловики - 200з, цена базовых юнитов снижена вдвое.

Цена постройки храма - 150з

оборотень - 400з (покупка) 

титан - 200з 

сатир - 200з 

грифон - 200з 

# Вещи:

урон сфер поднят на 15 очков для урона по всему отряду

сферы переодического урона поднят на 10 пунктов

сфера грома по одному юниту - 150 урона

талисманы - 7 использований в место 5

свитки вызова илюзий - убраны

Эликсиры защиты стали - зажигательными смесями (сферами) которые наносят урон 50/100/150 урона огнем по одной цели

рунный камень - дает навык острый взгляд

святая чаша - защиту от оружия

наручи с черепом - увеличивают хп на 20%

рог всеведенья - дает навык "первый удар"

гравированая диадема - стала "Диадемой Галеана" дает +50 хп

# Магия:

илюзии демонов - убраны

святая броня(империя) - увеличивает хп на 20 единиц

ледяной щит(гномы) - стал "рунным оружием" увеличивает точность на 10%

стойкость(гномы) - стала "Объятия Вотана" лечение 150 хп

зов предков(гномы) - порезано получение брони с 33% до 20%

быстрота(гномы) - стоимость 275рун 275смерти

Порезан урон для боевой магии 1ур = 10 урона, 2ур = 15 урона, 3ур = 30 урона, 4ур = 40 урона, 5ур = 50 урона.

Аое магия 3ур = 25 урона, 4ур = 35 урона. 5ур = 45 урона.

Призывные существа:

гончая - 15 урон

белиарх - 55

мститель - 45

оживший доспех - 55 урон

голем - 35

рух - 30 урон

валькирия - 35

каменный предок - 100

скелет - 30

хуорн - 55

кошмар - 30

танатос - 150 (доп урон ядом 150 очков убрано)

энт малый - 30

энт - 55

энт большой - 70

вердант - 45

# Юниты:

гварды замков - 500хп, 60 урон, 50 броня, 80% шанс разбить броню, имун к разбитию брони, разум, земля

Горгулья - 120хп, броня 35, защита от разбития брони

Мраморная горгулья - 170хп, броня 45, защита от разбития брони

Онисовая горгулья - 240хп, броня 50, защита от разбития брони

утер - 500хп (который используется в кампании демонов)

Повелитель стихий - больше не призывает джинов в место этого он дает защиту от оружия на 1 ход и лечит от ядов.

Некромант - воскрешает падших юнитов с половиной хп.

оборотень - 150хп , защита от оружия

тамплиер, лорд тьмы - атака могильный холод(вампирическая атака) 

смерть - 70 урон

сущий - 60 урон

Имунитеты к оружию у нежити заменены на защиту от оружия.

юниты которые носят меч - доп атака 25% шанс снизить повреждение (33% до 2 грейда начиная с 2 грейда 50%)

юниты которые носят дробящие оружия - доп атака 25% шанс разбить броню (20ед до 2 грейда начиная с 2 грейда 40ед)

юниты которые носят копье - доп атака 25% шанс снизить инициативу (33%)

юниты которые носят топор - доп атака 25% шанс доп урон (25ед до 2 грейда начиная с 2 грейда 50 ед)

Тень - шанс попасть 40%

Инкуб - шанс попасть 40%

Суккуб - шанс попасть 40%

Медуза - шанс попасть 40%

русалка - шанс паралича 40%

тварь - 25% шанс снизить инициативу на 33%

Священик - лечение порезано до 70 пунктов было 80
 
Патриарх - лечение порезано до 100 пунктов было 120

Прорицательница - лечение порезано до 60 пунктов было 70

ангел - тип атаки воздух
