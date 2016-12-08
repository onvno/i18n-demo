# i18n-demo
#### 安装依赖

```
npm install
```

#### demo示例说明

- front:前端渲染示例(`i18next`):

  ```
  # 进入目录
  cd demo/front

  # 启动服务
  python -m SimpleHTTPServer 8001

  # 查看效果(进入页面，点击切换)
  http://localhost:8001/
  ```

  ​

- back:服务器端渲染示例(`i18n-node`)

  ```
  # 进入目录
  cd demo/back

  # 启动服务
  node index

  # 查看效果(路由控制输出三种语言切换)
  http://localhost:3000/onres/en
  http://localhost:3000/onres/de
  http://localhost:3000/onres/ar
  ```

  实际项目中，可通过模板引擎传值渲染

  ​

  ​