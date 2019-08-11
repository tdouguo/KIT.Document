---
title: 介绍
---

# 介绍

<a href="https://github.com/KylinTechnologies/Kit/blob/master/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" title="license-mit" /></a> <a href="https://ci.appveyor.com/project/CnTDou/kit"><img src="https://ci.appveyor.com/api/projects/status/tk3o571mwbw2rykj?svg=true" title="Build status"/></a> <a href="https://github.com/KylinTechnologies/Kit/"><img src="https://img.shields.io/badge/version-v1-green.svg" title="GitHub version" ></a> <a href="https://github.com/KylinTechnologies/Kit/releases"><img src="https://img.shields.io/badge/Download-1k-green.svg" title="Downloads" /></a>


Kit for Unity 是Unity3D开发的工具包集合, 集成常见的开发组件以免于重复造轮子。

Kit 设计初衷则是根据业务需求自由组合搭配其中组件, 项目在任何阶段都可以轻松接入。

由多个部分组成Kit, 例: 基础组件、业务服务等。

- 任意基础组件都可抽取到其他项目中使用
- 业务服务基于基础组件扩展(业务服务+依赖基础组件)即可抽取到其他项目中使用.

## 组件简介

- ***对象池(pool)*** [敬请期待]

- ***有限状态机(fsm)*** [敬请期待]

- ***数据(data)*** [敬请期待]

	1. data-table 二维表结构(excle,sqlite)
	2. data-node 节点结构(xml,json)


- ***事件(event)*** [敬请期待] 提供模块之间消息通讯, 以及异步线程之间通讯

- ***网络(net)*** [敬请期待] Socket+Protobuf

	1. net-tcp
		- 提供断线重连、心跳检测、粘包、拆包
		- 扩展协议通讯 protobuf
	2. net-udp
	3. net-kcp
	4. net-http Get、Post请求, 提供自定义请求头,RES非对称加密 等技术处理


- ***Utility*** 工具 

	1. [依赖Unity] 截屏、GPS定位、IO处理、音频转换(AudioClip)、Windows对话框、Misc(WWW请求、图片、UI、Input)等
	2. 时间戳、 数据处理、Misc(string相关处理)等



- ***新手引导(NoviceGuide)*** [敬请期待] 


- ***国际化(i18n)*** [敬请期待]

	- [依赖] Data


- ***流程(process)*** [敬请期待] 控制游戏/App整体流程

- ***实体(entity)*** [敬请期待] 

- ***声音(audio)*** [敬请期待] 

- ***视频(video)*** [敬请期待] 

- ***资源(res)*** [敬请期待] 提供2种加载模式自由切换

	1. AssetBundle 加载资源 AssetBundle.Model (FoxRes(热更新模式),Packet(内嵌在安装包内模式))
		- AssetBundle Editor
	2. Resources 加载资源
	3. res-audioclip 加载网络音频(缓存/不缓存)、加载AB音频、加载Respurces音频、加载Packet内音频
	4. res-sprite 加载网络图片(缓存/不缓存)、加载AB图片、加载Resources图片、加载Packet图片


- ***内嵌Web浏览器(BuiltInWeb)*** [敬请期待] 

- ***热更新(xLua\IRuntime)*** [敬请期待] 


## 技术支持

<!-- QQ群: 633542313 [![](https://pub.idqqimg.com/wpa/images/group.png)](//shang.qq.com/wpa/qunwpa?idkey=1235068de91ee5b340182dfa324f2d118fa586c8dd4053946763172de0f5d580) -->
- E-mail: kevin@kylin.app 
- slack: kylin.slack (敬请期待)


> QQ群禁止水聊，但对技术类提问范围不限制，如：遇到友情链接中的项目的问题也可以直接在群中`@相关作者`。

## 友情链接

#### 热更新方案

- [ILRuntime](https://github.com/Ourpalm/ILRuntime) 项目为基于C#的平台（例如Unity）提供了一个纯C#实现的，快速、方便并且可靠的IL运行时，使得能够在不支持JIT的硬件环境（如iOS）能够实现代码的热更新（`@蓝色幻想`）
- [XLua](https://github.com/Tencent/xLua) 为Unity、 .Net、 Mono等C#环境增加Lua脚本编程的能力，借助xLua，这些Lua代码可以方便的和C#相互调用。（`@John`）


## 优秀的开源框架/项目

- [GameFramework](http://gameframework.cn/) 是一个基于 Unity 5.3+ 引擎的游戏框架，主要对游戏开发过程中常用模块进行了封装，很大程度地规范开发过程、加快开发速度并保证产品质量。（[`@Ellan`](https://github.com/EllanJiang)）
- [ET框架](https://github.com/egametang/ET) 是一个Unity3d客户端+C#分布式服务端框架。使用组件式开发，提供客户端热更，服务端热更功能，提供erlang式分布式消息机制（[`@熊猫`](https://github.com/egametang)）
- [CatLib](https://catlib.io) 是一套渐进式的服务提供者框架。框架为客户端提供多个实现，并把他们从多个实现中解耦出来。服务提供者的改变对它们的客户端是透明的，这样提供了更好的可扩展性。她不仅易于上手，还便于与第三方库或既有项目整合。([`@喵喵`](https://github.com/yb199478)) 
- [BlackFire](https://github.com/BlackFire-Studio/BlackFire) Framework 是专门为了提高中小型企业程序研发团队工作效率和降低中小型企业研发成本而设计的Unity3D游戏开发框架，框架遵循MIT协议，目前还在开发阶段，预计未来框架将友好地面向游戏、三维仿真、VR、AR、Web、区块链等业务开发团队。 ([`@Alan`](https://github.com/0x69h)) 