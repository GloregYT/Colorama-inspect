#Код

import colorama

from colorama import Fore, Back, Style

import inspect

print("Атрибути та методи colorama:")

print(inspect.getmembers(colorama, inspect.isfunction))

print(inspect.getmembers(colorama, inspect.isclass))

print("\nДоступні кольори (Fore):", dir(Fore))

print("Доступні фони (Back):", dir(Back))

print("Доступні стилі (Style):", dir(Style))

print(Fore.RED + 'Це текст червоного кольору')

print(Back.GREEN + 'Це текст з зеленим фоном')

print(Style.BRIGHT + 'Це яскравий текст')

print(Style.RESET_ALL + 'Скидання стилів')

colorama.init()


#Вивід

Доступні кольори (Fore): ['BLACK', 'BLUE', 'CYAN', 'GREEN', 'LIGHTBLACK_EX', 'LIGHTBLUE_EX', 'LIGHTCYAN_EX', 'LIGHTGREEN_EX', 'LIGHTMAGENTA_EX', 'LIGHTRED_EX', 'LIGHTWHITE_EX', 'LIGHTYELLOW_EX', 'MAGENTA', 'RED', 'RESET', 'WHITE', 'YELLOW', '__class__', '__delattr__', '__dict__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getstate__', '__gt__', '__hash__', '__init__', '__init_subclass__', '__le__', '__lt__', '__module__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__setattr__', '__sizeof__', '__str__', '__subclasshook__', '__weakref__']

Доступні фони (Back): ['BLACK', 'BLUE', 'CYAN', 'GREEN', 'LIGHTBLACK_EX', 'LIGHTBLUE_EX', 'LIGHTCYAN_EX', 'LIGHTGREEN_EX', 'LIGHTMAGENTA_EX', 'LIGHTRED_EX', 'LIGHTWHITE_EX', 'LIGHTYELLOW_EX', 'MAGENTA', 'RED', 'RESET', 'WHITE', 'YELLOW', '__class__', '__delattr__', '__dict__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getstate__', '__gt__', '__hash__', '__init__', '__init_subclass__', '__le__', '__lt__', '__module__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__setattr__', '__sizeof__', '__str__', '__subclasshook__', '__weakref__']

Доступні стилі (Style): ['BRIGHT', 'DIM', 'NORMAL', 'RESET_ALL', '__class__', '__delattr__', '__dict__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getstate__', '__gt__', '__hash__', '__init__', '__init_subclass__', '__le__', '__lt__', '__module__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__setattr__', '__sizeof__', '__str__', '__subclasshook__', '__weakref__']

Це текст червоного кольору / 
Це текст з зеленим фоном / 
Це яскравий текст / 
Скидання стилів
