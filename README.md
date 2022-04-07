# https://clck.ru/ebyQA


/* ПОДКЛЮЧАЕМ ШРИФТ */
@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@300;400;800&display=swap');

/* УСТАНАВЛИВАЕМ ОБЛАСТИ СТРАНИЦЫ НУЛЕВОЙ ОТСТУП И КРАСИМ ПО УМОЛЧАНИЮ ТЕКСТ В СЕРЫЙ ЦВЕТ */
body {
  margin: 0;
  color: #5c5b5b;
}

/* ДЛЯ ОБРАМЛЯЮЩЕГО БЛОКА УКАЗЩЫВАЕМ ПОДКЛЮЧЕННЫЙ ШРИФТ, ФЛЕКС ОТОБРАЖЕНИЕ, ШИРИНУ ДЕСКТОПНОЙ ВЕРСИИ И ВЫРАВНИВАНИЕ ПО СЕРЕДИНЕ */
.page {
  font-family: 'Roboto Slab', serif;
  display: flex;
  flex-direction: column;
  width: 1184px;
  margin: 0 auto;
}

/* БЛОКУ ЗАГОЛОВКА ДАЕМ 100 ПРОЦЕНТОВ ДОСТУПНОЙ ШИРИНЫ И ВЫРАВНИВАЕЙ ЭЛЕМЕНТЫ ВНУТРИ ПО ЦЕНТРУ */
header {
  width: 100%;
  text-align: center;
}
