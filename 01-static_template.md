# 1.静态模板 - Static Template

为了说明angularJS如何增强了标准HTML，我们先将创建一个静态HTML页面模板，然后把这个静态HTML页面模板转换成能动态显示的AngularJS模板。

在本步骤中，我们往HTML页面中添加两个手机的基本信息，用以下命令将工作目录重置到步骤1。

```sh
git checkout -f step-1
```

请编辑`app/index.html`文件，将下面的代码添加到`index.html`文件中，然后运行该应用查看效果。

**app/index.html**

```html
<ul>
    <li>
        <span>Nexus S</span>
        <p>
        Fast just got faster with Nexus S.
        </p>
    </li>
    <li>
        <span>Motorola XOOM™ with Wi-Fi</span>
        <p>
        The Next, Next Generation tablet.
        </p>
    </li>
</ul>
```

## 练习

尝试添加多个静态HTML代码到index.html， 例如：

```
<p>Total number of phones: 2</p>
```

## 总结

本步骤往应用中添加了静态HTML手机列表， 现在让我们转到步骤2以了解如何使用AngularJS动态生成相同的列表。