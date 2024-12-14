vue前端人员后台管理

代码分为两部分

下载代码后需要修改前后端的实际电脑ip地址，以便后续能访问，
第一修改前端：\vue-project\vue-project\src\components\EmployeeDynamics.vue,六十行之后自己实际电脑IP。 第二修改后端：\vue-project\vue-project\my-backend\server.js，15行实际电脑IP地址

运行
第一步：后端在\vue-project\vue-project\my-backend下输入指令
yarn add express body-parser cors    下载库
yarn add ws
node server.js

第二步：前端在\vue-project\vue-project\src目录下输入
yarn dev

(前提成功配置了vue,node.js)

![屏幕截图 2024-12-14 111524](https://github.com/user-attachments/assets/f9b94dde-3d8b-4647-875a-ad3b155beb08)
![屏幕截图 2024-12-14 112404](https://github.com/user-attachments/assets/ee6e2941-ae58-4bd3-94eb-834b10f64521)
