# Findmate desktop app demo version

#Инструкции по установке

1) Скачать zip-архив (кнопка на правом сайдбаре) и распаковать

2) Установить Node.js
	 https://nodejs.org/   -> install

2.5) Установить mongodb
 	http://www.mongodb.org/downloads -> качаешь msi установщик, устанавливаешь

 	если что, инструкции
 	http://docs.mongodb.org/manual/tutorial/install-mongodb-on-windows/

 	идешь в корень диска C: делаешь папку data в ней папку db

 	идешь в папку где установлена монго, запускаешь mongod.exe
 	там должно появиться что-то вроде 
 	[initandlisten] waiting for connections on port 27017

3) Пуск -> Nodejs -> Nodejs command prompt

4) Чтобы разрешить копирование и вставку в коммандной строке:
	 в левом верхнем углу клик по значку (черный ярлык) -> свойства -> опции вставки -> поставь все галочки
	 копирование и вставка в коммандной строке делается правой кнопкой мыши

5) напиши npm install bower -g

6) перейди в папку, куда скачал архив

	 краткий гайд по навигации в коммандной строке

	 для перехода по разделам  -> D:

	 для перехода в корень диска -> cd /

	 для перехода в папку вперед, можно вводить полный адрес от того места, где ты находишься, без раздела -> cd downloads

	 для перехода на уровень назад -> cd ..

	 если в названии папки есть пробелы, адрес пиши в кавычках -> cd "My Documents"

	 список папок в текущей директории -> dir

	 создать папку -> mkdir названиепапки
	 

7) когда доползешь до архива, зайди в корень и напиши npm start

если ошибок нет, сайт будет доступен в браузере по адресу http://localhost:8080/


# CHANGELOG

v 0.2.0

* Авторизация Вконтакте

v 0.2.9

* Фикс серверных маршрутов. Теперь Create, Update, Read и Delete работают как нужно.
* Добавлена time-ago поддержка



