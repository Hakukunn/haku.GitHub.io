<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<meta name="viewport" content="initial-scale=1.0, user-scalable=no" />

	<script type="text/javascript" src="//api.map.baidu.com/api?v=2.0&ak=LXpXl6bnXk8EPypPqxwu1CL1s2j0jLU9"></script>
	<title>地图展示</title>
</head>

	<div id="allmap"></div>

</html>
<script type="text/javascript">
	// 百度地图API功能
	var map = new BMap.Map("allmap");    // 创建Map实例
	map.centerAndZoom(new BMap.Point(120.081007,29.451391), 11);  // main初始化地图,设置中心点坐标和地图级别
	//添加地图类型控件
	map.addControl(new BMap.MapTypeControl({
		mapTypes:[
            BMAP_NORMAL_MAP,
            BMAP_HYBRID_MAP
        ]}));	  
	map.setCurrentCity("义乌");          // 设置地图显示的城市 此项是必须设置的
	map.enableScrollWheelZoom(true);     //开启鼠标滚轮缩放
</script>
![yiwu](https://github.com/Hakukunn/Hakukunn.github.io/blob/main/yiwu.jpg)

[义乌介绍](https://baike.baidu.com/item/%E4%B9%89%E4%B9%8C/214555?fr=aladdin)	

      
//<img src="https://github.com/Hakukunn/Hakukunn.github.io/blob/main/yiwu.jpg" width="16px">
	<br>

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Hakukunn/-.GitHub.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

      
![宰](https://github.com/Hakukunn/haku.GitHub.io/blob/gh-pages/timgYPCDKH9U.jpg)

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Hakukunn/-.GitHub.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
