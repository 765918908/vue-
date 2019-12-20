# vue-tool
# 效果
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
