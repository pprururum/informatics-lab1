## Лабораторная работа 1



1. Создайте новый файл с именем `script.bash`

```bash
touch script.bash
```

2. Откройте созданный файл `script.bash` для редактирования. Стандартный текстовый редактор в Linux Ubuntu это `gedit`. Выполните в терминале

```bash
gedit script.bash
```
![image](https://github.com/user-attachments/assets/75d12da9-b3a4-4630-b59d-c3d34c358f7a)

3. Впишите следующий скрипт

```bash
#!/bin/bash

echo "Welcome to ITMO University"
```
![image](https://github.com/user-attachments/assets/c37adbab-428f-403a-9b5e-237004bcd668)

4. Сохраните файл. Закройте текстовый редактор `gedit`. Запустите bash-скрипт, выполнив в терминале

```bash
bash script.bash
```

5. Если вы все сделали верно, то в терминале должна отобразиться строка `Welcome to ITMO University`.
![image](https://github.com/user-attachments/assets/f69804d8-437c-411a-970a-5861d62ebd14)


А теперь, используя знания полученные из лекций, дополнительных источников и, добавив к этому немного смекалки, решите следующую задачу.

### Задача

Модифицируйте файл `script.bash` так, чтобы при его запуске в терминале в виде

```bash
bash script.bash Vasya Pupkin
```

Вывод был

`Welcome, Vasya Pupkin`

*Hint:* Скрипт должен работать для любых имен, даже если это Benedict Timothy Carlton Cumberbatch.


Решение
Для вывода любого запрашиваемого имени используем переменную `$@`, вписываем её в скрипт.
![image](https://github.com/user-attachments/assets/a6ab5d0e-f2c5-41c9-a384-6bf4a9e40fc3)
Проверяем нашу программу на различных вводных значениях
![image](https://github.com/user-attachments/assets/f7336081-992a-469a-92cb-cf7e7ae4f5af)

Посталенная задача достигнута!
