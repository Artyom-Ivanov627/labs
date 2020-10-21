## Отчет о лабораторных работах
## Cтудент группы ИДБ-17-06 Иванов А.Э.
# Лабораторная 1. 
![](https://github.com/Artyom-Ivanov627/labs/blob/main/lab1/model.png)

Строитель строит дом в соответствии с нормативной документацией с помощью бетона и строительного крана.

@startuml
class Строитель {
  {field} Строительный кран
  {method} Построить дом (бетон, нормативная документация), построенный дом
}
@enduml

![Рисунок](https://github.com/Artyom-Ivanov627/labs/blob/main/lab1/uml.png)

@startuml
:монтажник: <- :строитель:
:строитель: -right- (построить дом)
:строительный кран: -left- (построить дом)
:строительный кран: -> :строительное оборудование:
@enduml

![Рисунок](https://github.com/Artyom-Ivanov627/labs/blob/main/lab1/class.png)

# Лабораторная 2.
На диаграмме изображён процесс постройки дома.
![](https://github.com/Artyom-Ivanov627/lab2/blob/main/Диаграмма.png)
Подуровень IDF0 диаграммы:
![](https://github.com/Artyom-Ivanov627/lab2/blob/main/model%20(1).png)
А1 На этапе заливки фундамента используется бетон и щебенка. На выходе получаем готовый фундамент.

А2 На этапе постройки каркаса на вход дается арматура. На выходе получаем каркас дома.

А3 На этапе установки крыши на вход дается шифер. На выходе получаем крышу.

А4 На этапе покраски на вход дается краска. На выходе получается построенный дом.

DFD диаграмма:
![](https://github.com/Artyom-Ivanov627/lab2/blob/main/model%20(2).png)
Строитель обращается к списку работников, чтобы осуществить сбор крыши на земле и прикрепить крышу к крану. Далее на основании нормативной документации с помощью строительного крана проводится установка крыши.

Диаграмма прецедентов:
![](http://www.plantuml.com/plantuml/png/hP0z3e9048LxJZ6b5bnWOmnNCH5_4hH0x14R4xo55q0ZPaLtp_3DZLoeAMtdlVTzoII7Of4NnrqM6Rvud5Oql71OEYEpM8oUjD8IZmrPoqUl9XexIfnlrviYbWctFgR1uNdGqGYTbbhh1JiT6-EqvZsq-bbWPUdgNwYvZDRmj8BdZW_0Cy_UC9WihOcITByCV_a1)
