基于Android10的Launcher3源码，修改后，在AndroidStudio中编译通过。
编译过程如下https://zhuanlan.zhihu.com/p/141243776

验证过的功能
- 应用微件(RemoteViews)
- 桌面排列(网格，3x3，4x4...)
- 横竖屏切换(CellLayout，Icon等的处理)
- 应用处理(应用load，uninstall)
  
- 应用圆点(通知类的提示)
- 主屏设置
  - 应用通知
  - 图标添加到主屏幕
  - 旋转控制
  - 开启网格

- 双层桌面(LauncherModel加载，Workspace，BaseLayer滑动控制, WipeDetector)
- 应用拖拽(DragLayer拖拽)
- 应用卸载
- 应用快捷功能(长按应用的快捷功能, PopDataProvider 查询出所有快捷方式， 权限校验)
- 搜索(QsbContainerView$QsbFragment)
- 负一屏(自主开发)
未经验证，但是直观体验到的功能

- pwd应用
- 壁纸
-



