### CSS选择器n为负的情况

:nth-child(-n+2)

选中从第1个到第2个子元素。使用 :nth-child(-n+9) ，就相当让你选中第2个和其之前的所有子元素

```
<style>
    span:nth-child(-n+2) {
        color: red;
    }
</style>
<div class="box">
    <span>1</span>
    <span>2</span>
    <span>3</span>
    <span>4</span>
    <span>5</span>
    <span>6</span>
    <span>7</span>
</div>

```

### CSS选择器范围

前后限制范围

:nth-child(n+4):nth-child(-n+8)

选中第4-8个子元素。使用 nth-child(n+4):nth-child(-n+8) 我们可以选中某一范围内子元素，上面的例子里是从第4个到第8个子元素