# Решение домашнего задания к занятию «Запуск приложений в K8S»
https://github.com/netology-code/kuber-homeworks/blob/main/1.3/1.3.md

## Задание 1. Создать Deployment и обеспечить доступ к репликам приложения из другого Pod
### Манифест деплоймента
https://github.com/pkostua/kuber-1.3/blob/master/deployment1.yml
### Поды до и после масштабирования  
![image](https://github.com/user-attachments/assets/8e82107e-86d1-43a3-a93c-79c1092109eb)  
### Манифест сервиса
https://github.com/pkostua/kuber-1.3/blob/master/service1.yml
### Манифест пода
https://github.com/pkostua/kuber-1.3/blob/master/pod1.yml
### Доступ из пода до приложения  
![image](https://github.com/user-attachments/assets/9eaff05c-9fca-412a-b70d-6a85865dbe7c)

## Задание 2. Создать Deployment и обеспечить старт основного контейнера при выполнении условий
### Манифест деплоймента
https://github.com/pkostua/kuber-1.3/blob/master/deployment2.yml
### Манифест применлся, nginx не запускается
![image](https://github.com/user-attachments/assets/611a87c4-b8ae-4712-8336-3a1c8025fada)  
### Манифест сервиса
https://github.com/pkostua/kuber-1.3/blob/master/service2.yml
### После применениея манифеста сервиса, nginx запустился
![image](https://github.com/user-attachments/assets/bf33db11-34c6-494d-aeae-8a8be5db00bf)












