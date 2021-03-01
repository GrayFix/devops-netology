# devops-netology

Файл создан для курса DevOps на Нетологии

В .gitignore прописаны исключения для файлов и каталогов:
1. Все содержимое каталога .terraform, каталог может лежать как в корне так и во вложенных каталогах
2. Будут проигноированы файлы в корне каталога crash.log, override.tf, override.tf.json, .terraformrc, terraform.rc
3. Будут проигноированы файлы в корне каталога про маске *.tfstate, *.tfstate.*, *.tfvars, *_override.tf, *_override.tf.json

Новая строка в ветке fix