# wepy-com-cutex1
微信小程序适配iPhoneX组件

## 用法

```html
<script>
import Ipx from 'wepy-com-cutex1'
import wepy from 'wepy'
export default class Home extends wepy.page {
    components = {
        Ipx,
    }
}
</script>

<template>
    <view class="page--home">
        <Ipx>
            <view slot="content" class="home-main">
                This is main content...
            </view>        
        </Ipx>
    </view>
</template>

<style lang="scss" scoped>
.page-home{
    width: 100%;
    height: 100%;
    background-color: blue;//here is your bg-color...
    .home-main{
        width: 100%;
        height: 100%;
    }
}
</style>
//...
```