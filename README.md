# 2 ПГ, ДЗ 2
## Часть 1
Ответы на вопросы из ноутбука представлены в ноутбуке.  
Ссылка: https://colab.research.google.com/drive/1fXDFCG-8-gmxVozPuR8a0tPr5ajbSQnn?usp=sharing
### 1. FastQC отчеты
Подрезание чтений понадобилось только для ENCFF815VLD
**ENCFF644SSR:**  
![image](https://user-images.githubusercontent.com/55440084/155748402-ee20c407-8ef4-4004-a9c7-e0e8fbea6242.png)
![image](https://user-images.githubusercontent.com/55440084/155748433-278d2b07-ef58-45a3-8579-b82f35e3cb4b.png)
![image](https://user-images.githubusercontent.com/55440084/155748459-2c0a6d42-533c-499e-82a7-69bbeceb6391.png)

**ENCFF815VLD (trimmed):**  
![image](https://user-images.githubusercontent.com/55440084/155761166-973a21b3-e741-470e-85b3-cb6e92c37929.png)
![image](https://user-images.githubusercontent.com/55440084/155761184-0e249c1e-250a-431d-901c-00cc5b4497d9.png)
![image](https://user-images.githubusercontent.com/55440084/155761215-380dfa2d-6c3d-444b-9b2d-f66b76d568b4.png)
![image](https://user-images.githubusercontent.com/55440084/155761434-fe7ea13d-6b3e-4e12-b206-2e29482f0aab.png)

**ENCFF775RGK (контроль):**  
![image](https://user-images.githubusercontent.com/55440084/155748485-91f57b63-cb8d-4dff-919f-52538206cb4a.png)
![image](https://user-images.githubusercontent.com/55440084/155748510-007ad34f-ec5d-4b22-8ce6-a4030ea7bfce.png)
![image](https://user-images.githubusercontent.com/55440084/155748543-779e7108-fa73-49c8-986c-6af426972363.png)
![image](https://user-images.githubusercontent.com/55440084/155748576-efcaba12-5371-4755-9ad7-7ec238088e36.png)

### 2. Таблица со статистикой
|Образец                 |ENCFF815VLD|ENCFF644SSR|ENCFF775RGK (контроль)|
|:-----------------------|:---------:|:---------:|:--------------------:|
|Reads total             |37425763   |66685589   |10508255              |
|Unique reads aligned    |1660442    |3153615    |507252                |
|Non-unique reads aligned|3661959    |6981027    |1006116               |
|Not aligned             |32103362   |56550947   |8994887               |

### 3. Диаграмма Венна
![image](https://user-images.githubusercontent.com/55440084/156043299-612ceceb-1324-4343-9e27-054fbec510d7.png)
![image](https://user-images.githubusercontent.com/55440084/156043250-94b2d08d-b3a6-44fd-8cf6-79db57d4c62c.png)
![image](https://user-images.githubusercontent.com/55440084/156043349-b397d50f-9570-4d1f-86f5-8e46a1aaa925.png)
![image](https://user-images.githubusercontent.com/55440084/156043378-ca249347-7ab3-4f82-839e-561f96e67a63.png)

## Часть 2

Для проверки согласованности используемых данных с экспериментальными, мне удалось найти работу, посвященную, в том числе, гистону H3K9ac. Изображение из этой работы представлено ниже. В целом мы можем наблюдать соответсвие данных на графике и хитмапе с эксперементальнами. Так, мы можем видеть росто перед TSS и затем резко снижение после.

![image](https://user-images.githubusercontent.com/55440084/156918841-a153043d-fdac-43ce-9919-b9df8e4b8055.png)

![image](https://user-images.githubusercontent.com/55440084/156922472-5a84dc5b-ead8-4b24-b7a6-556e06b05d0d.png)
![image](https://user-images.githubusercontent.com/55440084/156922482-a44148d4-79b3-42d3-80ac-ec43f1e158b6.png)
