# android-interview-record

> Android 高级面试经常会有很多原理分析，以及性能优化监控相关，列出一些高频知识点仅供参考。

[Android 相关](#1)  
[性能优化](#2)  
[Java 相关](#3)  
[Kotlin 相关](#4)  
[网络相关](#5)  
[插件化](#6)  
[图片相关](#7)  
[Gradle 相关](#8)     
[Flutter 相关](#9)  

<h3  id="1">Android 相关</h3>

[Android之SharedPreferences内部原理浅析](https://blog.csdn.net/u010687392/article/details/50174271)

[剖析 SharedPreference apply 引起的 ANR 问题](https://www.jianshu.com/p/9ae0f6842689)

[Android源码分析-消息队列和Looper](https://blog.csdn.net/singwhatiwanna/article/details/17361775)

[Android中Thread、Handler、Looper、MessageQueue的原理分析](http://blog.csdn.net/bboyfeiyu/article/details/38555547)

[Android IntentService完全解析 当Service遇到Handler](http://blog.csdn.net/lmj623565791/article/details/47143563)

[Android源码分析—带你认识不一样的AsyncTask](https://blog.csdn.net/singwhatiwanna/article/details/17596225)

[Android AsyncTask 源码解析](http://blog.csdn.net/lmj623565791/article/details/38614699)

[Android性能优化之使用线程池处理异步任务](http://blog.csdn.net/u010687392/article/details/49850803)

[Android 线程和线程池一篇就够了](https://juejin.im/entry/593109e72f301e005830cd76)

[剖析Android中进程与线程调度之nice](https://droidyue.com/blog/2015/09/05/android-process-and-thread-schedule-nice/)

[【线程死锁】Android多线程死锁的产生以及如何避免](https://blog.csdn.net/Tomasyb/article/details/72884562)

[WatchDog工作原理](http://gityuan.com/2016/06/21/watchdog/)

[《手Q Android线程死锁监控与自动化分析实践》](https://mp.weixin.qq.com/s/lRHLP76V0fr2UwkeImdqzQ?utm_source=joyk.com&utm_medium=referral&hmsr=joyk.com)

[Android Context完全解析，你所不知道的Context的各种细节](http://blog.csdn.net/guolin_blog/article/details/47028975)

[LocalBroadcastManager 的实现原理，与 BroadcastReceiver 异同](http://www.trinea.cn/android/localbroadcastmanager-impl/)

[Activity的启动方式和flag详解](http://blog.csdn.net/singwhatiwanna/article/details/9294285)

[浅析Activity横竖屏切换时的生命周期](浅析Activity横竖屏切换时的生命周期)

[Android源码分析-资源加载机制](http://blog.csdn.net/singwhatiwanna/article/details/24532419)

[Android 源码解析 之 setContentView](http://blog.csdn.net/lmj623565791/article/details/41894125)

[深入剖析 Android中的 ArrayMap](http://droidyue.com/blog/2017/02/12/dive-into-arraymap-in-android/)

[深度解读ArrayMap优势与缺陷](http://gityuan.com/2019/01/13/arraymap/)

[startActivity启动过程分析](http://gityuan.com/2016/03/12/start-activity/)

[startService启动过程分析](http://gityuan.com/2016/03/06/start-service/)

[【凯子哥带你学Framework】Activity启动过程全解析](http://blog.csdn.net/zhaokaiqiang1992/article/details/49428287)

[【凯子哥带你学Framework】Activity界面显示全解析](http://blog.csdn.net/zhaokaiqiang1992/article/details/49681321)

[Android LayoutInflater原理分析，带你一步步深入了解View(一)](https://blog.csdn.net/guolin_blog/article/details/12921889)

[由App的启动说起 | jaminzzhang](https://yq.aliyun.com/articles/26960)

[Android内核开发：图解Android系统的启动过程](http://blog.51cto.com/ticktick/1659473)

[为什么 Android 要采用 Binder 作为 IPC 机制？](https://www.zhihu.com/question/39440766)

[Android进程间通信（IPC）机制Binder简要介绍和学习计划](http://blog.csdn.net/luoshengyang/article/details/6618363)

[Binder VS socket](https://blog.csdn.net/graitude/article/details/55522626)

[Android跨进程通信：图文详解 Binder机制 原理](https://blog.csdn.net/carson_ho/article/details/73560642)

[彻底理解Android Binder通信架构](http://gityuan.com/2016/09/04/binder-start-service/)

[Binder异常解析](http://gityuan.com/2017/05/01/binder_exception/)

[ELF文件格式解析](https://blog.csdn.net/feglass/article/details/51469511)

[loadLibrary动态库加载过程分析](http://gityuan.com/2017/03/26/load_library/)

[Android 的 so 文件加载机制](https://juejin.im/post/5bc832f1e51d450e6973c0be)

[通过ApkTool分析resources.arsc文件以及resources.arsc文件的格式](https://litets.com/article/2019/4/10/307.html)

[Toast 原理剖析](http://thinkdevos.net/2017/10/13/2017-10-13-toast/)

[Android I/O 那些事儿](https://isuperqiang.cn/post/android-io-na-xie-shi-er/)

[10分钟了解Android项目构建流程](https://juejin.im/post/5a69c0ccf265da3e2a0dc9aa)

[RecyclerView性能优化及高级使用](https://blog.csdn.net/smileiam/article/details/88396546)

[android mvvm architecture-samples](https://github.com/android/architecture-samples)

[Lifecycle 使用及原理解析 一文搞懂](https://juejin.im/post/5c90d955f265da60e926783d)

[ViewPager2重大更新，支持offscreenPageLimit](https://juejin.im/post/5cda3964f265da035d0c9d8f)

[Android View的绘制流程知识点总结](https://zhuanlan.zhihu.com/p/44976896)

[深入理解Android之View的绘制流程](https://www.jianshu.com/p/060b5f68da79)

[Android JNI 中的线程操作](https://juejin.im/post/5b4c0a09f265da0f955cc1c7)

[Android JNI 之 Bitmap 操作](https://juejin.im/post/5b5810a56fb9a04f8c5ee296)

[Android组件化方案及组件消息总线modular-event实战](https://tech.meituan.com/2018/12/20/modular-event.html)

[Android 组件化最佳实践](https://juejin.im/post/5b5f17976fb9a04fa775658d)

[Android中JSBridge的原理和实现](https://skyacer.github.io/2018/03/23/Android%E4%B8%ADJSBridge%E7%9A%84%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E7%8E%B0/)

[Android Webview H5 秒开方案实现](https://juejin.im/post/5b94ca52e51d450e7d097f38)

[WebView性能、体验分析与优化](https://tech.meituan.com/2017/06/09/webviewperf.html)

[彻底解析Android缓存机制——LruCache](https://www.jianshu.com/p/b49a111147ee)

[视频缓存AndroidVideoCache攻略](https://www.jianshu.com/p/53c4a6c9bd07)

[Google Exoplayer之全面认识](https://blog.csdn.net/hejjunlin/article/details/54693696)

[设计模式在外卖营销业务中的实践](https://tech.meituan.com/2020/03/19/design-pattern-practice-in-marketing.html)

<h3  id="2">性能优化</h3>

[Android性能优化来龙去脉总结](https://juejin.im/post/5b194563e51d4506d25e20f5)

[Android 性能优化最佳实践](https://juejin.im/post/5b50b017f265da0f7b2f649c)

[Android GC 原理探究](https://zhuanlan.zhihu.com/p/24835977)

[JVM 的工作原理，层次结构以及 GC 工作原理](https://segmentfault.com/a/1190000002579346)

[Java内存问题及 LeakCanary 原理分析](https://juejin.im/post/5ab8d3d46fb9a028ca52f813)

[Android性能优化（十一）之正确的异步姿势](https://www.jianshu.com/p/5f99f0e51118)

[Android 性能优化之布局优化](https://henleylee.github.io/posts/2019/d59595e2.html)

[Android性能优化：那些不可忽略的绘制优化](https://www.jianshu.com/p/cbdaeb1bede5)

[Android中Bitmap内存优化](https://www.jianshu.com/p/3f6f6e4f1c88)

[美团点评移动网络优化实践](https://tech.meituan.com/2017/03/17/shark-sdk.html)

[大众点评App的短视频耗电量优化实战](https://tech.meituan.com/2018/03/11/dianping-shortvideo-battery-testcase.html)

[Android 存储优化 —— MMKV 集成与原理](https://juejin.im/post/5d55284d6fb9a06aee362b07)

[Matrix IOCanary -- I/O 质量监控](https://github.com/Tencent/matrix/wiki/Matrix-Android-IOCanary)

[Matrix TraceCanary -- 初恋·卡顿](https://github.com/Tencent/matrix/wiki/Matrix-Android-TraceCanary)

[Matrix ResourceCanary -- Activity 泄漏及Bitmap冗余检测](https://github.com/Tencent/matrix/wiki/Matrix-Android-ResourceCanary)

[Android图片加载尺寸监控](https://www.jianshu.com/p/fa1c4fbf4f57)

[美团外卖Android Crash治理之路](https://tech.meituan.com/2018/06/14/waimai-android-crash.html)

[理解Android Crash处理流程](http://gityuan.com/2016/06/24/app-crash/#handleApplicationCrashInner)

[理解Native Crash处理流程](http://gityuan.com/2016/06/25/android-native-crash/)

[彻底理解安卓应用无响应机制](http://gityuan.com/2019/04/06/android-anr/)

[ANR问题分析的一般套路](https://www.jianshu.com/p/18f16aba79dd)

[ANR的监测与信息采集](https://www.jianshu.com/p/ac545e10e39e)

[Android ANR 监测方案解析](https://testerhome.com/articles/17101)

[Probe：Android线上OOM问题定位组件](https://tech.meituan.com/2019/11/14/crash-oom-probe-practice.html)

[《Android 创建线程源码与OOM分析》](https://mp.weixin.qq.com/s/Z7cCCF8jzS6NpVEd0b0Emg)

[安装包立减1M--微信Android资源混淆打包工具](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=208135658&idx=1&sn=ac9bd6b4927e9e82f9fa14e396183a8f#rd)

[AabResGuard: AAB 资源混淆工具](https://juejin.im/post/5e115ca7e51d4540e53b7dcc)

[zstd 高质量压缩算法](https://facebook.github.io/zstd/)

[AndroidJniBitmapOperations](https://github.com/AndroidDeveloperLB/AndroidJniBitmapOperations)

[Android开发高手课](https://time.geekbang.org/column/intro/100021101)

<h3  id="3">Java 相关</h3>

[Java 四种线程池的用法分析](https://blog.csdn.net/u011974987/article/details/51027795)

[Java有几种文件拷贝方式？哪一种最高效？](https://blog.csdn.net/qweqwruio/article/details/81359618)

[使用FileChannel(文件通道)来实现文件快速复制](http://blog.csdn.net/wangxy799/article/details/50897061)

[JVM类加载机制详解（一）JVM类加载过程](https://blog.csdn.net/zhangliangzi/article/details/51319033)

[JVM类加载机制详解（二）类加载器与双亲委派模型](https://blog.csdn.net/zhangliangzi/article/details/51338291)

[Java实现线程同步的几种方式](https://www.jianshu.com/p/6542c8a96392)

[java笔记七：IO流之字节流与字节缓冲流](http://www.cnblogs.com/liuling/archive/2013/05/07/InputStreamAndOutputStream.html)

[Java NIO浅析](https://tech.meituan.com/2016/11/04/nio.html)

[Java内存管理：深入Java内存区域](http://www.cnblogs.com/gw811/archive/2012/10/18/2730117.html)

[看完这篇垃圾回收，和面试官扯皮没问题了](https://mp.weixin.qq.com/s/8vXENzg580R7F2iNjSdHFw)

[理解Java中的ThreadLocal](http://droidyue.com/blog/2016/03/13/learning-threadlocal-in-java/index.html)

[理解Java中的弱引用](https://droidyue.com/blog/2014/10/12/understanding-weakreference-in-java/)

[理解Java的强引用、软引用、弱引用和虚引用](https://juejin.im/post/5b82c02df265da436152f5ad)

[Java中的堆和栈的区别](http://droidyue.com/blog/2014/12/07/differences-between-stack-and-heap-in-java/)

[HashMap 用可变对象作为 key 踩坑](https://icharle.com/hashmapkebianobj.html)

[聊聊并发（七）——Java中的阻塞队列](http://ifeve.com/java-blocking-queue/)

[深入研究java.lang.Object类](http://lavasoft.blog.51cto.com/62575/15456/)

[Java ArrayList、LinkedList、Vector的区别](https://blog.csdn.net/zhangqiluGrubby/article/details/72870493)

[HashMap和Hashtable的区别](https://blog.csdn.net/u010983881/article/details/49762595)

[HashMap、TreeMap、HashTable区别](https://blog.csdn.net/Jason847/article/details/78050358)

[你想知道的HashMap](https://skyacer.github.io/2018/05/06/%E4%BD%A0%E6%83%B3%E7%9F%A5%E9%81%93%E7%9A%84HashMap/)

[ConcurrentHashMap总结](https://my.oschina.net/hosee/blog/675884?spm=a2c4e.10696291.0.0.374719a4XfiYcR)

[Java 8系列之重新认识HashMap](https://tech.meituan.com/2016/06/24/java-hashmap.html)

[HashMap多线程死循环问题](http://blog.csdn.net/xuefeng0707/article/details/40797085)

[深入分析Volatile的实现原理](https://www.infoq.cn/article/ftf-java-volatile)

[Java并发编程：Synchronized及其实现原理](https://www.cnblogs.com/paddix/p/5367116.html)

[Java反射在JVM的实现](https://blog.csdn.net/jim__charles/article/details/52815318)

[Unsafe 与 CAS](https://www.cnblogs.com/xrq730/p/4976007.html)

[Java魔法类：Unsafe应用解析](https://tech.meituan.com/2019/02/14/talk-about-java-magic-class-unsafe.html)

[Java AtomicInteger原理分析](https://fangjian0423.github.io/2016/03/16/java-AtomicInteger-analysis/)

[Java并发编程：CountDownLatch、CyclicBarrier和Semaphore](https://www.cnblogs.com/dolphin0520/p/3920397.html)

[理解ReentrantLock的公平锁和非公平锁](https://www.jianshu.com/p/2ada27eee90b)

[Java面试必问-死锁终极篇](https://juejin.im/post/5aaf6ee76fb9a028d3753534)

[深入理解读写锁ReentrantReadWriteLock](https://www.jianshu.com/p/4a624281235e)

[CountDownLatch详解](https://www.jianshu.com/p/128476015902)

[深入理解final关键字的作用](http://medesqure.top/2018/08/30/final/)

[Java CAS 和ABA问题](https://www.cnblogs.com/549294286/p/3766717.html)

[关于JAVA中的Class.cast方法](https://blog.csdn.net/axzsd/article/details/79206172)

[如何正确地写出单例模式](http://wuchong.me/blog/2014/08/28/how-to-correctly-write-singleton-pattern/)

[【Java】try-catch-finally语句中return的执行顺序思考](https://itimetraveler.github.io/2017/09/20/%E3%80%90Java%E3%80%91try-catch-finally%E8%AF%AD%E5%8F%A5%E4%B8%ADreturn%E7%9A%84%E6%89%A7%E8%A1%8C%E9%A1%BA%E5%BA%8F%E6%80%9D%E8%80%83/)

[二分查找法的实现和应用汇总](https://www.cnblogs.com/ider/archive/2012/04/01/binary_search.html)

[二叉树遍历(先序、中序、后序)](https://www.jianshu.com/p/456af5480cee)

[Java最小堆解决TopK问题](http://blog.csdn.net/xiao__gui/article/details/8687982)

<h3  id="4">Kotlin 相关</h3>

[from-java-to-kotlin](https://github.com/MindorksOpenSource/from-java-to-kotlin/blob/master/README-ZH.md)

[kotlin_tips](https://github.com/heimashi/kotlin_tips)

[从原理分析Kotlin的延迟初始化: lateinit var和by lazy](https://juejin.im/post/5affc369f265da0b9b079629)

[使用Kotlin Reified 让泛型更简单安全](https://droidyue.com/blog/2019/07/28/kotlin-reified-generics/)

[Kotlin里的Extension Functions实现原理分析](http://hengyunabc.github.io/kotlin-extension-functions/)

[Kotlin系列之顶层函数和属性](https://blog.csdn.net/bingjianIT/article/details/79134670)

[Kotlin 兼容 Java 遇到的最大的 “坑”](https://juejin.im/entry/58e19fd12f301e006214b88c)

[Kotlin 的协程用力瞥一眼](https://kaixue.io/kotlin-coroutines-1/)

[Kotlin 协程「挂起」的本质](https://kaixue.io/kotlin-coroutines-2/)

[到底什么是「非阻塞式」挂起？协程真的更轻量级吗？](https://kaixue.io/kotlin-coroutines-3/)

[资源混淆是如何影响到Kotlin协程的](https://juejin.im/post/5cf0dc58f265da1b9612ea89)

[Kotlin Coroutines(协程) 完全解析](https://johnnyshieh.me/posts/kotlin-coroutine-introduction/)

[破解 Kotlin 协程](https://www.bennyhuo.com/2019/04/01/basic-coroutines/)

<h3  id="5">网络相关</h3>

[深度解析HTTPS原理](https://blog.csdn.net/zhongzh86/article/details/69389967)

[HTTPS 原理浅析及其在 Android 中的使用](https://cloud.tencent.com/developer/article/1005073)

[HTTP 断点续传（分块传输）](https://blog.csdn.net/liang19890820/article/details/53215087)

[HttpDns 原理是什么](http://www.linkedkeeper.com/171.html)

[《客厅TV-APP HttpDNS技术接入与实战》](https://mp.weixin.qq.com/s/BVF24W6pyfhtoZo9cTbtpA)

[HttpDns接入以及全局替换的实现](https://juejin.im/post/5b8a1c31f265da436d7e5874)

[happy-dns-android](https://github.com/qiniu/happy-dns-android)

[TCP、UDP、HTTP、SOCKET之间的区别](https://blog.csdn.net/magister_feng/article/details/8634518)

[一文搞懂TCP与UDP的区别](https://blog.fundebug.com/2019/03/22/differences-of-tcp-and-udp/)

[Android直播开发之旅(7)：Android视频直播核心技术(架构)详解](https://blog.csdn.net/AndrExpert/article/details/76919535)

[Android最佳实践——深入浅出WebSocket协议](https://blog.csdn.net/sbsujjbcy/article/details/52839540)

[拆轮子系列：拆 Okio](https://blog.piasy.com/2016/08/04/Understand-Okio/index.html)

[拆轮子系列：拆 OkHttp](https://blog.piasy.com/2016/07/11/Understand-OkHttp/index.html)

[Android Volley完全解析(四)，带你从源码的角度理解Volley](http://blog.csdn.net/guolin_blog/article/details/17656437)

<h3  id="6">插件化</h3>

[Android插件化库比较](https://blog.csdn.net/u013435893/article/details/78972782)

[深入理解Android插件化技术](https://zhuanlan.zhihu.com/p/33017826)

[Android 插件化 -- ClassLoader 源码分析](https://www.heqiangfly.com/2017/05/18/android-plugins-dynamic-load-source-code-analysis/)

[Android热补丁之Tinker原理解析](http://w4lle.com/2016/12/16/tinker/index.html)

[Android插件化原理解析——Hook机制之动态代理](http://weishu.me/2016/01/28/understand-plugin-framework-proxy-hook/)

[Android 动态代理与Hook机制详解](https://blog.csdn.net/csdn_aiyang/article/details/79085039)

[MultiDex工作原理分析和优化方案](https://zhuanlan.zhihu.com/p/24305296)

[Android 一种在Dalvik虚拟机上多Dex加载优化的方案](https://blog.csdn.net/sbsujjbcy/article/details/53381663)

[Android 8.0 中的 ART 功能改进](https://source.android.google.cn/devices/tech/dalvik/improvements?hl=zh-cn)

[DEX、ODEX、OAT文件&Dalvik和ART虚拟机](https://www.cnblogs.com/genggeng/p/9810311.html)

[art dex2oat 加载加速浅析](https://fucknmb.com/2018/12/30/art-dex2oat%E5%8A%A0%E8%BD%BD%E5%8A%A0%E9%80%9F%E6%B5%85%E6%9E%90/)

[剖析 Android ART Runtime (1) - 背景知识](https://mssun.me/blog/android-art-runtime-1-background.html)

[剖析 Android ART Runtime (2) – dex2oat](https://mssun.me/blog/android-art-runtime-2-dex2oat.html)

[剖析 Android ART Runtime (3) – Compilerb](https://mssun.me/blog/android-art-runtime-3-compiler.html)

[Android ART运行时无缝替换Dalvik虚拟机的过程分析](https://blog.csdn.net/luoshengyang/article/details/18006645)

[入门ART虚拟机(1)——加载DEX文件](https://www.jianshu.com/p/20dcfcf27004)

[入门ART虚拟机(5)——OAT文件](https://www.jianshu.com/p/e0929379cdc3)

[Android运行时ART加载OAT文件的过程分析](https://blog.csdn.net/Luoshengyang/article/details/39307813)

[Android App Bundle 构建流程浅析](https://fucknmb.com/2018/05/25/Android-App-Bundle%E6%9E%84%E5%BB%BA%E6%B5%81%E7%A8%8B%E6%B5%85%E6%9E%90/)

[系统级插件化？Google全新的动态化框架Android App Bundles分析](https://zhuanlan.zhihu.com/p/36902641)

[深入解读Android新特性——App Bundles](https://yq.aliyun.com/articles/600909)

[基于Android App Bundle的动态化方案探索](https://myslide.cn/slides/21232)

[Qigsaw - dynamic modularization library](https://github.com/iqiyi/Qigsaw)

<h3  id="7">图片相关</h3>

[Fresco图片框架内部实现原理探索](http://blog.csdn.net/u010687392/article/details/50266633)

[彻底弄懂 GLIDE V4 之宏观原理分析](http://yinshudi.com/2019/01/03/%E5%BD%BB%E5%BA%95%E5%BC%84%E6%87%82%20Glide%20v4%20%E4%B9%8B%E5%AE%8F%E8%A7%82%E5%8E%9F%E7%90%86%E5%88%86%E6%9E%90/)

[WebP原理和Android支持现状介绍](https://zhuanlan.zhihu.com/p/23648251)

[浓缩的才是精华：浅析 GIF 格式图片的存储和压缩](https://cloud.tencent.com/developer/article/1004763)

[高效加载大型位图](https://developer.android.com/topic/performance/graphics/load-bitmap)

[Android 高清加载巨图方案 拒绝压缩图片](https://blog.csdn.net/lmj623565791/article/details/49300989)

[Lottie 动画原理剖析](http://ivanfan.site/2018/07/01/Lottie%E5%8A%A8%E7%94%BB/)

[SVGA 背后的故事](https://www.jianshu.com/p/dfa16d9d67cd)

<h3  id="8">Gradle 相关</h3>

[Android Gradle Plugin 源码分析](https://www.jianshu.com/p/cb0e085c466f)

[Android Gradle Plugin 源码阅读与编译](https://fucknmb.com/2017/06/01/Android-Gradle-Plugin%E6%BA%90%E7%A0%81%E9%98%85%E8%AF%BB%E4%B8%8E%E7%BC%96%E8%AF%91/)

[Improving Android Build Performance](https://www.droidcon.com/media-detail?video=352688995)

[Using Gradle's Worker API to reduce build time](https://guides.gradle.org/using-the-worker-api/)

[Gradle 学习之 Android 插件的 Transform API](https://juejin.im/post/5ccd41066fb9a03204595a91)

[Android AOP三剑客之AspectJ](https://www.jianshu.com/p/d43807ac33bd)

[Android AOP三剑客之APT](https://www.jianshu.com/p/e66e8926c01d)

[Android AOP三剑客之Javassist](https://www.jianshu.com/p/dfc4681f8090)

[Chapter-ASM - Android 开发高手课](https://github.com/AndroidAdvanceWithGeektime/Chapter-ASM)

[matrix-gradle-plugin - matrix](https://github.com/Tencent/matrix/tree/master/matrix/matrix-android/matrix-gradle-plugin)

[Android Lint增量扫描实战纪要](https://www.jianshu.com/p/4833a79e9396)

[便于性能分析的日志框架hugo](https://github.com/JakeWharton/hugo)

[WMRouter：美团外卖Android开源路由框架](https://tech.meituan.com/2018/08/23/meituan-waimai-android-open-source-routing-framework.html)

[ARouter - Android App 进行组件化改造的路由框架](https://github.com/alibaba/ARouter)

[滴滴开源 Booster：移动APP质量优化框架](https://blog.csdn.net/singwhatiwanna/article/details/90630200)

<h3  id="9">Flutter 相关</h3>

[Flutter原理与实践](https://tech.meituan.com/2018/08/09/waimai-flutter-practice.html)

[揭秘Flutter Hot Reload（原理篇）](https://juejin.im/post/5bc80ef7f265da0a857aa924)

[Flutter 动态化探索](https://fucknmb.com/2019/03/22/Flutter-%E5%8A%A8%E6%80%81%E5%8C%96%E6%8E%A2%E7%B4%A2/)

[Flutter如何和Native通信-Android视角](https://juejin.im/post/5b4c3c9a5188251ac446d915)

[深入理解Flutter Platform Channel](https://juejin.im/post/5b84ff6a6fb9a019f47d1cc9)

[Flutter Engine 编译指北](https://fucknmb.com/2019/02/26/Flutter-Engine-%E7%BC%96%E8%AF%91%E6%8C%87%E5%8C%97/)

[Flutter Engine 线程模型](https://zhuanlan.zhihu.com/p/64034467)

[深入理解Flutter多线程](https://www.jianshu.com/p/54da18ed1a9e)

[Flutter状态管理 - 初探与总结](https://juejin.im/post/5cd91bb0f265da034e7eaca3)

[Flutter | 状态管理指南篇——Provider](https://juejin.im/post/5d00a84fe51d455a2f22023f)

[深入理解Flutter应用启动](http://gityuan.com/2019/06/29/flutter_run_app/)

[Flutter渲染机制—UI线程](http://gityuan.com/2019/06/15/flutter_ui_draw/)

[Flutter渲染机制—GPU线程](http://gityuan.com/2019/06/16/flutter_gpu_draw/)

[深入理解Flutter应用启动](http://gityuan.com/2019/06/29/flutter_run_app/)

[深入理解setState更新机制](http://gityuan.com/2019/07/06/flutter_set_state/)

[深入理解Flutter消息机制](http://gityuan.com/2019/07/20/flutter_message_loop/)

[深入理解Flutter动画原理](http://gityuan.com/2019/07/13/flutter_animator/)

[Dart虚拟机运行原理](http://gityuan.com/2019/10/05/dart_vm/)

[源码解读Flutter tools机制](http://gityuan.com/2019/09/01/flutter_tool/)

[源码解读Flutter run机制](http://gityuan.com/2019/09/07/flutter_run/)

[Fultter App 国际化/多语言](https://github.com/Sky24n/fluintl)

[Flutter豆瓣客户端](https://github.com/kaina404/FlutterDouBan)  

