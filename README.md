# auto-avia-offer
Ранжирование предложений для пользователя
## Наш окончательный файл для сдачи catboost_0_83_submission_final.csv
Название модели: ranking_model_catb_2500_cw1.5_0.84.pkl это CatBoostClassifier
### Инструкция по развёртыванию
Нужно создать виртуальное окружение, далее пример для windows:
<br/>virtualenv — утилита для создания виртуальных окружений.
<br/>Для установки виртуального окружения:
<br/>`pip install virtualenv`
<br/>Для создания виртуального окружения:
<br/>`virtualenv <имя виртуального окружения>`
<br/>В текущем каталоге будет создана новая директория с указанным вами названием, куда будут перенесены python, pip и в дальнейшем установлены другие библиотеки.
<br/>Активация виртуального окружения:
<br/>`<имя виртуального окружения>\Scripts\activate`
<br/>Для деактивации виртуального окружения:
<br/>`deactivate`

Нужно установить все необходимые библиотеки командой: `pip install -r ranking_module\\requirements.txt`

Запустить модель в обвязке можно при помощи команды: `python ranking_module\\main.py`. Когда она попросить ввести название файла, есть тестовый файл для проверки, его можно написать вот так `ranking_module\\ExampleRequestAgent.xlsx`
