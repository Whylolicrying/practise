# README для проекта "Расчёт среднего значения выборки"

## Описание

Данный проект содержит программу на Python, которая позволяет пользователям вычислять среднее значение выборки, введённой вручную или сгенерированной случайным образом. Программа предоставляет пользователю возможность выбрать способ ввода данных и реализует обработку ошибок для удобства использования.

## Установка

Для запуска этого кода вам потребуется установить Python (рекомендуется версия 3.6 и выше). Убедитесь, что Python установлен и доступен в вашей среде.

## Использование

1. **Запустите программу:**
   Вы можете запустить программу, открыв терминал и выполнив следующую команду:
```bash
   python имя_файла.py
Выбор способа ввода данных:
При запуске программы вам будет предложено выбрать, хотите ли вы сгенерировать случайную выборку или ввести данные вручную:
Введите random, чтобы сгенерировать случайную выборку.
Введите manual, чтобы ввести числа вручную.
Генерация случайной выборки:
Если вы выбрали random, программа запросит:
Размер выборки (целое число).
Минимальное значение (целое число).
Максимальное значение (целое число).
Программа проверит, что минимальное значение меньше максимального, и создаст случайную выборку на основе введённых параметров.

Ввод данных вручную:
Если вы выбрали manual, программа попросит ввести числа, разделённые запятыми. Вводимые данные будут преобразованы в список чисел с плавающей точкой.
Расчёт среднего значения:
После получения данных программа вычислит и выведет среднее значение введённой выборки.
Примеры
Пример генерации случайной выборки:
   Хотите сгенерировать случайную выборку (введите 'random') или ввести данные вручную (введите 'manual')? random
   Введите размер выборки: 5
   Введите минимальное значение: 1
   Введите максимальное значение: 10
Пример ввода данных вручную:
   Хотите сгенерировать случайную выборку (введите 'random') или ввести данные вручную (введите 'manual')? manual
   Введите числа через запятую: 1, 2.5, 3.5, 4, 5
Обработанные ошибки
Программа включает в себя обработку ошибок для следующих случаев:

Если вводимый размер выборки является нецелым числом.
Если минимальное значение не меньше максимального.
Если пользователь ввёл неверное значение при выборе способа ввода данных.
Автор tg:https://t.me/sunset812 