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
