# Lighthouse-role
## Переменные
--------------
| Переменные  |  Описание|
|:-----|:----|
| lighthouse_vcs | Путь до репозитория lighthouse |
| lighthouse_dir    | Каталог программы |
| lighthouse_port   | Порт |

## Пример Playbook
----------------

```yml
    - name: Install Lighthouse
      hosts: servers
      roles:
        - lighthouse-role
```

## Лицензия
----------------
MIT

## Автор
----------------
Иван Селезнев
