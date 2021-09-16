# cpvm
cpvm = core package version monitor

### 动机
vue3 and vue3 ecosystem is update too fast now, watch the version of dev code.  
可能不经常看都想不起来是不是要看看哪些包有重点更新，比如 echarts 都到 5 了


常见核心包版本监控程序 (定期打开看一看？)

- 用 github 的 watch 又有点太琐碎，mailing list太分散，而且有些包不一定有
- 使用`jsdelivr`的接口 **Thanks**，npm官方直接调用有跨域问题，专门做一个node的实现又不够轻量
- 尽量查看 changelog 在更新版本号，生产环境还是要以稳定为准，而不是随便`npm upgrade`
- **todo**  整理 release link 的链接看看都修改了啥
- 如果有个人网址导航 直接把这个页面加到网址导航本地打开也是可以的
