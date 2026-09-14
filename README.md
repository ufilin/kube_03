## kube_03
# Task 1

> Манифесты к заданию   

    [Deploy]:(https://github.com/ufilin/kube_03/blob/main/deploy_task1.yaml)  
    [Service]:(https://github.com/ufilin/kube_03/blob/main/serv_task1.yaml)  
    [Pod]:(https://github.com/ufilin/kube_03/blob/main/pod_task1.yaml)  

Pods до и после масштабирования

<p align="center">
  <img src="kube_03-1-1.png" width="800">
</p>

Проверка доступа из отдельного podа через curl наличие доступа к deploy приложениям

<p align="center">
  <img src="kube_03-1-2.png" width="800">
</p>

# Task 2

> Манифесты к заданию  

    [Deploy]:(https://github.com/ufilin/kube_03/blob/main/deploy_task2.yaml)  
    [Service]:(https://github.com/ufilin/kube_03/blob/main/serv_task2.yaml)  


Создание deploy приложения nginx, без сервиса не стартует

<p align="center">
  <img src="kube_03-2-1.png" width="800">
</p>

Запущен сервис, Pod переходит в состояние running

<p align="center">
  <img src="kube_03-2-2.png" width="800">
</p>