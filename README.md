Cript
=====
Краткое описание классов
Класс String—класс из стандартной библиотеки языка С++,инкапсулирует понятие «строка» или «набор символов»,или «текст».
Класс Сryptologist (шифровальщик) —абстрактный базовый класс, инкапсулирующий понятие «шифровальщик»,не имеет собственных членов-данных, в нем реализованы чистые виртуальные функции,такие как получение готового текста и метода шифрования. Класс определяет интерфейс для всех производных классов.Полиморфизм заключается в вызовах виртуальных функций GetText и GetMetod.
Класс Сrypto_tabl—класс, производный от Cryptologist,моделирует понятие «шифрование табличным методом». Ключом шифрования является размер таблицы.
Как аргумент конструктора принимает объект класса String представляющий собою исходный текст.
Класс Сrypto_afin—класс, производный от Cryptologist,моделирует понятие «шифрование аффинным шифром Цезаря». Ключом шифрования является два числовых параметра. Они обозначены как X и Y и используются для определения параметра смещения для замены символов исходного алфавита символами того же алфавита, но выбранными с применением параметра смещения. 
Как аргумент конструктора принимает объект класса String представляющий собою исходный текст.
Класс Сrypto_Viginer—класс, производный от Cryptologist,моделирует понятие «шифрование по методу Вижинера». Ключом шифрования является слово.
Как аргумент конструктора принимает объект класса String представляющий собою исходный текст.
