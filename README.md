# Dot
Dot 是一个使用canvas制作的粒子特效插件，使用简单方便。
### 1、Feature
1. 使用原生canvas，不需依赖任何外部插件
1. 支持`AMD`&&`CMD`规范

### 2、Install&&Useage
下载文件引入`Dot.js`文件

```bash
<canvas id="dot" style="background:linear-gradient(to bottom, #B80D57, #C9182B);">
	<p>your browser not support canvas</p>
</canvas>
```

```bash
<script src="js/dot.js"></script>
<script>
Dot("dot", {*****});
</script>
```

###3、DEMO
运行`demo.html`

![](demoImgs/demo.png)

###4、Configure
|   属性  |   类型  | 默认值 |   描述   |
|--------|-------- |-------|-------- |
|cW| Number| 1367  |canvas宽度|
|cH| Number| 500  |canvas高度|
|numDot| Number | 100 |粒子数目|
|radDot| Number| 3 | 粒子半径|
|isRangeRad| Boolean | true  |是否随机粒子半径（给定的radDot范围内）|
|dotColor| String | ”#FFFFFF“ |粒子填充颜色|
|lineDist| Number | 75  |连线距离|
|lineColor| String| "#FFFFFF"  |连线颜色|
|bounce| Number | 1  |反弹系数|
|opacity|  Number | 0.5  |透明度|
|isTouch|  Boolean | false  | 是否与鼠标发生交互|
|vxRange|  Number | 2  | 粒子x方向速度|
|vyRange|  Number | 2  | 粒子y方向速度|
|isWallCollisionTest|  Boolean | true  | 是否与边界碰撞检测|
|isBallCollisionTest|  Boolean | true  | 球体间是否发生碰撞检测|

###5、Supports browser
- IE 10+
- Chrome
- Firefox
- Opera
- Safari