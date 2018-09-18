<h1 align="center">adaption_by_rem（A Plug-in for mobile adaption）</h1>

## Introduce
通过rem实现的移动端适配方案

## Install

```sh
    npm install adaption_by_rem
```

## Example
在你需要进行适配的页面引入adaption_by_rem库
```javascript
    // your xx.js
    import 'adaption_by_rem';
```
如果你的UI设计稿是iphone6尺寸，在你的css中只需要除以100即可得到对应的rem值。

比如设计稿上box宽为150px, 设置为1.5rem即可适配其他尺寸屏幕；
```css
.box {
    width: 1.5rem; 
}
```
如果设计稿为其他尺寸宽度，需自行修改lib/util.js中传入的参数

## Todo
命令化、配置化