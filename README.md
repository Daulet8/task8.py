# task8.py
seconds = int(input("Введите количество секунд: "))

hours = seconds // 3600
minutes = (seconds % 3600) // 60
seconds_left = seconds % 60

print(hours, "ч", minutes, "мин", seconds_left, "сек")
