Для установки - npm i -D typescript

Для проверки версии - npx tsc -v

Для инициализации файлика - npx tsc --init

Для компиляции использовать - npx tsc

Компиляция программы TypeScript выполняется вызовом компилятора tsc.

    tsc — без параметров заставляет компилятор искать ближайший вышележащий файл tsconfig.json, начиная с текущей директории.
    tsc –p <file-name> — когда запускается компилятор с указанием -p имя_файла, то компилятор использует именно этот файл. При этом рядом может находиться стандартный tsconfig.json-файл. Так вот, в этом случает стандартный файл полностью игнорируется.

Пакеты модульного тестирования 

    @types/chai — декларации типов для пакета оценки результатов модульного тестирования.
    @types/chai-spies — декларации типов для пакета «подстановки» тестовых реализаций функций.
    @types/jsdom — декларации типов для пакета имитации DOM во время тестирования на node.
    @types/jsdom-global — декларации типов для пакета имитации окна браузера во время тестирования.
    @types/mocha — декларации типов для пакета запуска модульного тестирования.
    @types/sinon — декларации типов для пакета подмены импортируемых функций.
    chai — пакет помогает в оценке результатов теста.
    chai-spies — пакет помогает заменять некоторые функции на время тестирования.
    jsdom — пакет помогает эмулировать поведение DOM при тестировании на стороне node.
    jsdom-global — пакет помогает эмулировать поведение DOM при тестировании на стороне node.
    mocha — платформа для запуска модульных тестов.
    sinon — пакет для эмуляции функций, методов и много чего ещё в целях тестирования.
    ts-node — пакет позволяет «проще» запускать TypeScript в среде node.