# Маслов Василий - "Lyceum_everywhere"
# Пользовательские сценарии

### Группа: 10 - И - 2


### [ Сценарий 1 - Создание собственного профиля ]

1. Пользователь вводит свое имя.
2. Пользователь вводит свою фамилию.
3. Пользователь пишет из какой он группы (к примеру, "10И2")
4. Пользователь добавляет свою фотографию.
5. Пользователь добавляет описание к своему профилю.
6. Когда пользователь завершает создание профиля, то он попадает в меню, где он может либо включить поиск (reply кнопка "Включить поиск"), любо изменить профиль (reply кнопка "Изменить профиль").


### [ Сценарий 2 - Изменение профиля ]

1. Пользователь нажимает на reply кнопку "Изменить профиль".
2. Пользователь может изменить свое имя.
3. Пользователь может изменить свою фамилию.
4. Пользователь может изменить группу.
5. Пользователь может изменить фотографию.
6. Пользователь может изменить свое описание.

### [ Сценарий 3 - Включение поиска ]

1. Пользователь нажимает кнопку "Найти лицеистов поблизости".
2. Пользователь выбирает радиус, на котором он хочет найти лицеистов.
3. Пользователь скидывает свое местоположение.
4. Пользователю присылается список профилей лицеистов, которые тоже находятся в поиске и в выбранном пользователем радиусе. Под каждым профилем есть две inline кнопки ("👍","👎"). В конце списка профилей будет сообщение "↓Здесь будут приходить сообщения от лицеистов↓". Также будет reply кнопка - "Выключить поиск".

### [ Сценарий 4 - Поиск по профилям  ]

1. Если пользователь нажмет на кнопку "👍", то сообщение с профилем лицеиста измениться (inline кнопки под сообщением исчезнут, появится строчка "Ваша оценка: 👍"), а лицеисту, под чьим профилем пользователь нажал "👍", придет сообщение с профилем пользователя и с такими же inline кнопками ("👍","👎").
2. Если пользователь нажмет "👎", то inline кнопки под сообщением с профилем лицеиста исчезнут.
3. Если пользователю под сообщением "↓Здесь будут приходить сообщения от лицеистов↓" придет сообщение с профилем лицеиста (то есть лицеист лайкнул пользователя), то пользователь может лайкнуть его в ответ (нажать "👍"), либо не лайкать (нажать "👎"). Если пользователь лайкнет его в ответ, то сообщение с профилем лицеиста изменится: в нем покажется телеграмм лицеиста, а inline кнопки исчезнут. Если пользователь нажмет "👎", то под сообщением лицеиста только исчезнут inline кнопки.
4. Если пользователь нажмет на кнопку "Выключить поиск", то поиск выключится, а пользователь вернется в меню.

### [ Сценарий 5 - Поиск по карте ]

1. Параллельно с поиском по профилям пользователь через web может открыть карту и увидеть на них других лицеистов в выбранном радиусе (если они есть).
2. Пользователь может нажать на любого лицеиста и увидеть его профиль, где будет только одна кнопка ("👍").
3. Если пользователь нажмет "👍", то так же, как и с поиском по профилям, лицеисту, в чьем профиле пользователь нажал "👍", под сообщением "↓Здесь будут приходить сообщения от лицеистов↓" придет сообщение с профилем пользователя с inline кнопками ("👍","👎").
4. Если лицеист лайкнул профиль пользователя через карту, то также, как и с поиском по профилям, пользователю под сообщением "↓Здесь будут приходить сообщения от лицеистов↓" придет сообщение с профилем лицеиста с inline кнопками ("👍","👎").
5. Выключение поиска происходит так же, как и с поиском по профилям, через reply кнопку "Выключить поиск".
