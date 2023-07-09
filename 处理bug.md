# bug处理汇总

### 1. `Error: The URL must be of scheme file at D:\Code\GitHub\vue3-ts-eplus-template\vite.config.ts`

node版本过高，换成 16.0.0 即可

### 2. npm i reset.css

引入 `@import 'reset.css/reset.css';` 完整路径即可

### 3. 解决 ElMessage 报类型错误

[解决 TS ElMessage 报类型错误](https://www.cnblogs.com/sunshine-wy/p/17381028.html)

添加 `tscofing.app.json` `"moduleResolution": "Node"`,
