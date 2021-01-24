Отправка/получение сообщения, выполнение видеозвонка в мобильной версии программы Telegram на ОС IOS 14.3 <br/>
на мобильном устройстве должна быть установленна программа Telegram <br/>
мобильное устройство должно быть подключено к интернету <br/>
Name | Preconditions| Description | Result
:----|:-------------|:------------|:------
1 Создание сообщения новому контакту | открыть программу Telegram | - нажать на кнопку "Чаты" в нижнем углу<p> - нажать на кнопку в верхнем правом углу (квадрат с пером) <p> - в поле "Поиск" ввести контакт получателя <p> - выбрать контакт получателя <p> - в поле "Сообщение..." ввести текст <p> - нажать на кнопку отправки сообщения (стрелочка вверх в белом кругу) <p> - напротив Вашего сообщения появится значек 1 галочки| сообщение отправленно
2 Создание сообщения контакту из списка | открыть программу Telegram | - нажать на кнопку "Чаты" в нижнем углу <p> - из списка выбрать нужный контакт <p> - в поле "Сообщение..." ввести текст <p> - нажать на кнопку отправки сообщения (стрелочка вверх в белом кругу) <p> - напротив Вашего сообщения появится значек 1 галочки| сообщение отправленно
3 Создание сообщения с помощью голосового помошника | |- Вызвать голосового помошника <p> - сказать команду "Отправь сообщение в программе Telegram "имя контакта", "текст сообщения"" <p> - нажать на кнопку "Отправить"| сообщение отправленно
4 Удалить сообщение у отправителя| открыть программу Telegram | - открыть нужную переписку, где находится сообщение <p> - нажать и удерживать нужное сообщение <p> - в появившемся окне нажать на кнопку "Удалить" <p> - выбрать "Удалить у меня" | сообщение удалится только у отправителя
5 Удалить сообщение у отправителя и получателя| открыть программу Telegram | - открыть нужную переписку, где находится сообщение <p> - нажать и удерживать нужное сообщение <p> - в появившемся окне нажать на кнопку "Удалить" <p> - выбрать "Удалить у меня и у пользователя"| сообщение удалится у отправителя и получателя
6 Получение уведомления об сообщении | | - на мобильном устройстве появится уведомление от программы Telegram <p> - Нажать на уведомление <p> - откроется программа Telegram с перепиской от получателя|сообщение прочитано
7 Получение сообщения | открыть программу Telegram | - нажать на кнопку "Чаты" в нижнем углу <p> - выбрать контакт от которого пришло сообщение (в правой стороне будет цифра с числом непрочитанных сообщений в белом кругу)|сообщение прочитано
8 Создание видеозвонка | открыть программу Telegram| - нажать на кнопку "Чаты" в нижнем углу<p> - нажать на кнопку в верхнем правом углу (квадрат с пером) <p> - в поле "Поиск" ввести контакт получателя <p> - выбрать контакт получателя <p> - нажать на аватарку пользователя <p> - в появившемся окне нажать на кнопку видеозвонка (черная камера в белом кругу) | произведётся видеозвонок

Bug report
Name | Preconditions| Steps | Expected results | Actual results | Status 
:----|:-------------|:------|:-----------------|:---------------|:------
плохой интернет|-включить интернет Edge <p> - открыть программу Telegram| - нажать на кнопку "Чаты" в нижнем углу<p> - нажать на кнопку в верхнем правом углу (квадрат с пером) <p> - в поле "Поиск" ввести контакт получателя <p> - выбрать контакт получателя <p> - в поле "Сообщение..." ввести текст <p> - нажать на кнопку отправки сообщения (стрелочка вверх в белом кругу) | напротив Вашего сообщения появится значек 1 галочки | - напротив Вашего сообщения появляется значек часов <p> - программа Telegram переходит в режим "Ожидание сети" либо "Обновление" | сообщение не отправлено
отсутствие интернета|-выключить интернет <p> - открыть программу Telegram| - нажать на кнопку "Чаты" в нижнем углу<p> - нажать на кнопку в верхнем правом углу (квадрат с пером) <p> - в поле "Поиск" ввести контакт получателя <p> - выбрать контакт получателя <p> - в поле "Сообщение..." ввести текст <p> - нажать на кнопку отправки сообщения (стрелочка вверх в белом кругу) <p> - включить интернет через 30 минут | напротив Вашего сообщения появится значек 1 галочки | - напротив Вашего сообщения появляется значек восклицательного знака <p> - программа Telegram не отправляет сообщение при подключении к интернету | сообщение не отправлено
