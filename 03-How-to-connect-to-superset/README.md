# How to

## 初始化 Superset

- 将以下 container name 更新成实际运行 名字 例如: '03-how-to-connect-to-superset_superset_1'

`docker exec -it [name] superset-init`

## Odoo Connection String

- 注意服务器名字为 service name

`postgresql://odoo:odoo@pqdb:5432/odoo`
