# biliplayerPlus

基于Tampermonkey插件的对bilibili播放器的功能增强

## 更新日志

### 2022.5.9
- 实现下拉框组件
- 实现切换按钮组件
- 实现滑动条组件
- 对状态栏进行监控
- 对history路由变化进行监控
- 实现消息提示组件
- 对键盘快捷键进行监控
- 对快捷键进行动态绑定判断
- 添加节流函数
- 实现默认设置和自定义设置的对接

### 2022.5.10
- 使用css优化下拉框组件性能
- 使用css优化消息提示组件

### 2022.5.11
- 使用shadowroot重构下拉框、滑动条、切换按钮组件
- 添加shadowroot的启用选项
- 使用css优化滑动条组件性能
- 按键绑定添加快捷键冲突提示
- 添加冲突项的提示
- 解决切换视频时设置按钮绑定消失的bug

### 2022.5.12
- 添加宽屏全屏判断函数，修复初始化时尺寸变换的bug
- 监听b站速度控制面板的切换

### 2022.5.21
- 监听b站画质面板的切换(未实现大会员检测)

### 2022.5.22
- 实现多选框组件
- 添加hidden隐藏属性，用以在页面不显示
- 实现hidden属性和多选框属性的对应
- 重构滑动条组件UI，使得滑动条与b站原生样式一致
- 修复滑动条组件过渡效果bug
- 添加滑动条左右端点时加减按钮的disable
- 添加触摸事件选项

### 2022.5.23
- 添加触摸事件监听
- 触摸事件触发方向添加为8个方向
- 修复触摸事件触发方向异常的bug
- 修复进度条更改异常的bug
- 添加进度条和音量更改手势支持

### 2022.5.28
- 添加长按触摸事件的监听
- 添加短按触摸事件的监听

### 2022.6.9
- 实现按钮组件

### 2022.7.4
- 添加图标组件
- 使用图标组件重构部分代码
- 重构图标库引入代码，引入最新的Material图标库

### 2022.7.5
- 添加按钮按下特效
- 修复全屏模式下消息提示框消失的bug
- 修复滑动条过渡特效的启用切换不实时生效的bug
- 重写下拉框内容更改绑定逻辑
- 修复下拉框修改循环调用的bug
- 修复多选框内容联动更新bug

### 2022.7.6
- 修复下拉框点击边框后选项消失的bug

### 2022.10.7
- 添加数字框组件
- 修复数字框组件与shadowroot的样式联动bug
- 修复数字框组件与滑动条的联动bug
- 修复数字框组件shadowroot开启后字体丢失的bug
- 添加数字框组件长按按钮一直改变数字的功能
- 修复数字框组件能够输入非数字的bug
- 修复数字框组件输入时光标异常错位的bug
- 修复数字框组件切换shadowroot设置后光标异常错位的bug
- 修复页面加载时脚本无法加载的异常情况
- 修复页面加载后数字框组件显示object的异常bug

### 2022.10.8
- 添加设置面板最小宽高
- 修复数字框组件可以粘贴图片的bug

### 2022.11.3
- 修复多选框宽度异常的bug
- 修复多选框与文字不对齐的bug
- 修改数字框组件长按逻辑
- 滑动条组件添加长按事件，与数字框组件同步逻辑

### 2022.11.4
- 修改变量监听逻辑，修复开启监听值丢失的bug
- 添加弹出提示框组件

### 2022.11.5
- 新增提示框组件，使用自定义组件优化逻辑

### 2022.11.7
- 优化提示框组件逻辑，使其受控
- 解决延迟显示影藏时，显影会冲突的bug
- 添加提示框组件对方向的控制

### 2022.11.8
- 修复提示框组件定位逻辑错误的bug
- 提示框添加algin属性

### 2022.11.10
- 提示框添加箭头相关属性
- 更新提示框布局
- 重构部分提示框逻辑

### 2022.11.11
- 将组件注册放入init之前

### 2022.11.12
- 组件名称添加前缀，防止冲突

### 2022.11.19
- 添加版本更新函数
- 修复触发函数为空时报错的bug

### 2022.12.15
- 将版本更新函数分化为内核更新和用户脚本更新两项

### 2022.12.27
- 更新渲染逻辑，不再保存dom信息

### 2022.12.28
- 更新dependency逻辑

### 2022.12.29
- 更新checkbox组件的部分代码