# makeNMC
Данный макрос для Excel позволяет производить расчёт начальной (максимальной) цены.

Инструкция:
1) Скачать файл PERCONAL.XLSB и сохранить по адресу: %Systemroot%/Пользователи/ Username /appdata/Roaming/Microsoft/Excel/XLSTART/
2) Необходимо открыть Excel и создать файл.
3) Далее необходимо включить вкладку "Разработчик" в excel по [инструкции:](https://clck.ru/UXm9j)
4) На вкладке "Разработчик" небходимо нажать на кнопку "Макросы" (слева вверху) или комбинацию клавиш Alt + F8.
5) Из открывшегося меню необходимо выбрать макрос "makeNMC" и запустить его.
6) В появившемся меню необходимо выбрать путь до папки, где размещены локальные сметы в формате xlsx. (ВАЖНО: в папке должны быть только сметы!)
7) Макрос формирует таблицу с разбивкой работ по справочникам: БЦ1-БЦ22, 26-05-45, в данной версии разбивка по справочникам ТЕР, ФЕР, ОЕР (а так же пуско-наладочные работы) не производится.
8) Если в сформированной таблице в столбце "Разница" сумма равно 0, то смета внесена в расчёт корректно.
