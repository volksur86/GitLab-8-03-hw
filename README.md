Задание 1
Что нужно сделать:

Разверните GitLab локально, используя Vagrantfile и инструкцию, описанные в этом репозитории.

Создайте новый проект и пустой репозиторий в нём.

Зарегистрируйте gitlab-runner для этого проекта и запустите его в режиме Docker. Раннер можно регистрировать и запускать на той же виртуальной машине, на которой запущен GitLab.

В качестве ответа в репозиторий шаблона с решением добавьте скриншоты с настройками раннера в проекте.

Решение 1:

1.1 Развернули GitLab локально на нашей виртуальной машине

<img width="1142" height="276" alt="image" src="https://github.com/user-attachments/assets/9f14c765-e395-4ef0-89ec-47c579f01434" />

<img width="1043" height="670" alt="image" src="https://github.com/user-attachments/assets/c73e25f8-c3eb-4fc9-a74c-0b7044ab9127" />

<img width="1834" height="1075" alt="image" src="https://github.com/user-attachments/assets/ee6da614-93c0-46b3-bc73-e54401c40896" />

1.2 Создаем новый проект и пустой репозиторий в нём

<img width="1632" height="1100" alt="image" src="https://github.com/user-attachments/assets/d7e291b1-f6bd-4c3b-8f45-7b2c244873bd" />

1.3 Регистрируем gitlab-runner для своего проекта и запустим его в режиме Docker

<img width="1247" height="431" alt="image" src="https://github.com/user-attachments/assets/ea45942e-77cd-4169-a584-a3f3c13bdb0c" />

<img width="1192" height="958" alt="image" src="https://github.com/user-attachments/assets/e749d204-715c-4a89-a078-d0c35898ce62" />

<img width="1599" height="1119" alt="image" src="https://github.com/user-attachments/assets/45fef65a-5dab-40e4-8559-9be233f335af" />

<img width="1267" height="1126" alt="image" src="https://github.com/user-attachments/assets/4ddbc449-f619-4c82-bcd3-8a59576d9ebf" />

<img width="1300" height="856" alt="image" src="https://github.com/user-attachments/assets/daff0e57-1c7f-49b5-85ef-af2835897de4" />

<img width="1230" height="1128" alt="image" src="https://github.com/user-attachments/assets/6cc5f3cb-3ffb-40fc-9ef7-3a5dc6ceaa8c" />

Задание 2
Что нужно сделать:

Запушьте репозиторий на GitLab, изменив origin. Это изучалось на занятии по Git.

Создайте .gitlab-ci.yml, описав в нём все необходимые, на ваш взгляд, этапы.

В качестве ответа в шаблон с решением добавьте:

файл gitlab-ci.yml для своего проекта или вставьте код в соответствующее поле в шаблоне;

скриншоты с успешно собранными сборками.

Решение 2:

Второе задание выполнял на ВМ в Yandex Cloud, т.к. при запуске машина развернутая на VirtualBox зависала.

<img width="1920" height="833" alt="image" src="https://github.com/user-attachments/assets/3bf31d39-2321-4897-a4ab-bec530c1a2e5" />

<img width="1540" height="1145" alt="image" src="https://github.com/user-attachments/assets/a36c627a-1bfd-495a-9bcf-5edc69c9426e" />

<img width="1540" height="1119" alt="image" src="https://github.com/user-attachments/assets/53a80e6c-f3e7-45c7-bd8f-45f5e81b160d" />

<img width="1863" height="1115" alt="image" src="https://github.com/user-attachments/assets/406fc6bc-8aed-4d02-b5f4-bd1c9fecf1ca" />


Дополнительные задания* (со звёздочкой)
Их выполнение необязательное и не влияет на получение зачёта по домашнему заданию. Можете их решить, если хотите лучше разобраться в материале.

Задание 3*
Измените CI так, чтобы:

этап сборки запускался сразу, не дожидаясь результатов тестов;
тесты запускались только при изменении файлов с расширением *.go.
В качестве ответа добавьте в шаблон с решением файл gitlab-ci.yml своего проекта или вставьте код в соответсвующее поле в шаблоне.
