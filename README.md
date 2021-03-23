# Отчёт по lab01

## Report

1. _$ export LAB_NUMBER=01_

   Создание переменной LAB_NUMBER и присваение ей значения 01.
   
1. _$ git clone https://github.com/tp-labs/lab${LAB_NUMBER} tasks/lab${LAB_NUMBER}_

   Клонируем репозиторий по данной ссылке в tasks/lab01.
   
1. _$ mkdir reports/lab${LAB_NUMBER}_

   Создание директории reports/lab01.
   
1. _$ cp tasks/lab${LAB_NUMBER}/README.md reports/lab${LAB_NUMBER}/REPORT.md_

   Копирование файла README.md из tasks/lab01 в reports/lab01.
   
1. _$ cd reports/lab${LAB_NUMBER}_

   Смена рабочего каталога на Dan10022002/workspace/workspace/reports/lab01.
   
1. _$ edit REPORT.md_

   Открытие файла REPORT.md.

### Скриншоты работы

   ![work](https://github.com/Dan10022002/tp_lab01/blob/main/work.png)

   ![test](https://github.com/Dan10022002/tp_lab01/blob/main/test.png)

## Homework

1. Скачайте библиотеку boost с помощью утилиты wget. Адрес для скачивания https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz

   ![boost](https://github.com/Dan10022002/tp_lab01/blob/main/boost.png)
   
1. Разархивируйте скаченный файл в директорию ~/boost_1_69_0

   Команда _tar -xf boost_1_69_0.tar.gz_
   
1. Подсчитайте количество файлов в директории ~/boost_1_69_0 не включая вложенные директории.

   ![tree1](https://github.com/Dan10022002/tp_lab01/blob/main/tree1.png)
   
1. Подсчитайте количество файлов в директории ~/boost_1_69_0 включая вложенные директории.

   ![tree2](https://github.com/Dan10022002/tp_lab01/blob/main/tree2.png)
   
1. Подсчитайте количество заголовочных файлов, файлов с расширением .cpp.

   ![h](https://github.com/Dan10022002/tp_lab01/blob/main/h.png)
   
   ![cpp](https://github.com/Dan10022002/tp_lab01/blob/main/cpp.png)
   
1. Найдите полный пусть до файла any.hpp внутри библиотеки boost.

   ![any](https://github.com/Dan10022002/tp_lab01/blob/main/any.png)
   
1. Выведите в консоль все файлы, где упоминается последовательность boost::asio.

   Команда _grep -rnw -e "boost::asio_

   ![asio](https://github.com/Dan10022002/tp_lab01/blob/main/asio.png)

1. Скомпилирутйе boost.

   ![boost](https://github.com/Dan10022002/tp_lab01/blob/main/boost.png)
   
1. Перенесите все скомпилированные на предыдущем шаге статические библиотеки в директорию ~/boost-libs.

   Команда _cp -r ~/boost_1_69_0/tools/build/boost_output ~/boost-libs_
   
