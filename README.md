# dotNet-programmers
---
Построить три класса (базовый и 2 потомка), описывающих некоторых работников с почасовой оплатой (один из потомков) и фиксированной оплатой (второй потомок). Описать в базовом классе абстрактный метод для расчета среднемесячной заработной платы. Для «повременщиков» формула для расчета такова: «среднемесячная заработная плата = 20.8 * 8 * почасовую ставку», для работников с фиксированной оплатой «среднемесячная заработная плата = фиксированной месячной оплате».

    1. Упорядочить всю последовательность работников по убыванию среднемесячного заработка. При совпадении зарплаты – упорядочивать данные по алфавиту по имени. Вывести идентификатор работника, имя и среднемесячный заработок для всех элементов списка.
    2. Вывести первые 5 имен работников из полученного в пункте а) списка.
    3. Вывести последние 3 идентификатора работников из полученного в пункте а) списка.
    4. Организовать чтение коллекции в/из файла.
    5. Организовать обработку некорректного формата входного файла.
---
Пример файла:
```
<Employees>
	<Employee type="0">
		<id>1</id>
		<name>The .Net programmer</name>
		<salary>8</salary>
	</Employee>
	<Employee type="1">
		<id>2</id>
		<name>junior .Net programmer</name>
		<salary>30000</salary>
	</Employee>
	<Employee type="1">
		<id>3</id>
		<name>middle .Net programmer</name>
		<salary>50000</salary>
	</Employee>
	<Employee type="3">
		<id>4</id>
		<name>senior .Net programmer</name>
		<salary>500</salary>
	</Employee>
</Employees>
```
