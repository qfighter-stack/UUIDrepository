# Генерация UUID4 на Python

Этот репозиторий содержит примеры генерации UUID4 на Python с использованием стандартной библиотеки `uuid`.

## Установка

Для использования примеров вам понадобится Python 3. Установите зависимости с помощью pip:

```bash
pip install -r requirements.txt
```
## Примеры
### Генерация одного UUID4
```python
import uuid

uuid4 = uuid.uuid4()
print(uuid4)
```
###  Генерация нескольких UUID4
```python 
import uuid

for _ in range(5):
    uuid4 = uuid.uuid4()
    print(uuid4)
```
## Лицензия

Этот проект лицензирован под Лицензией MIT.