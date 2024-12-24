# module_13_2
Домашнее задание по теме "Хендлеры обработки сообщений".  Задача "Бот поддержки (Начало)
Цель: написать простейшего телеграм-бота, используя асинхронные функции.

Подготовка:
Выполните все действия представленные в предыдущих видео модуля, создав и подготовив Telegram-бот для дальнейших заданий.
Нужные версии для 13 и 14 модулей и вашего виртуального окружения находятся здесь. Если не помните, как установить необходимые библиотеки, обратитесь к материалам 11 модуля.
Актуальная версия Python для дальнейшей работы - 3.9.13.

Задача "Бот поддержки (Начало)":
К коду из подготовительного видео напишите две асинхронные функции:
start(message) - печатает строку в консоли 'Привет! Я бот помогающий твоему здоровью.' . Запускается только когда написана команда '/start' в чате с ботом. (используйте соответствующий декоратор)
all_massages(message) - печатает строку в консоли 'Введите команду /start, чтобы начать общение.'. Запускается при любом обращении не описанном ранее. (используйте соответствующий декоратор)
Запустите ваш Telegram-бот и проверьте его на работоспособность.
Пример результата выполнения программы:
Ввод в чат Telegram:
Хэй!
/start
Вывод в консоль:
Updates were skipped successfully.
Введите команду /start, чтобы начать общение.
Привет! Я бот помогающий твоему здоровью.
