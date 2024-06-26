[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/6zBS7few)
# Лабораторна робота №9
## Патерн декоратор (Decorator)

- Потрібно вивчити теоретичний матеріал та написати власноруч приклад коду для патерну decorator. Деяку теоретичну інформацію можна почерпнути тут https://refactoring.guru/uk/design-patterns/decorator
- Закомітити приклад НАПИСАНИЙ власноруч та зробити pull request.
- Згідно власного варіанту потрібно переписати існуючий проект та додати за потреби нові класи. Варіанти завдань отримати у викладача.
- В README файлі навести UML діаграму класів для коду згідно власного варіанту з короткими поясненнями.
- Закомітити код та зробити pull request.

## Варіант індивідуальних завдань для патерну "Декоратор"

13. **Декоратор для ноутбука з військовими властивостями**
    Створити декоратор, який модифікує звичайний ноутбук, додаючи до нього властивості, необхідні для військових, як-от збільшена стійкість до ударів.
    
## Короткий опис коду з поясненнями
- Component: Абстрактний клас, що визначає базовий інтерфейс для всіх компонентів. <br>
- ConcreteComponent: Конкретна реалізація компонента, яка представляє звичайний ноутбук. <br>
- Decorator: Абстрактний клас декоратора, який розширює базовий функціонал компонента. <br>
- MilitaryDecoratorA, MilitaryDecoratorB: Конкретні реалізації декораторів, які додають військові властивості до компонентів. <br>
- Client: Клас, який використовує компоненти і декоратори для створення та використання нових об'єктів. <br>
- Program.Main: Демонстраційний код, який створює звичайний ноутбук, додає до нього військові властивості за допомогою декораторів та виводить результати. 
