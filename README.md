# NewsPaper
#依据设计图制作报纸版面页面；

#知识注意点：

#vertical-align: 垂直对齐的各个参数（行内元素间）
#baseline 基准线对齐（一般是内容文字的基线）, 
#sub 文本的下标对齐,
#super文本的上标对齐 ,
#top 最顶端对齐 , 
#text-top 依据字体顶端对齐 ,
#middle 中间对齐 , 
#bottom 最低端对齐, 
#text-bottom 依据文字的最低端对齐,
#% 大小为行高的百分比 ,
#inherit

#:first-letter伪类，选择段落的首个字母

#text-transform : capitalize  首字母大写

#font-variant: small-caps  使用小型大写字母


#段落首字下沉效果：
#使用:first-letter伪类，选择首字，增大字号且设置浮动，段落的其他文字会形成环绕效果；

#文字环绕图片：
#设置图片浮动，图片下面的文字会自动环绕图片（设置图片在段落内部，可实现三面环绕）；

#大写单词首字母更大：
#设置首字母大写和小型大写字母，即可实现；
#若使用额外的标签包住首个字母，会使下划线不对齐；