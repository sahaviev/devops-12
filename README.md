
# Rail Sakhaviev

## Описание terraform/.gitignore

Этот файл будет игнорировать: 
1. Рекурсивно все папки **.terraform** и их содержимое
2. Все файлы с расширением *.tfstate или которые содержат в своем имени подстроку **.tfstate**
3. Все файлы с названием **crash.log**
4. Все файлы с расширением ***.tfvars**
5. Все файлы с названием **override.tf** и **override.tf.json**
6. Все файлы название которых заканчивается на **_override.tf** и **_override.tf.json**
7. Все файлы с названием **.terraformrc** и **terraform.rc**




