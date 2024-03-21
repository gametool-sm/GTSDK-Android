# GTSDK AAR

目录树：

```java
├─Androidx
│  │  gtsdk-androidx.aar
│  │  gtsdk-androidx_constrainlayout_1.1.3.aar
│  │
│  └─getIdentifier
│          gtsdk-androidx.aar
│          gtsdk-androidx_constrainlayout_1.1.3.aar
│
└─Support
    │  gtsdk-support.aar
    │  gtsdk-support_constrainlayout_1.1.3.aar
    │
    └─getIdentifier
            gtsdk-support.aar
            gtsdk-support_constrainlayout_1.1.3.aar
```

1、Androidx 文件夹下为 Androidx 版本的 aar。

2、Support 文件夹下为 Support 版本的 aar。

3、其中还提供了 ConstrainLayout 版本为 1.1.3 版本的 aar，在接入普通 aar 后界面控件堆积在屏幕左上角的情况下可以使用此 aar，看是否还存在问题

4、getIdentifier 文件夹下的 aar 使用 getIdentifier 方法获取资源，未使用 R.id、R.layout 等方式获取资源，有需求的可以使用。

官方接入文档：https://docs.gametool.com/detail/1?p=2&v=1

示例Demo：https://github.com/gametool-sm/GameToolDemo-Android