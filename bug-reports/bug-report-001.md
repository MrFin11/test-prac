## Bug report number 1!
Цветовая схема определена в глобальных стилях:

### Номер версии сайта:
14.88

### Критичность бага:
s3 (Значительный)
### Приоретет:
P2 Средний

### Установка и запуск

1. Клонируйте репозиторий и перейдите в папку проекта:
    git clone https://github.com/autobuscgt/openday.git
    cd openday

2. Установите зависимости:
   npm i

3. Запустите приложение в режиме разработки:
   npm start
   Приложение откроется по адресу http://localhost:3000

## Важные замечания для разработчиков

### Работа с ассетами
- **Шрифты:** закидывайте в `src/assets/fonts/` и подключайте через `@font-face` в CSS (Доступны MM - Montserrat medium, MB - Montserrat Bold).

### Контекст (Context)
Для глобального состояния квестов и путей используются `questContext.js` и `pathContext.js`.  
## Основные цвета (CSS переменные)

Цветовая схема определена в глобальных стилях:

### Цвета идут в четкой последовательности слева направо в соответствии с текстом сверху вниз.

<img width="1347" height="168" alt="Colors" src="https://github.com/user-attachments/assets/6d4bd49c-9f4b-463f-8bef-ca32c0d00e47" />

--white-blue: #76CAFF; <br/>
--white-grey: #E8E8E8; <br/>
--dark-grey: #363636; <br/>
--primary-color: #F9F9F9; <br/>
--white-purple: #6392F7; <br/>
--light-blue: #9DBBFA; <br/>
--green-color : #63C574; <br/>
--red-color: #EF3C3C; <br/>
--orange-color: #F48445; <br/>

## Как запустить проект

### Требования
- node.js 
- npm 

### Установка и запуск

1. Клонируйте репозиторий и перейдите в папку проекта:
    git clone https://github.com/autobuscgt/openday.git
    cd openday

2. Установите зависимости:
   npm i

3. Запустите приложение в режиме разработки:
   npm start
   Приложение откроется по адресу http://localhost:3000

## Важные замечания для разработчиков

### Работа с ассетами
- **Шрифты:** закидывайте в `src/assets/fonts/` и подключайте через `@font-face` в CSS (Доступны MM - Montserrat medium, MB - Montserrat Bold).

### Контекст (Context)
Для глобального состояния квестов и путей используются `questContext.js` и `pathContext.js`.  
