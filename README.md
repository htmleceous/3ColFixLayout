# 3ColFixLayout
## 3-column Fixed Width Layout Using Semantic Markup
![3-column Fixed Width Layout Using Semantic Markup ](https://github.com/htmleceous/3ColFixLayout/blob/master/images/result-right-align.jpg)

The padding is placed only on the top and bottom of the block elements. Avoiding padding on the left and/or right edges of the block elements prevents any redoing of the block level mathematics because if you place padding on the left and/or right edges of the block elements, the width of the block will be affected. Therefore, if you want to add margins to those block elements, place margin on the elements they host.

If you want the navigation on the right side of the page, just float the following to the right and browser will render them in reverse order:

       .sidebar1 {
            float: right;
            width: 200px;
            background-color: #5f450c;
        }
        
        .content {
            padding: 10px 0;
            width: 560px;
            float: right;
        }
        
        aside {
            float: right;
            width: 200px;
            background-color: #eadcae;
            padding: 10px 0;
            border-bottom: 1px solid #31302f;
        }
