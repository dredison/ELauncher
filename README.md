# 墨水屏

## 多看电子书桌面

### 主要功能
- 展示/隐藏/卸载APP
- 悬浮球(返回/主页/刷新/自定义)
- 应用自启
- 清理后台
- 跳转原生设置(无障碍/设备管理器)

//跳转自带的应用列表
intent.component = ComponentName(
                    "com.mgs.settings",
                    "com.mgs.settings.app.AppMain"
                );

//跳转dpi设置，但是不知道参数，有知道的可以告诉我
intent.component = ComponentName(
                    "com.mgs.settings",
                    "com.mgs.settings.app.EinkSettingsDialog"
                );