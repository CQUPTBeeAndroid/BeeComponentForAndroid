# 勤奋蜂 Android 组件化架构
## 整体预期功能
- 支持分模块调试
- 支持组件间相互调用（不只是Activity跳转，支持任意指令的调用/回调）
- 支持app间调用的开关及权限设置（满足不同级别的安全需求，默认打开状态且不需要权限）
- 支持同步/异步方式调用
- 支持超时设置
- 编译时自动注册组件(IComponent)，无需手动维护组件注册表
- 支持动态注册/反注册组件(IDynamicComponent)



## 参考文章
- 组件化思想及源码
[Android组件化方案](https://blog.csdn.net/guiying712/article/details/55213884)
[得到app组件化源码 作者版：JIMU ](https://github.com/mqzhangw/JIMU)
[得到app组件化：Android彻底组件化方案实践](https://www.jianshu.com/p/1b1d77f58e84)
[AndroidModulePattern github 源码](https://github.com/guiying712/AndroidModulePattern)

- Gradle插件、Maven
[Gradle for Android 翻译版 ](https://segmentfault.com/a/1190000004229002)
[Gradle插件开发](https://www.jianshu.com/p/3c59eded8155)
[Gradle User Guide](https://docs.gradle.org/current/userguide/userguide_single.html#custom_plugins)
[Writing Custom Plugins](https://docs.gradle.org/current/userguide/custom_plugins.html)
[在AndroidStudio中自定义Gradle插件](https://www.jianshu.com/p/d53399cd507b)
[如何使用Android Studio开发Gradle插件](https://blog.csdn.net/sbsujjbcy/article/details/50782830)
[拥抱 Android Studio 之五：Gradle 插件开发](http://geek.csdn.net/news/detail/64058)
[AndroidStudio本地化配置gradle的buildToolsVersion和gradleBuildTools](https://blog.csdn.net/guiying712/article/details/72629948)
[Gradle for Android（二）全局设置、自定义BuildConfig](https://www.cnblogs.com/xinmengwuheng/p/5797048.html)
[RUNTIME CLASSPATH VS COMPILE-TIME CLASSPATH](http://techblog.bozho.net/runtime-classpath-vs-compile-time-classpath/)
[Dependency Scope](http://maven.apache.org/guides/introduction/introduction-to-dependency-mechanism.html#Dependency_Scope)
[creating and managing module](https://www.jetbrains.com/help/idea/creating-and-managing-modules.html)
[发布Android studio项目到本地Maven仓库](https://www.jianshu.com/p/8d7d0cc8fcc3)
[Android studio User Guide The Top-level Build File](https://developer.android.com/studio/build/index.html#top-level)
[ Gradle Docs 4.7 xtra properties](https://docs.gradle.org/current/userguide/writing_build_scripts.html#sec:extra_properties)

- 注解
[知乎专栏 聊聊Apt/Annotation Processor](https://zhuanlan.zhihu.com/p/38433630)
[Android中使用AbstractProcessor在编译时生成代码 使用](https://blog.csdn.net/industriously/article/details/53932425)
[Android编译时注解APT实战（AbstractProcessor）](https://www.jianshu.com/p/07ef8ba80562)
[ javapoet 官方github地址 （注意看REAGME）](https://github.com/square/javapoet)
[]()

- 路由技术
[ARouter](https://github.com/alibaba/ARouter)
[EasyRouter](https://github.com/Zane96/EasyRouter)

- MVP架构
[MVP 模式](http://kaedea.com/2015/10/11/android-mvp-pattern/)
[Android MVP 详解 (上) ](http://www.jianshu.com/p/9a6845b26856)
[Android MVP 详解（下）](https://www.jianshu.com/p/0590f530c617)

- 相关 app 参考
[微阅 app](https://github.com/Will-Ls/WeiYue)
[[Android]如何做一个崩溃率少于千分之三噶应用app--章节列表 苍王](https://www.jianshu.com/p/94a05b996d78)
