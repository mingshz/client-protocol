### 客户端API

#### #使用
- 下载并安装 [node.js](https://nodejs.org/en/)
- 更换npm源，终端（CMD）中输入 `npm config set registry https://registry.npm.taobao.org`
- 依次在**git bash**里面执行以下命令
```
git clone https://github.com/mingshz/common-solution-frontend.git
cd common-solution-frontend
git checkout 1.14.0
cd api-mocker
npm install
npm run build
cd ../local-api-mocker
npm install
cd ../webpack-local-api-mocker
npm install
cd ../../
git clone https://github.com/mingshz/swagger-editor.git
npm run dev
```
- 项目运行成功，在浏览器输入 http://localhost:3200
- 将`swagger.yaml`文件中的内容到**Swagger 文档在线编辑器**中查看文档。

#### #TODO
- [x] 登录、注册、权限相关接口
- [x] 用户相关接口
- [x] 订单相关接口
- [x] 项目相关接口
- [ ] 支付相关接口
- [ ] 充值相关接口

#### #Help wanted
