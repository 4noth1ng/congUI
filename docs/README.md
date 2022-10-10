# 快速开始

#### 安装组件库

```bash
npm i cong-ui
```

#### 引用组件库
> 在 main.js 中引用组件库

```javascript
// 全部引入
import 'cong-ui/style/index.css';
import CUI from 'cong-ui';
Vue.use(CUI)

// 按需引入
import 'cong-ui/style/card.css';
import { Card } from 'cong-ui';
Vue.use(Card)

// 在页面中使用
<div>
  <c-card></c-card>
</div>
```