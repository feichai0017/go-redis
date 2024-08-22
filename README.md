## 项目背景
 - 本项目是用golang写的一个简略版本的redis-server，目的是用来讲解redis核心的技术原理。
 - 没有使用net库、goroutine、channel等golang特色工具。使用unix包的系统调用实现ae事件库，目的是为了复刻redis的设计。
 - ae事件库仅实现了epoll版本，所以只能在linux系统中运行。
 - 项目设计与实现中没有任何稳定性和性能等实用方面的考虑。
 - 目前版本有大量命令和功能没有实现，有兴趣的同学可以参考视频part9自行拓展。

