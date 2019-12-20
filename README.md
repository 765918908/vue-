# vue-tool
# grid九宫格效果
![九宫格效果](https://github.com/765918908/imgStorage/blob/master/img-storage/grid.jpg)
# 用法
```
js:
	import {NineGrid,GridRow,GridItem} from '@/components/common/grid'
  components: {
			NineGrid,
			GridRow,
			GridItem
		}
    
 html:
 		<nine-grid>
			<grid-row>
				<grid-item>
					<img slot="grid-icon" src="../../assets/icon/licai.png" />
					<div slot="grid-text">文字</div>
				</grid-item>
				<grid-item>
					<img slot="grid-icon" src="../../assets/icon/licai.png" />
					<div slot="grid-text">文字</div>
				</grid-item>
				<grid-item>
					<img slot="grid-icon" src="../../assets/icon/licai.png" />
					<div slot="grid-text">文字</div>
				</grid-item>
			</grid-row>
		</nine-grid>
```
 
# tabbar底部导航效果
![底部导航效果](https://github.com/765918908/imgStorage/blob/master/img-storage/tabbar.jpg)
```
		<tab-bar>
			<tab-bar-item path="/home">
				<img slot="item-icon" src="../assets/icon/home.png"/>
				<img slot="item-icon-active" src="../assets/icon/home-active.png"/>
				<div slot="item-text">首页</div>
			</tab-bar-item>
			<tab-bar-item path="/my">
				<img slot="item-icon" src="../assets/icon/my.png"/>
				<img slot="item-icon-active" src="../assets/icon/my-active.png"/>
				<div slot="item-text">我的</div>
			</tab-bar-item>
		</tab-bar>
``` 
