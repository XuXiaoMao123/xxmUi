# 快速开始

### 安装组件库

```bash
npm i @xxm123/mao-ui
```
### 引用组件库
> 在main.js 中引用组件库

```javascript
//全部引入
import '@xxm123/mao-ui/dist/css/index.css';
import MUI from '@xxm123/mao-ui';
Vue.use(MUI);

//按需引入
import '@xxm123/mao-ui/dist/css/demo.css';
import { Demo } from '@xxm123/mao-ui';
Vue.use(Demo);
```
