# Flex learn

>1.justify-content
*定义主轴对齐方式*
- 可选：flex-start(default): 左对齐
- flex-end: 右对齐
- center: 居中对齐
- space-between: 两端对齐
- space-around: 所有间隔都相同


>2.lex-direction
*定义主轴方向(即排列的方向)*
- row (default): 主轴为水平方向，起点在左边
- row-deserve：主轴为水平方向，起点在右边
- column： 主轴为竖直向，起点在上
- column-reserve: 主轴为水平方向，起点在最下


>3.flex-wrap
*定义换行方式*
- flex-wrap
- nowrap(default): 不换行
- wrap： 换行
- wrap-reserve： 换行


>4.flex-flow: flex-direction || flex-wrap;
*以上两者的简写形式*


>5.align-items：
*定义在交叉轴上如何对齐*
- flex-start:交叉点与起点对齐
- flex-end:交叉点与终点对齐
- center:交叉点与中点对齐
- baseline:与第一行文字的基线对齐
- stretch(default): 如元素未设置高度或者auto，将默认占满所有高度


>6.align-content
*定义多根轴线的对齐方式。如果只有一根，则不起作用*
- flex-start:flex-start：与交叉轴的起点对齐。
- flex-end：与交叉轴的终点对齐。
- center：与交叉轴的中点对齐。
- space-between：与交叉轴两端对齐，轴线之间的间隔平均分布。
- space-around：每根轴线两侧的间隔都相等。所以，轴线之间的间隔比轴线与边框的间隔大一倍。
- stretch（默认值）：轴线占满整个交叉轴
