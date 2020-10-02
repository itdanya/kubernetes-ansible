# kubernetes-ansible

Разворачиваем kubernetes кластер 

hosts - инвентарь, ноды на которые будем ставить и адреса

initial.yml - просто для проверки живы ли хосты

dependencies.yml - установка необходимых зависимостей

master.yml - установка master ноды

workers.yml - установка и добавление worker'ов к master ноде
