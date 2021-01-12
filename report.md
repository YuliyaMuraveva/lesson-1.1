# Отчёт о тестировании KeyValidator

## Краткое описание

12/01/2021 - было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [При введении ключа 80b427f8-92cd-3aae-ba04-3927fbe17c6 валидатор выдает FAIL](https://github.com/YuliyaMuraveva/lesson-1.1/issues/1#issue-784059326)
* [При введении ключа 387eedc6-12e9-3b32-9881-63b6b5e85317 валидатор выдает FAIL](https://github.com/YuliyaMuraveva/lesson-1.1/issues/2#issue-784063053)
* [При введении ключа 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 валидатор выдает OK](https://github.com/YuliyaMuraveva/lesson-1.1/issues/3#issue-784064472)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* OpenJDK11
* KeyValidator


В качестве тестовых данных использовались данные [Руководства использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):
* Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
* Result for 80b427f8-92cd-3aae-ba04-3927fbe17c6: OK
* Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
* Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: OK
* Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK
* Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
* Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
* Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
* Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL

Тестирование производилось в следующем окружении:
* Fedora 32 x86_64
* OpenJDK version 11.0.9
