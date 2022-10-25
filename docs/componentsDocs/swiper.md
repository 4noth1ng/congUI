# Swiper 轮播图
### 轮播图组件

### 实例
### 
<c-swiper></c-swiper>

### 代码
```html
<c-swiper :list="list" :autoplay="true" :duartion="1000"></c-swiper>
```
```javascript
list1: [
        {
        id: 0,
        imgSrc: '/picture1.4c4d0655.png'
        },
        {
        id: 1,
        imgSrc: '/picture2.20a36478.png'
        },
        {
        id: 2,
        imgSrc: '/picture3.15c04f77.png'
        },
    ],
```

### Attributes
 | 参数 | 说明 | 类型 | 是否必要 | 默认值 |
 | ---  | ---  | --  |   ----   | ----  |
 | list | 轮播图数据 | Array | true | - |
 | autoplay | 是否自动播放 | Boolean | false | false |
 | duration | 定时器时间 | Number | false | 3000 |