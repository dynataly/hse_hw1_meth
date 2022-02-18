https://colab.research.google.com/drive/1qJ-yYc2uCH0WUWvwHWIMTgvDMlldJfcM?usp=sharing


fastqc анализ для 8cell

Интересно, что GC content образует на гладкую кривую (как ожидалось), а имеет два ярко выраженных пика: на 22% и на 68%.



таблица:
I - число ридов, закартированных на участок 11347700-11367700

II - число ридов, закартированных на участок 40185800-40195800

III - процент дуплицированных чтений

![таблица](https://user-images.githubusercontent.com/72361668/154709521-46eb66df-18aa-4158-8c8f-88fa6dbbb054.png)


M-bias plot
Для epiblast:

![m-bias epi 1](https://user-images.githubusercontent.com/72361668/154709594-1f9c87df-36dd-4892-b125-0dc1ee905a57.png)
![m-bias epi 2](https://user-images.githubusercontent.com/72361668/154709599-324f3aad-0a7a-4bd8-a2ae-add1358f2339.png)


Гистограммы
распределения метилирования цитозинов по хромосоме

В 8-cell образце большой процент цитозинов не заметилирован, но около четверти заметилированы.

В образце ICM, как и ожидалось, наблюдается спад уровня метилирования почти до нуля; в образце Epiblast уровень метилирования возрастает, и при этом превосходит исходный уровень в 8-cell образце)

То есть действительно наблюдается ожидаемое изменение уровны метилирования: спад, а потом возрастание.

![гистограммы](https://user-images.githubusercontent.com/72361668/154709669-bccb5fa6-2183-4c6f-a173-6a1ed5361281.png)



Уровень метилирования и покрытия каждого образца

8-cell:

![im_8cell](https://user-images.githubusercontent.com/72361668/154709740-c3d3c14f-7fc8-4491-b30f-12e5e3aeb204.png)

ICM:

![im_icm](https://user-images.githubusercontent.com/72361668/154709753-4d23b5ce-d922-4fdf-8bb5-a944248d583f.png)

Epiblast:

![im_epi](https://user-images.githubusercontent.com/72361668/154709760-409fc981-a117-4af6-8818-930efe3ec81c.png)
