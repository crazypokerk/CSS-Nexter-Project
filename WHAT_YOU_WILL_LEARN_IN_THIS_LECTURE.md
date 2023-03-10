110.Building the Story Section Part 1 ~ 2

-   How to deal with overlapping grid items;
-   Why images are special and behave differently than other grid items;
-   How to decide if flexbox is a better tool in certain situations.

如果是常规元素，设置好 grid-area 属性后，会填满区域；但是如果是 img 元素，则不会，因为图像本身有一定的尺寸和纵横比，图像本身总是会试图保持纵横比例。那么为了让图像可以保持居中，就可以给父元素使用 align-items: center 来设置元素居中显示。

想要给图片设置不同的背景颜色，就可以借助 background-img 中的 linear-gradient 属性。

112.Building the Homes Scetion Part 1 ~ 2

-   How to build a rather complex component using a mix of CSS Grid properties, overlapping and flexbox.

grid 布局目前没有办法单独设置某一行、某一列的 gap 大小。

114.Building the Gallery Part 1 ~ 2

-   How to create a complex grid-looking gallery;
-   Using `object-fit` together with images for grid items.

`object-fit: cover` 只有在手动设置了`width`和`height`之后才会生效。

116.Building the Footer

Apply the concepts you already learned.

想要使得段落居中，可以设置`margin-left: auto; margin-right: auto;`。

117.Building the Sidebar

Apply the concepts you already learned.

118.Building the Header Part 1 ~ 2

-   How to manage vertical spacing in a responsive layout using CSS Grid techniques;
-   How to use `::before` and `::after` as grid items.

伪类元素也可以占据网格布局，所以如果有伪类元素也可以使用`grid`布局。

120.Building the Realtors Section

Apply the concepts you already learned.

121.Writing Media Queries Part 1 ~ 2

响应式布局可以宽度和高度可以选择使用`max-width`和`max-height`

123.Browser Support for CSS Grid

渐进式增强：`@support`
