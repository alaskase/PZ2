     Идентификация и аутентификация
# 1) Установка ОС Debian 12 в виртуальной среде:
![Процесс установки Debian 12](/images/01.jpg)
![01](https://github.com/alaskase/PZ2/assets/145039541/ddcd2fe8-ca82-411a-8fc0-2f44ac02a571)
# 2) Создать пользователя super – {ФИО}, наделить его привилегиями суперпользователя.
![Вход под суперпользователем (root)](/images/02.jpg)
![02](https://github.com/alaskase/PZ2/assets/145039541/1f0a3e7a-64b6-475c-93bf-0ab52a9284e6)
![Создадим пользователя super](/images/03.jpg)
![03](https://github.com/alaskase/PZ2/assets/145039541/2badd16e-4d0f-4b9c-9601-2281d57d578f)
![Наделим его привилегиями](/images/04.jpg)
![04](https://github.com/alaskase/PZ2/assets/145039541/660638d0-594a-45d9-af9f-a61499f8e2a3)
![Отредактируем /etc/sudoers](/images/05.jpg)
![05](https://github.com/alaskase/PZ2/assets/145039541/85f6b851-f861-46f6-97dc-d4603cf78e0c)
![Включим в группу sudo](/images/06.jpg)
![06](https://github.com/alaskase/PZ2/assets/145039541/bc1fce39-28d6-465a-8617-29e54b4ccf6e)
![Проверим /etc/sudoers](/images/07.jpg)
![07](https://github.com/alaskase/PZ2/assets/145039541/9a4d2809-28c9-420f-84d3-6b0e030b6350)
![Проверим доступность прав администратора у пользователя super](/images/08.jpg)
![08](https://github.com/alaskase/PZ2/assets/145039541/04a3f61b-7aad-4fe8-8d78-15249ea8b5da)

# 3) Зайти под созданным пользователем и создать группу.
![Выполним вход пользователем super](/images/09.jpg)
![09](https://github.com/alaskase/PZ2/assets/145039541/abec5a6a-fe70-4cc3-b763-11a51e4da665)
![Создадим группу](/images/10.jpg)
![10](https://github.com/alaskase/PZ2/assets/145039541/663de2e7-8c88-4bbb-a36c-ee4aef4e7791)
# 4) Добавить пользователя super в группу:
![Добавим пользователя super в группу](/images/11.jpg)
![11](https://github.com/alaskase/PZ2/assets/145039541/4437716e-1c11-420f-9e8a-7e265d5491cb)

# 5) Продемонстрировать наличие пользователя в группе:

![Пользователь super принадлежит созданной группе](/images/12.jpg)
![12](https://github.com/alaskase/PZ2/assets/145039541/3238f68b-327b-47f7-b81b-2cb70d0bf1db)

# 6) Создать пользователя user, добавить его в группу:
![Создадим пользователя user](/images/13.jpg)
![13](https://github.com/alaskase/PZ2/assets/145039541/6cca55ad-f6e2-4921-8ee6-83b1d1bbb448)

![Добавим пользователя в группу](/images/14.jpg)
![14](https://github.com/alaskase/PZ2/assets/145039541/f9a943e0-7b34-4d86-8e03-2ec9c7f797f3)


# 7) Наделить полномочиями (с использование механизма дискретного управления доступом chmod) пользователя user правом создания и удаления файлов в домашнем каталоге пользователя super:

![Используя chmod разрешим пользователю создавать и удалять файлы](/images/15.jpg)
![15](https://github.com/alaskase/PZ2/assets/145039541/3cac6b8c-8ccf-4432-ac3b-521991ed5049)

# 8) Продемонстрировать работу механизмов разграничения доступа:

![Демонстрация создания и удаления файлов в домашнем каталоге пользоватля super](/images/16.jpg)
![16](https://github.com/alaskase/PZ2/assets/145039541/0b16a65e-110e-45f8-95c4-27a41e432108)

