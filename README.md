# Hello, World!
> Это один маленький шаг для всего GitHub, но гигантский скачок для [yuramayer](https://github.com/yuramayer)

## Идея :thinking:
При разработке возникла потребность заявить о себе миру. Необходимо было найти грамотный с технической точки ответ, который решал бы возникшую проблему. Так возник концепт функции `hello_world`.

## Реализация :raised_hands:
В качестве языка программирования был выбран **Python** ввиду доступности и широкого сообщества. 

Черновые варианты включали в себя:
- **Вывод в функции**:
   ```python
   def printing_hello_world():
       print('Hello, World!')
   ```
- **Обращения по имени:**
   ```python
   def hello_names(names: list):
       print(f"Hello, {', '.join(names)}")
   ```
- **Вывод команд конкретным лицам:**
   ```python
   def order_someone(**orders):
       print('My orders!')
       for name, order in orders.items():
           print(f'{name}: {order}')
   ```

Эти варианты были отброшены в пользу **более логичного и элегантного решения**.
