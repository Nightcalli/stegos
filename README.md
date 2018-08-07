# stegos
модуль для python, скрывающий информацию стеганографическим способом

# Использование
**Подключение:**
from stegos import urlImg, readFile, hideMsg

**Описание функций:**<br><br>
**readFile('file_path')** считывает байты файла<br>
**urlImg('url_path')** скачивает картинку по указаному url в папку img (Создается автоматически если ее нету)<br>
**hideMsg('file_name','msg')** скрывает текст на уровне байтов <br>
**hideArh('file_name','arhive_name')** скрывает архивы в файлах
