110.Building the Story Section Part 1 ~ 2

-   How to deal with overlapping grid items;
-   Why images are special and behave differently than other grid items;
-   How to decide if flexbox is a better tool in certain situations.

如果是常规元素，设置好 grid-area 属性后，会填满区域；但是如果是 img 元素，则不会，因为图像本身有一定的尺寸和纵横比，图像本身总是会试图保持纵横比例。那么为了让图像可以保持居中，就可以给父元素使用 align-items: center 来设置元素居中显示。

想要给图片设置不同的背景颜色，就可以借助 background-img 中的 linear-gradient 属性。