# lab-work2-TRiTPO
# Требования - Ежедневник
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
#1 Ведение
####&nbsp;&nbsp;&nbsp;Задачей данного проекта – разработать приложение «Ежедневник». Основное назначение продукта – создание списка дел с возможностью задания звукового оповещения в случае, если такая потребность необходима.
#2 Требования пользователя
##2.1 Программные интерфейсы
####&nbsp;&nbsp;&nbsp;&nbsp;Проект не будет использовать внешние ресурсы для своей работы. Для разработки будет использован язык Java. Приложение будет разрабатываться для Android.
##2.2 Интерфейс пользователя
####&nbsp;&nbsp;&nbsp;&nbsp;Данный продукт не требует никакой аутентификации. При запуске приложения пользователь попадает на главное окно. Пример окна представлен на рисунке 1.
![](https://github.com/TsikunovNik/lab-work2-TRiTPO/blob/master/%D0%93%D0%BB%D0%B0%D0%B2%D0%BD%D0%BE%D0%B5%20%D0%BE%D0%BA%D0%BD%D0%BE.png)
####&nbsp;&nbsp;&nbsp;&nbsp;Рисунок 1. Главное окно приложения
####&nbsp;&nbsp;&nbsp;&nbsp;При создании новой записи, на экране отображается новое окно приложения, где пользователь указывает название дела, её описание, время срабатывания и, при необходимости, задаёт звуковой сигнал при наступлении заданного времени. Пример окна представлен на рисунке 2.
![](https://github.com/TsikunovNik/lab-work2-TRiTPO/blob/master/%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE.png)
####&nbsp;&nbsp;&nbsp;&nbsp;Рисунок 2. Создание новой записи
####&nbsp;&nbsp;&nbsp;&nbsp;В случае, если пользователю требуется более гибкое задание времени срабатывания оповещения, то он может выбрать период действия уведомлений и настроить ежедневное время срабатывания уведомления. Данное окно представлено на рисунке 3.
![](https://github.com/TsikunovNik/lab-work2-TRiTPO/blob/master/%D0%9D%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0%20%D0%B4%D0%B0%D1%82%D1%8B.png)
####&nbsp;&nbsp;&nbsp;&nbsp;Рисунок 3. Настройка времени
##2.3 Характеристики пользователей 
####&nbsp;&nbsp;&nbsp;&nbsp;Данное приложение подойдет для использования любых групп пользователей, как по возрастной категории, так уровню занятости. Предполагается что, интерфейс приложения будет понятен и легко осваиваемый для любого пользователя.
##2.4 Предположения и зависимости
####&nbsp;&nbsp;&nbsp;&nbsp;Предполагается, что у приложения отсутствуют факторы, могущие повлиять на работоспособность приложения.
#3 Системные требования
####&nbsp;&nbsp;&nbsp;&nbsp;Приложение будет разработано с использованием языка Java в интегрирование среды разработки IntelliJIDEA, с использованием плагина для разработки приложений для Android.
##3.1 Функциональные требования
Функциональные требования вклучают следующие пункты:
+ Разработка интерфейса;
+ Разработка механизма взаимодействия приложения с внутренним временем смартфона;
+ Разработка базы данных, для хранения записей ежедневника;
+ Тестирование и устранение ошибок

##3.2 Нефункциональные требования
### 3.2.1 Атрибуты качества
####&nbsp;&nbsp;&nbsp;&nbsp;Надежность приложения – один из самых важных атрибутов приложения, при этом подразумевается, что приложение будет работать как без ошибок, так и функционально правильно, так как не срабатывание звукового сигнала-предупреждения может плохо сказаться на пользователе.
Легкость интерфейса, легкость освоения приложения не менее важно, так как пользователь не хочет разбираться со сложными настройками приложения, подразумевается, что пользователь на интуитивном уровне сможет освоить приложение.
Малая ресурсоемкость – приложение должно занимать мало места на смартфоне и затрачивать как можно меньше ресурсов на свою работу.
На рисунках 1 – 6 представлены диаграммы описываемого приложения.

#Диаграмма вариантов использования
![Диаграмма вариантов использования](https://github.com/TsikunovNik/lab-work2-TRiTPO/blob/master/use-case-1.png)

#Диаграмма активности
![Диаграмма активности](https://github.com/TsikunovNik/lab-work2-TRiTPO/blob/master/activity-2.png)

#Диаграмма состояний
![Диаграмма состояний](https://github.com/TsikunovNik/lab-work2-TRiTPO/blob/master/state-3.png)

#Диаграмма последовательности
![Диаграмма последовательности](https://github.com/TsikunovNik/lab-work2-TRiTPO/blob/master/Sequences-4.png)

#Диаграмма расположения
![Диаграмма расположения](https://github.com/TsikunovNik/lab-work2-TRiTPO/blob/master/%D0%A0%D0%B0%D1%81%D0%BF%D0%BE%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5-5.png)
