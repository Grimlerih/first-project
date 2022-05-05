# Проект №1 Верстка сайта "Научиться учиться".
>Практическая работа первого спринта "Статическая верстка"
с применением БЭМ методологии, анимации, подключением шрифтов, при верстке применялся FlexBox.

Добрый день, к сожалению работа отклоняется от проверки по критериям из чеклиста:

- [x] Один или несколько блоков неверно отображаются в Firefox, Google Chrome или Yandex Browser; (в проекте не отображаются стили, изображения и т.д http://joxi.ru/zANKkENF1NlGWr)

- [x] reset.css необходимо удалить из проекта

Было бы хорошо испарвить перед первой итерацией:

- [x] Файловую структуру нужно полностью переработать: блоки не должны вкладываться в другие блоки, даже если они вложены в html. При составлении файловой структуры совсем забудьте про html код, важна только БЭМ-иерархия: что из этого блоки, а что - элементы и модификаторы. В папке "blocks" должны на одном уровне лежать папки с блоками. Внутри папки с блоком - стилевой файл блока и папки с элементами и модификаторами этого блока. Внутри папки элемента - стилевой файл элемента и папки с модификаторами этого элемента. Пожалуйста, изучите БЭМ-структуру здесь подробнее: https://ru.bem.info/methodology/filestructure/#nested

- [ ] У многих текстовых элементов нужно обнулить дефолтные браузерные отступы и назначить корректные если в них по брифу есть необходимость(для определения стандартных отступов используйте dev tools и инспектор кода)

- [x] Для хранения селекторов page необходимо создать фаловую структуру

- [x] @keyframes rotation файловой стрктуре блока rotation

- [x]Папку для Nested структуры необходимо назвать blocks

- [x]Для анимации необходимо использовать микс блока rotation

- [x]Необходимо удалить обращения к тегам напрямую, для наведения будет более корректно использовать микс

- [ ]В модификации элементов в коде есть неточности, например в блоке footer, обратите внимание: C точки зрения БЭМ-методологии модификатор не может использоваться в отрыве от модифицируемого блока или элемента. Модификатор должен изменять вид, поведение или состояние сущности, а не заменять ее. Используйте схему: имя-блока__имя-элемента имя-блока__имя-элемента_имя-модификатора_значение-модификатора Подробнее можно узнать в официальной документации БЭМ в разделе модификаторы: https://ru.bem.info/methodology/quick-start/#%D0%BC%D0%BE%D0%B4%D0%B8%D1%84%D0%B8%D0%BA%D0%B
