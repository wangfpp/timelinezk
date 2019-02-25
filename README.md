# 基于TimeLinejs3的修改
- 支持import引入
- 支持Swiper轮播

# 使用方法

- npm install timelinezk
- 在需要的文件中 import 'timelinezk';
- 在main.js中 import 'timelinezk/css/timeline.css';

# Swiper的配置
		import 'timelinezk';
		let options = {
			......,
			swiper: {
                isable: true, # 是否支持轮播
                time_gap: 3000, # 轮播的时间间隔
                tag: '' # 定时器标识
            },
            ......
		};
		let timeline = new TL.Timeline(node, timeline_json, options); # 挂载的节点 events事件 配置参数

# 参考文件
[TimeLine官网](https://timeline.knightlab.com/)  
[TimeLine Github地址](https://github.com/NUKnightLab/TimelineJS3)