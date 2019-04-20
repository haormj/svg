## svg

### 为什么?

#### 需求

1. 开发过程中需要绘制图直观表述当前系统架构
2. 希望图片可以方便的被修改,而不是类似`png`/`jpg`生成之后就没办法修改
3. 有好的绘图工具,可以直观的绘图,而不是写代码绘图,背离绘图的初衷
4. 有好的保真原则,放大和缩小都不影响观看
5. 可以被`markdown`引用,在`gitlab`/`github`上都能支持
6. 有大量基础图形库

#### 方案

1. 调研后选择`svg`,感觉`ppt`太重,[mermaid](https://mermaidjs.github.io/)不能解决需求
2. 工具为[inkscape](https://inkscape.org/),跨平台且在更新

3. 经过实验`github`支持`svg`,但`gitlab`在`11.9.6`虽然支持,但还不是很好,勉强接受
4. 基础图形库虽然有,但对个人而言,需要的还是开发的图形库,从而创立本项目积累基础图形库

### 基础图形

#### 说明

svg大小为128px

#### 开发

<table border=1 cellspacing=0>
    <tr>
        <td><img src="./dev/long-arrow.svg" heigth="128px" width="128px"/></td>
        <td><img src="./dev/long-arrow.svg" heigth="128px" width="128px"/></td>
        <td><img src="./dev/long-arrow.svg" heigth="128px" width="128px"/></td>
        <td><img src="./dev/long-arrow.svg" heigth="128px" width="128px"/></td>
        <td><img src="./dev/long-arrow.svg" heigth="128px" width="128px"/></td>
        <td><img src="./dev/long-arrow.svg" heigth="128px" width="128px"/></td>
    </tr>
</table>


#### 自制

<table border=1 cellspacing=0>
    <tr>
        <td><img src="./diy/bear.svg" heigth="128px" width="128px"/></td>
        <td><img src="./diy/haormj-webdings.svg" heigth="128px" width="128px"/></td>
        <td><img src="./diy/baby.svg" heigth="128px" width="128px"/></td>
        <td><img src="./diy/bear.svg" heigth="128px" width="128px"/></td>
        <td><img src="./diy/bear.svg" heigth="128px" width="128px"/></td>
        <td><img src="./diy/bear.svg" heigth="128px" width="128px"/></td>
    </tr>
    <tr>
        <td><img src="./diy/bear.svg" heigth="128px" width="128px"/></td>
        <td><img src="./diy/bear.svg" heigth="128px" width="128px"/></td>
        <td><img src="./diy/bear.svg" heigth="128px" width="128px"/></td>
        <td><img src="./diy/bear.svg" heigth="128px" width="128px"/></td>
        <td><img src="./diy/bear.svg" heigth="128px" width="128px"/></td>
        <td><img src="./diy/bear.svg" heigth="128px" width="128px"/></td>
    </tr>
</table>

### 参考

1. [可缩放向量图形](https://zh.wikipedia.org/wiki/%E5%8F%AF%E7%B8%AE%E6%94%BE%E5%90%91%E9%87%8F%E5%9C%96%E5%BD%A2)
2. [Comparison of vector graphics editors](https://en.wikipedia.org/wiki/Comparison_of_vector_graphics_editors)
