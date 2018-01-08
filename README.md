### 客户端API

#### #使用
> Windows环境下一切操作请在 git bash中进行，CMD会有坑
- 下载并安装 [node.js](https://nodejs.org/en/)，下载LTS稳定版本。目前文档版本为8.9.4
- 更换npm源，终端（git bash）中输入 `npm config set registry https://registry.npm.taobao.org`
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
cd swagger-editor
npm run dev
```
###### 提示：上面 clone swagger-editor 这个库可能会超级超级慢，可以直接从 github 下载 zip。 文件名应该是 swagger-editor-it-master。保证它与common-solution-frontend 同级目录
***
- 项目运行成功，在浏览器输入 http://localhost:3200。
  当终端看到 `build modules[BABEL] Note: The code generator has deoptimised the styling of "D:/repository/swagger-editor/src/plugins/validation/validation.worker.js" as it exceeds the max of "500KB".` 就应该运行成功
- 将`swagger.yaml`文件中的内容到**Swagger 文档在线编辑器**中查看文档。

#### #TODO
- [x] 登录、注册、权限相关接口
- [x] 用户相关接口
- [x] 订单相关接口
- [x] 项目相关接口
- [ ] 支付相关接口
- [ ] 充值相关接口

#### #Help wanted
@helloztt 及时提出改正意见