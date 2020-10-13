[< к содержанию](./readme.md)

### git mv
Как и в случае с [удалением](./rm.md), переименовать файл в *git* репозитории можно двумя способами – с использованием и без использования средств операционной системы.

#### Первый способ
Переименуем файл *test_main_file.c* на *test_main.c*

```bash=
 mv test_main_file.c test_main.c
 ```
 Теперь отправим изменение в репозиторий.

```bash
> git add .
> git commit -m "Rename test_main_file.c"
```

#### Второй способ

В рамках второго способа рассмотрим работу с командой *git mv*. Переименуем файл *test_main.c* в *main.c*. Текущее содержимое репозитория и рабочего каталога.

```bash
> git mv test_main.c main.c
> git commit -m "Rename test_main.c file"
```