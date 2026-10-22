import matplotlib.pyplot as plt
import numpy as np

# Данные по годам (с 1994 по 2024)
years = np.arange(1994, 2025)

# Смоделированные данные (количество постов в миллиардах)
posts = [
    0.01, 0.02, 0.04, 0.08, 0.15, 0.25, 0.4, 0.6, 0.9, 1.3, 
    2.0, 3.0, 4.5, 7.0, 10.0, 15.0, 25.0, 40.0, 65.0, 100.0, 
    150.0, 220.0, 320.0, 450.0, 620.0, 850.0, 1150.0, 1500.0, 1900.0, 2400.0, 3000.0
]

# Создание графика
plt.figure(figsize=(10, 6))

# Рисуем линию (цвет - синий, толщина - 3)
plt.plot(years, posts, color='#1DA1F2', linewidth=3)

# Заливка под линией
plt.fill_between(years, posts, color='#1DA1F2', alpha=0.2)

# Заголовки и подписи осей
plt.title('Рост количества публикаций в социальных сетях (1994–2024)', fontsize=14, fontweight='bold')
plt.xlabel('Год', fontsize=12)
plt.ylabel('Количество постов (в миллиардах)', fontsize=12)

# Сетка
plt.grid(True, linestyle='--', alpha=0.6)

# Текстовые пометки (эпохи)
plt.text(1996, 1000, 'Эпоха форумов', fontsize=10, color='gray')
plt.text(2010, 2000, 'Взрыв соцсетей', fontsize=10, color='gray')
plt.text(2019, 2800, 'Мобильный контент', fontsize=10, color='gray')

# Автоматическое выравнивание и показ
plt.tight_layout()
plt.show()