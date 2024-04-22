# GTSDK AAR

目录树：

```java
├─Androidx
│  │  gtsdk-androidx.aar
│  │
│  └─getIdentifier
│          gtsdk-androidx.aar
│
└─Support
    │  gtsdk-support.aar
    │
    └─getIdentifier
            gtsdk-support.aar
```

1、Androidx 文件夹下为 Androidx 版本的 aar。

2、Support 文件夹下为 Support 版本的 aar。

3、getIdentifier 文件夹下的 aar 使用 getIdentifier 方法获取资源，未使用 R.id、R.layout 等方式获取资源，有需求的可以使用，目前此方式并不完全，部分第三方库内部仍然使用 R.id 方式获取资源，如果因此导致屏幕样式堆积异常且无法处理，请联系盖姆兔官方人员使用注入方式接入。

官方接入文档：https://docs.gametool.com/detail/1?p=2&v=1

示例Demo：https://github.com/gametool-sm/GameToolDemo-Android