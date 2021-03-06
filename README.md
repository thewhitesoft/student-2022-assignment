## Задание
В одной крупной компании произошел сбой! Злоумышленники нашли уязвимость и испортили сообщения пользователей! К счастью, аналитики смогли обнаружить, какие изменения были произведены. Но неизвестно для каких сообщений! Ваша задача написать консольное приложение, которое восстановит исходные сообщения. Аналитики также смогли выяснить, что измененная однажды часть сообщения больше не модицифировалась!
## Входные данные
Имеются следующие файлы: <br/>
– `replacement.json.` Данные о произведенных перестановках. Содержит следующую структуру:
```JSON
[
        {
            “replacement”: string
            “source”: string
        }
        ...
]
```
– `data.json`. Сообщения пользователей. Содержит массив строк

**Правила замен**:
> –  *replacement.json* может содержать неуникальные объекты. *Неуникальными* называются объекты, содержащие одинаковые `replacement` и `source`

> – `replacement` может повторяться больше 1 раза. В этом случае нужно использовать последнее встречающееся значение `source`

> – `source` может быть `null`, в этом случае сообщения изначально не было и его нужно удалить из *data.json*
## Выходные данные
Необходимо сформировать новый файл *result.json*, который содержит исправленные сообщения. Должен содержать массив строк
## Дополнительное задание
Не является обязательным и будет являться плюсом. *data.json* должен быть получен с указанного [API](https://raw.githubusercontent.com/thewhitesoft/student-2022-assignment/main/data.json) с использованием HTTP GET запроса:

---
## Куда отсылать
Программу на любом языке программирования отсылать на [student@theWhite.ru](mailto:student@theWhite.ru). Решение должно содержать инструкцию для запуска<br/>
Размещение в Git ([Git](https://github.com/), [GitLab](https://about.gitlab.com/), [Bitbucket](https://bitbucket.org/dashboard/overview)) будет плюсом.
## Что еще
Расскажи о себе больше, заполнив [анкету](https://docs.google.com/forms/d/1WWUiYkiOqXI8pT6AaKYSA-fOvfYasU-0sghIHQ0rzL0/viewform?edit_requested=true)
