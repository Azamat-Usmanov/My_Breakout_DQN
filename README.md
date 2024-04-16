## My_Breakout_DQN

# Отчет по проделанной работе

# Алгоритм

* DQN
* Эпсилон жадная стратегия

# Score и время ожидания обучения

* Смог добиться 338 очков за игру
* Обучал ~30 часов

# Что использовал

* PyTorch
  * Функция потерь Huber(Smooth L1 Loss Function)
  * Оптимизатор Адама
* gym
* numpy
* gym.wrappers

# Архитектура модели

* CNN(три слоя)
* Перцептрон(три слоя)
* Вход: чернобелая картинка, 4 канала(4 последних кадра игры)
* Выход: Q-функии для каждого действия
