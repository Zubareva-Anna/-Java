# Отчёт о тестировании KeyValidator #
## Краткое описание ##
<14.03.2021>-<14.03.2021> было проведено тестирование приложения **KeyValidator**:
* функциональное тестирование, 
* дымовое тестирование, 
* тестирование граничных значений, 
* тестирование документации,
* тестирование совместимости

На тестирование затрачено: 30 минут

В результате тестирования выявлены следующие дефекты:

* [В руководстве использования ВООБЩЕ нет данных по установке и запуску приложения](https://github.com/Zubareva-Anna/-Java/issues/4)
* [Валидные ключи - не валидны](https://github.com/Zubareva-Anna/-Java/issues/1)
* [НЕ валидный ключ валидный](https://github.com/Zubareva-Anna/-Java/issues/3)

### **Артефакты тестирования** ###

1. [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
2. [Приложение KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class)
3. [Инструкция пользования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

В качестве тестовых данных использовались данные из [Инструкции пользования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

**Ключи для проверки**

*Валидные ключи:*

* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

*Невалидные ключи:*

* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

**Тестирование производилось в следующем окружении:**

* Windows 10, 64-разрядная
* Java 11 

