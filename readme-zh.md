# 项目说明

原版仓库： [GitHub - BlankSourceCode/obs-zoom-to-mouse: An OBS lua script to zoom a display-capture source to focus on the mouse](https://github.com/BlankSourceCode/obs-zoom-to-mouse)

由于在 OBS 32.1.2 上面持续报错，于是我就改了一下bug，测试 `OBS 32.1.2` 可用

# 安装方法

在OBS中添加脚本： 打开OBS，依次点击：工具 -> 脚本 -> 点击 + 增加脚本，将 `obs-zoom-to-mouse.lua` 脚本添加进来。

# 中英文功能对照

- 缩放源 (显示器采集)（Zoom Source）: 选择需要对鼠标光标进行缩放的显示捕获源。
- 刷新缩放源（Refresh zoom sources）: 刷新可用的显示捕获源列表。
- 缩放系数（Zoom Factor）: 控制缩放级别，数值越大，缩放效果越明显。
- 缩放速度（Zoom Speed）: 调整缩放效果的过渡速度，数值越低，缩放越慢；数值越高，缩放越快。
- 自动跟随鼠标（Auto follow mouse）: 勾选后，脚本会自动跟随鼠标光标。
- 跟随外部界限（Follow outside bounds）: 勾选后，即使鼠标移出预定缩放区域，缩放也会继续跟随鼠标。
- 跟随速度（Follow Speed）: 控制缩放跟随鼠标光标的速度。
- 跟随边框（Follow Border）: 确定鼠标必须在屏幕边缘内的距离，缩放才会开始跟随鼠标。
- 锁定灵敏度（Lock Sensitivity）: 调整锁定功能的灵敏度，可能指缩放跟随光标的紧密程度。
- 反向方向上的自动锁定（Auto Lock on reverse direction）: 勾选后，当鼠标改变方向时，缩放会锁定在当前位置。
- 允许任何缩放源（Allow any zoom source）: 启用后，任何显示捕获源都可以用于缩放，而不仅仅是最初选择的那个。
- 设置手动源位置（Set manual source position）: 手动设置缩放源的位置。
- 更多信息（More Info）: 提供关于脚本的更多信息或帮助。
- 启用调试日志记录（Enable debug logging）: 启用后，会开始记录调试信息，用于解决脚本问题。
- 默认（Default）: 将所有设置重置为默认值。
- 编辑脚本（Edit Script）: 允许直接编辑Lua脚本。
- 脚本日志（Script Log）: 打开脚本的日志文件，查看记录的信息和错误。
- 关闭（Close）: 关闭设置窗口。