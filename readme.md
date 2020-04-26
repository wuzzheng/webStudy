- 学习了盒子模型，并用所学的知识，写了一个小案例
- 学习了 float 浮动，若是主容器中的元素都使用了 float，会有高度坍塌，在主容器使用`overflow: hidden;`来解决高度坍塌
- `a`标签去除下划线使用`text-decoration: none`
- `文本溢出处理`
    ```css
        /*单行*/
        overflow: hidden;
        text-overflow: ellipsis;
        white-space: nowrap;
        margin: 20px;

        /* 多行溢出处理 */
        overflow: hidden;
        text-overflow: ellipsis;
        display: -webkit-box;
        -webkit-line-clamp: 2;
        -webkit-box-orient: vertical;
    ```
