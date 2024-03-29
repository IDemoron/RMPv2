# ChurchFinderKrsk
Приложение для поиска храмов различных религий в Красноярске.
## Инструкция по сборке
Скачав архив с приложением, необходимо его распаковать, открыть консоль и ввести следующие команды:
### Windows:
```
cd "Путь к распакованному проекту"
gradlew.bat assembleDebug
```
### MAC Os/Linux
```
$ cd "Путь к распакованному проекту"
./gradle assembleDebug
```
После успешного выполнения команды в директории "путь к
распакованному проекту"/app/build/outputs/apk/debug
будет находится собранный apk-файл готовый для установки на
устройство Android.
Далее нужно будет передать apk-файл любым способом на Androidустройство и установить.

Также, можно открыть проект в Android Studio и запустить его там, используя эмулятор.

На всякий случай, в корневой папке проекта уже лежит готовый apk-файл.

## Использование приложения:
На главном экране нам предложено выбрать одну из 4х религий, а также перейти в раздел "избранное", но раздел находится на стадии разработки, т.к ещё отсутствует локальная база данных.

![image](https://github.com/IDemoron/RMPv2/assets/115086039/c8257903-dff5-4e05-b1a6-e0815e04a9df)

После выбора нужной религии, нам предлагают ознакомится со списком храмов и выбрать один из них, кликнув по нему.

![image](https://github.com/IDemoron/RMPv2/assets/115086039/2fa4168f-fef1-4570-a2c3-ef7311f172f6)

После выбора храма, нам откроется вся нужная нам дополнительная информация, часы работы и местоположение на карте (в разработке)

![image](https://github.com/IDemoron/RMPv2/assets/115086039/9d8fedbb-fee1-422b-8e41-60399ed6f0a3)

В дальнейших версиях приложения будет реализовано: 
1. Возможность добавлять в избранное нужный нам храм.
2. Карта местоположения храма.
3. Жизненно важный виджет - прогноз погоды, ведь нам нужно знать, какой сегодня коннект с небом?
