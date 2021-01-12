Будут проигнорированы:

1) Файлы в любом месте:
crash.log
override.tf
override.tf.json
.terraformrc
terraform.rc

2) Файлы в любом месте, путь которых оканчивается на:
.tfstate
.tfvars
_override.tf
_override.tf.json

3) Файлы в каталоге /.terraform/, который может быть расположен в 0 или более каталогах

4) Файлы, в пути которых содержится .tfstate.

