# Итоговая контольная работа по основному блоку.

## Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

### Алгоритм решения:
1. Делаем перебор значений из исходного массива
2. Проверяем каждое значение из массива на соответствие условию: `длина строки <= 3` 
3. Если строка удовлетворяет условию заносим значение в новый массив
4. Выполняем пункты `2` и `3` до тех пор, пока не достигнем конца исходного массива
5. Возвращаем новый заполненый массив как результат

### Блок-схема алгоритма:
 https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Diagramm.drawio#R7Vpbb6M6EP41eWwE5prHJmm2q%2BasVmp1dvO0coILZA3mGKdJ%2BuuPATtcTC7a5qqu1FI8HoP5Zvx5ZtyOMYhWXyhMgn%2BIh3AHaN6qYww7AOiGa%2FM%2FmWRdSJyeXgh8GnpCqRQ8h%2B9ICDUhXYQeSmuKjBDMwqQunJE4RjNWk0FKybKu9kpw%2Fa0J9JEieJ5BrEp%2FhB4LCqkLnFL%2BiEI%2FkG%2FW7V7RE0GpLL4kDaBHlhWR8dAxBpQQVtxFqwHCGXgSl2LcaEvvZmIUxeyQAeB3FL1MfjiDX0jrWy9fB97Av9MtMTm2ll%2BMPA6AaBLKAuKTGOKHUtqnZBF7KHusxlulzpiQhAt1LpwjxtbCmnDBCBcFLMKil8%2BYrn%2BK8XljkjW6lmwOV9XO4Vq01E8WKGRzrggEAF8QiRAfzxUowpCFb3WjQuEb%2FkZvM%2FQ7CfkrgCb82LCEEYUXG9I95SMYpD5iYlRphHtK4bqilmQK6fb3ALf%2BHtNp2HSPvpyX0Oc3xQxkq4JJKcr9pN1nRk9zPxmB0QC%2BzN8nj2gRuekdKF75BvFC4HkJH9rqCylZ0Bna4fPAOpPTuFbNOLp5mNP8gZ12fmfVUBzt3jC79rUOh9F15D2%2F9vPrg2pMjDnbZkZbBiFDzwnM4V1ywj%2FQJG%2BIMrTaibXEzKw7tFx3y5J7e0IUVGjX0rYbpwbrDgyfXpPX8Xg8nYz%2Be%2Fp3%2BPjt5%2FN4fGfejq%2B3zl9Mt%2FC0HXrGsZfEh1BXGSZlNIz9jtXvWMNsdJws%2BJqxMf%2Bm%2FpTyOz%2B7a2iRBWtVK1ZpyH9zk7T32zDK3DuepkluAW1e6PPrtiFavFExVBXFcXhAkGS33K4QY4SJT2HEFRNEQ44jos2%2B72XHvqX4Gq6QjKaOtTQB6G4htMrq1CXrVJene6rlad%2F48jQOXJ5H37E%2BhLqufxLYZZR3JbgbCuw5h0mqwgXLFOTYHaPY54uyaRcakGi6SM%2BymYOe02CMtv1cd87JGL0bd13rQNd1r8pz1UhU7s23vSdaoB6uArttR2wJWO1T%2BbejIP2NKCjzr2N1bCAO%2FZjfzzgWOZYZBuEM4nvREYWeV%2Fg%2BSsN3OM0flXm%2FSGn5c4uwiz%2BLu3tawsyDMvIbDQgmmfFiEqPcFhg3REcwh%2Bk2zWEp5jBbrGGcyhquyjZZjnUvMq3sWmRjVp6N2SoXnTH3soxGMaHNmbVzOrNu3hY5Hz9eaK8sNGlHlolOUFloz8%2F0v3ZpLcc1qhdmc2Wc2C7yO6sRYp4pW%2F2Qc%2FMmJmzGjHnKGis2PWus6Lh18nFU8gGSD84SKepqFWKC0k%2BzlxrN0rJx4b1UV0ObG2Ohg9NO%2B9h09THg1bxTRO9Wf15U2goGqXKNSiY14E9PKBvube6RFwvNdTUL%2BkyE0gzON8cjlyIUYFyCP8qzz67hbATZ%2Bafe1fYdgOatSsq7%2B1R0PyPZhzLSdZUTdLXuO%2B%2BAfv5zZbRjWaqXn5d2wEWSqKMf8e93ZvdAZz76WdcfHfXrjWzb7O0%2B6m%2Fqg7r%2Bh4%2F6d2JaLzlfxUIDWvM4yrx48U1GpJ%2Bz%2Bgaa9aPTbfC8Wf7jVOHs5b%2BfGQ%2F%2FAw%3D%3D  


### Программа:
Для запуска программы перейдите в папку `FinalWork` и запустите команду через терминал:
```
dotnet run 
```
Далее введите значения через пробел, например:
```
Введите значения через пробел: 2 hello sun 33 world
```
Пример вывода программы:
```
[2, hello, sun, 33, world] -> [2, sun, 33]
```