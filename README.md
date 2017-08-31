# Function for v1.0
## 路由
* `/` 主页
* `/dashboard` 
    * `/user` 用户管理
    * `/product` 产品管理
    * `/post` 论坛管理
    * `/resource` 资源管理
* `/user` 
    * `/{id}` id用户的详细信息
* `/product` 产品展示
    * `/{id}` id产品的详细信息
* `/post` 帖子列表
    * `/{id}` id帖子的详细信息
* `/api` Ajax API
    * `/user` get,post
        * `/{id}` get, post, put, delete
    * `/product` get,post
        * `/{id}` get, post, put, delete
    * `/post` get,post
        * `/{id}` get, post, put, delete
    * `/resource` get,post
        * `/{id}` get, post, put, delete

## 功能
### 用户管理
|前端|后端|
|---|---|
||* [x] 用户表|
|* [ ] 登录|* [x] 登录|
|* [ ] 注册|* [ ] 注册|
|* [ ] 用户CRUD|* [ ] 用户CRUD|
|* [ ] 找回密码|* [ ] 找回密码|

### 物品管理
|前端|后端|
|---|---|
||* [x] 产品表|
|* [ ] 产品CRUD|* [ ] 产品CRUD|

### 论坛管理
|前端|后端|
|---|---|
||* [x] 帖子表|
|* [ ] 帖子CRUD|* [ ] 帖子CRUD|
|* [ ] 发帖|* [ ] 发帖|
|* [ ] 回帖|* [ ] 回帖|

### 资源管理
|前端|后端|
|---|---|
||* [x] 资源表|
|* [ ] 资源CRUD|* [ ] 资源CRUD|
|* [ ] 发资源|* [ ] 发资源|
