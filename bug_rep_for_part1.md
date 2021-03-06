# Отчёт о тестировании Money transfer #
## Краткое описание ##
23.09 - 23.09 было проведено Unit test приложения Money transfer.

На тестирование затрачено: 1 hour 30 min

В результате тестирования выявлены следующие дефекты:
>   * Вывод не соответствует фактическому результату. 
>   * [wrong output data](https://github.com/zerospirit79/Netology_java_homework_lesson1/issues/1#issue-1014276224)

1.  Описание процесса тестирования
>    В процессе тестирования использовались следующие артефакты*:

>> * переменная currentAccount
>> * переменная transfer
>> * переменная summary

   + 1.  Создан проект на Java.
   + 2.  Объявлены переменные, выше со значениями. 
   + 3. Написан код для определения конечного значения по заданию. 
```
int summary = currentAccount + transfer;
```
   + 4. Запущено приложение.
   + 5. В Терминале получен результат. 
   + 6. Фактический результат не соответствует ожидаемому. 


Примечание*: не указывайте артефакты "для галочки". Если вы сюда напишите тест-план, то мы попросим вас его показать (а если не покажете - то отправим работу на доработку). Пишите только то, что реально существует и требуется в задании.

2.  В качестве тестовых данных использовались данные [info](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md):

 * currentAccount = 2_000_000_000
 * transfer = 500_000_000
 * summary = 2500000000

3. Тестирование производилось в следующем окружении:

 * <версия и разрядность ОС> Windows 10
 * <версия Java> 11
 * <другое ПО, при необходимости>

