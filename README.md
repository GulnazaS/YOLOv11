# Дообучение YOLOv11 для выполнения задачи детекции изображений дорожных знаков

## Краткий обзор на VOLOv11

YOLO11 это последняя итерация в Ultralytics YOLO серии детекторов объектов в реальном времени, заново определяющая возможные возможности благодаря передовой точности, скорости и эффективности. Основываясь на впечатляющих достижениях предыдущих версий YOLO, YOLO11 вносит значительные улучшения в архитектуру и методы обучения, что делает его универсальным выбором для широкого спектра задач компьютерного зрения.

![performance-comparison](https://github.com/user-attachments/assets/2fbe71d0-a3b9-4b1f-b00c-ba21aeed0133)


⋅⋅*Наиболее подробно можно ознакомиться с информацией на офоицильном источнике : https://docs.ultralytics.com/ru/models/yolo11/

## Датасет с дорожными знаками можно скачать, используя код ниже: 
```
!wget https://storage.yandexcloud.net/academy.ai/CV/traffic_signs_detection.zip
```

## Результаты дообучение
⋅⋅*Матрица ошибок

![confusion_matrix](https://github.com/user-attachments/assets/fd81052c-e1dc-4187-a985-f19b795b51eb)

⋅⋅*F1 - Confidense score
![Без названия](https://github.com/user-attachments/assets/97ce9b6b-b869-4020-9a1a-30a7119f2c2c)

⋅⋅*Precision - Recall score
![Без названия (1)](https://github.com/user-attachments/assets/c9a8e0a2-af54-429d-b6a8-a13a88c2275f)

⋅⋅*Precision - Confidense curve
![Без названия (2)](https://github.com/user-attachments/assets/5db023b0-444b-4234-bab0-c67ed0ca4c05)
