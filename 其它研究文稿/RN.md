#### RN

**完成：**RN的调研、RN在Pro中的集成、Pro正在等待审核、RN技术分享

**进行中：**出境界面用RN写一套，预计在8.0.8用Pro提交尝试效果

**待开发：**RN的一整套动态部署流程和风险控制机制:CodePush or自建（8.0.9及以后）

**RN开发职责与流程：**（ react开发、native开发、react打包、react包发布与热更新）

  1、JS这边的职责：

      普通的业务代码的编写

      更新bundle包的提供

  2、Native职责：

    提供js和native之间的通讯、包括一些基础的接口，如获取城市、获取当前网络状态、通知刷新等等

   react-native代码的维护：沙箱模式，安全和风险机制、回退机制等等

   react-native代码的热更新：热更新平台（native端）+服务端具体由服务端搭建平台

   react-native运行机制和深层次原理研究：核心组件的编写和react组件的性能相关

