#!/bin/bash

# Выводим приветственное сообщение
echo "Hello Student!"

# Запрашиваем имя пользователя
read -p "Введите Ваше имя: " name

# Выводим приветствие с именем пользователя
echo "Welcome to terminal $name"

# Создаем папку test в каталоге tmp
mkdir -p /tmp/test

# Создаем файл mydate.txt в папке /tmp
touch /tmp/mydate.txt

# Записываем текущее время в файл mydate.txt
date +%T > /tmp/mydate.txt

# Выводим на экран сообщение "Сохраняем данные"
echo "Сохраняем данные"
