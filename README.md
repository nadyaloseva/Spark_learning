# Spark_learning

Установка и настройка: 
1.  С официального сайта: https://spark.incubator.apache.org/downloads.html устанавливаем Apache Spark, предварительно установив java и python.
2.  Устанавливаем "контролье суммы" для сравнения
3.  Создаем папку на рабочем столе и добавляем туда файлы: spark-3.5.1-bin-hadoop3.tgz и spark-3.5.1-bin-hadoop3.tgz.sha512
4.  В командной строке переходим в эту папку: cd c:/users/user/sha
5.  Запускаем команду certutil для вычисления SHA512-хэша: certutil -hashfile spark-3.5.1-bin-hadoop3.tgz SHA512
   ![image](https://github.com/nadyaloseva/Spark_learning/assets/65419241/73ad7a9c-ccf4-46d0-9cfb-d5a31231c449)
6. Сравниваем полученый хэш с файлом spark-3.5.1-bin-hadoop3.tgz.sha512
   ![image](https://github.com/nadyaloseva/Spark_learning/assets/65419241/fe82e5a5-1bea-45d0-bedf-437c87e69fcb)
7. Создать папку Spark на диске C, с помощью командной строки:
   cd \
   mkdir Spark
8. С https://github.com/cdarlint/winutils нужно скачать файл winutils.exe в предварительно созданную папку C:\hadoop\bin
   ![image](https://github.com/nadyaloseva/Spark_learning/assets/65419241/77acee34-c630-4d91-b8ef-6dc70567993c)
9. Нужно добавить переменные среды HADOOP_HOME, SPARK_HOME и JAVA_HOME(если не была создана ранее)
Я действовала по инструкции: https://phoenixnap.com/kb/install-spark-on-windows-10  
