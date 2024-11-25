# Telegram-Helper_for_PC

Телеграм бот предназначен для получения удаленного доступа к ПК.

При запуске бота на Windows/Linux/Mac вы получаете доступ к консоле устройства:
- Можно просматривать данные
- Передвигаться между директориями 
- Скачивать и загружать данные 
- Смотреть информацию о компьютере, состояние сети, подключенных устройствах и т.п.
- Можно выполнять большенсвто команд вашей OS
---------------------
Большинство команд консоли можно вызвать так: \
$ <название команды> 
![](img/img.png)

Или так(получение вывода команды в файле txt): \
$f <название команды> 
![](img/img_1.png)

Для перемещения по директориям: \
cd ..
cd <название папки>
![](img/img_2.png)

Для загрузки файла с ПК: \
download <название файла >
![](img/img_3.png)

Для загрузки файла на ПК: \
![](img/img_4.png)
---------------------

Команды бота: 
help - справка с командами \
keyboard_linux -клавиатура linux \
keyboard_windows -клавиатура windows \
keyboard_stop - закрыть клавиатуру \
keyboard_windows_f -клавиатура windows с загрузкой файлов \
keyboard_linux_f - закрыть клавиатуру с загрузкой файлов \
bot_non_stop - выключение постоянной работы бота \

Для быстроты пользования в список кнопок изменить на свои команды

![](img/img_6.png)
![](img/img_7.png)

--------------------- 

На момент создания использовался Python 3.9.7 и библиотека pyTelegramBotAPI 4.4.0 \
При проблемах с установкой pyTelegramBotAPI: \
pip3 uninstall telebot \
pip3 uninstall PyTelegramBotAPI \
pip3 install pyTelegramBotAPI \
pip3 install --upgrade pyTelegramBotAPI \

---------------------
Для облегчения запуска программы можно использовать pyinstaller: \
Переходим в папку с HelperBotV1.py и выполняем команду \
pyinstaller -F -w HelperBotV1.py \
В папке dist появляется исполняемый файл, остальные файлы можно удалить

! При запуске exe файла на windows есть проблема кодировки, для испраления надо установить UTF-8 активным \
в настройках параметра языка \
![](img/img_5.png)

Также для windows есть команды, меняющие кодировку консоли \
Множество команд исполняются с разными кодировками \
Для просмотра кодировки: \
$ chcp \
Для изменения: \
$ chcp <номер кодировки> 

