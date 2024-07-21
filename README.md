# CS2GSI
CS2 Web State Integration
![image](https://github.com/user-attachments/assets/4757546c-2652-48b5-aee0-934ecfe6f12d)
  # Server side plugin (C#)
    +отправка массива данных о игроках на NodeJS (int 200ms)
    +отправка массива данных о сервере на NodeJS (int 400ms)
    +отправка игровых событий (tact free) на NodeJS:
      События игроков:
      + [] Смерть игрока
      + [] Попадание пули в цель
      + [] Сообщение в чат
      События сервера
      + [] Начало раунда
      + [] Конец раунда
  # Backend server (NodeJS)
    + Кеширование данных
    + Прорисовка дополнительных кардров x7 (до 28fps)
    + Создание искуственной задержки (1000+ ms)
  # Front web viewer (React)
    + Рендер игроков
    + Рендер игровых событий
