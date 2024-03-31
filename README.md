#### Для запуска программы нужно установить зависимости
pip install -r requirements.txt

#### Тестирование работы задач
python -m unittest

#### Для проверки выполнения основной части тестового задания запустить main.py
python main.py

#### Описание:
1. Выполняем обход первых двух страниц
2. Из каждого тендера собираем ссылку на печатную форму
3. Получаем ссылку на xml-форму
4. Парсим поле publishDTInEIS
5. Выводим в консоль записи в виде “ссылка на печатную форму”-”дата публикации”
