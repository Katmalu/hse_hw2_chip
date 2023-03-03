# hse_hw2_chip

Colab: https://colab.research.google.com/drive/1uwg4p06-hGHsNHWo78lTTio19vq8u1Sj?usp=sharing


 Клеточная линия | Гистоновая метка | Реплика 1 | Реплика 2 | Контроль
 --- | --- | --- | --- | ---
 H1 | H3K27me3 |ENCFF539PKS | ENCFF374VEK | ENCFF634CSE
 
 
## FastQC без подрезания
 

 ![image](https://user-images.githubusercontent.com/103137801/222808546-8058ec10-e44f-4442-b8d1-9d9a73169b68.png)| ![image](https://user-images.githubusercontent.com/103137801/222809036-5ab2d017-baf5-427f-9597-002ca3c7f632.png) | ![image](https://user-images.githubusercontent.com/103137801/222809325-f21808b2-913d-4d3c-82eb-b84374cd7625.png) 
 ---|---|---
 ![image](https://user-images.githubusercontent.com/103137801/222808930-8d71a3da-ed2f-4fa0-aec9-effde7377461.png) | ![image](https://user-images.githubusercontent.com/103137801/222809088-cfb29fd9-d858-4176-8be3-47164c97db77.png) | ![image](https://user-images.githubusercontent.com/103137801/222809379-3fd615db-7f29-446d-93b9-cf6528e411ab.png)
 
  
## FastQC после подрезания

(с помощью trimmomatic)
 
 ![image](https://user-images.githubusercontent.com/103137801/222811094-77af563e-17cd-4867-9760-28a33d63db73.png) | ![image](https://user-images.githubusercontent.com/103137801/222810939-3b738907-5bc7-4ce5-bf23-3edbaacaa395.png) | ![image](https://user-images.githubusercontent.com/103137801/222810827-06bbc89c-7954-48c7-9092-ec2d15f9891d.png)
 --- | --- | ---
 ![image](https://user-images.githubusercontent.com/103137801/222811147-cb768eb1-d899-4205-a815-46724e125f80.png) | ![image](https://user-images.githubusercontent.com/103137801/222811021-3ebaa2a7-4d98-4768-937e-65b393ae2062.png) | ![image](https://user-images.githubusercontent.com/103137801/222810868-6924b69c-3d81-4208-a27a-94d2ccb89d95.png)
 
 ## Выравнивание
 
 ID | кол-во ридов | НЕ выравнилось | выравнилось уникально | выравнилось НЕ-уникально
 --- | --- | --- | --- | ---
 ENCFF539PKS | 977233 | 828140 | 33975 | 115118
 ENCFF374VEK | 9116820 | 7942832 | 259006 | 914982
 ENCFF634CSE | 13063420 | 11651084 | 367606 | 1044730
