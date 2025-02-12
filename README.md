# OSPanel | OpenServerPanel

https://ospanel.io/

https://github.com/OSPanel/OpenServerPanel

[Документация](https://github.com/OSPanel/OpenServerPanel/wiki)

Интерфейс командной строки:

# Основные команды

## Выключаем всё
```osp off all```

## Переходим в папку
```cd home```

## Создаём папку
```mkdir first-test.local```

## Переходим в папку
```cd first-test.local```

## Создаём папку
```mkdir .osp```

## Переходим в папку
```cd .osp```

## Создаём файл и вписываем значение
```echo ^[first-test.local^] > project.ini```

## Смотрим статус всех модулей
```osp status```

## Смотрим статус конкретного модуля
```osp status PHP-8.1```

## Включаем модуль
```osp on php-8.1```

## Проверяем
```osp status PHP-8.1```

## Перезапускаем программу
```osp exit & ospanel```

## Применить модуль
```osp use php-8.1```

## Сгенерирует SSL-сертификат
```osp cacert init```

## Выполнит подготовку системы
```osp sysprep```

## Сбросить и добавить
```osp reset & osp add bind```
