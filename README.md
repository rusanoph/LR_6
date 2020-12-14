# LR6
Лабораторная работа №6

#Отчет о лабораторной работе №6

**Цель работы:**  изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

**Ход работы:**
Первым делом я создал аккаунт на сайте GitHub:
![Аккаунтт GitHub](https://sun9-62.userapi.com/impf/bw2K_hoX7LdRUXk4D1oc1UHeoqecCVqD1HXx6A/cIPutvufKkI.jpg?size=422x254&quality=96&proxy=1&sign=6aadbdcda2833bf117165afeb367e00b&type=album)
*Рис 1. Аккаунт GitHub*

Следующим шагом я сделал копию из [https://github.com/Kurtyanik/LR6/](https://github.com/Kurtyanik/LR6/):
![Сохранение репозитория](https://sun9-13.userapi.com/impf/48rbl2hodUbXFox-u8tCzfcHXQi2wc7ZHABEyA/R8Q2R_1PfCA.jpg?size=555x328&quality=96&proxy=1&sign=23c822f341903e62ff5459769c758082&type=album)
*Рис 2. Сохранение репозитория*

Далее устанавливаю Git и настраиваю клиент, вводя имя пользователя и email. Клонирую удалённый репозиторий на компьютер с помощью команды `$ git clone "github.com/Kurtyanik/LR6/"`:

![Клонирование репозитория](https://sun9-54.userapi.com/impf/S_GyHL_Hao0mUWiaQ2Y_I_mm9LkxLxz5TzZbfg/qysgB89xfPo.jpg?size=624x174&quality=96&proxy=1&sign=ae2bdc5f110415a8599de2c823c931ac&type=album)
*Рис 3. Клонирование репозитория*

После, через интерфейс GitHub, добавляю файл. Затем получаю историю каждой из веток и просматриваю последние изменения командой `$ git log`:
![История коммитов](https://sun9-5.userapi.com/impf/8RNmYEqudCM7T3brkOyN3gE-ZnLT2_SgaoiZ0Q/L9TkUedjYy4.jpg?size=624x259&quality=96&proxy=1&sign=25e427d26c2fe947ac042b525c811739&type=album)
*Рис 4. История коммитов*

Далее я создал новую ветку newBranch и создал файл file2.txt в репозитории, после чего сделал пару коммитов. Затем перешёл в master и выполнил слияние командой `$ git merge newBranch`:
![Слияние newBranch в master](https://sun9-41.userapi.com/impf/kJzKUVX4bHxDtTTpS55FL45bdJ3xKFptnIHgkA/EEqQ0J6PpKs.jpg?size=378x150&quality=96&proxy=1&sign=65631be4eb65d3b57167f4096a5204b7&type=album)
*Рис 5. Слияние newBranch в master*

Следующим я создал файл changes.txt и создал пару коммитов, чтобы затем сделать - -hard откат коммитов:
![Рис 6. «Хард» откат последних 2-х коммитов](https://sun9-67.userapi.com/impf/22bh5N-u_YRP85iO3AB1A2H5923d3u4fOrpSSA/s_puPbOqiJc.jpg?size=561x287&quality=96&proxy=1&sign=76a910eb1e28ba847ebb399f9f1cf893&type=album)
*Рис 6. «Хард» откат последних 2-х коммитов*