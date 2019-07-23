# vitaliy-pobokin_platform

# ДЗ №2
В рамках ДЗ №2 были выполнены следующие задачи:

Часть 1
--
1. Создан ServiceAccount bob в namespacе default
2. Создана связка данного аккаунта с кластерной ролью admin
3. Создан ServiceAccount dave в namespacе default без доступа к кластеру

Часть 2
--
1. Создан namespace prometheus
2. Создан ServiceAccount carol в namespacе prometheus
3. Создана ClusterRole pod-reader, позволяющая получать информацию о pod'ах в рамках кластера
4. Создана ClusterRoleBinding, предоставляющая роль pod-reader всем ServiceAccounts в namespace prometheus

Часть 3
--
1. Создан namespace dev
2. Создан ServiceAccount jane в namespacе dev
3. Создана RoleBinding, предоставляющая роль admin ServiceAccount'у jane в рамках namespace dev
4. Создан ServiceAccount ken в namespace dev
5. Создана RoleBinding, предоставляющая роль view ServiceAccount'у ken в рамках namespace dev

