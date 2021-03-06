# 引擎加载器	
	AI引擎加载器是通过对网络、日志、数据处理、分发策略、业务逻辑等模块进行统一封装，为AI引擎模型快速上线提供服务的方案。用户通过实现加载器既定插件接口，即可完成AI引擎及模型的快速服务化。
	目前支持文本，音频，图像，视频等数据的交互处理。

## 主要功能
 - 支持多数据类型交互
 - 支持多数据流输入&输出
 - 支持数据管理排序
 - 支持数据编码解码
 - 支持音频数据重采样
 - 支持会话模式&非会话模式
 - 支持实时模式&离线模式

## 插件接口
	见"wrapper/c/wrapper.h"

## 命令行参数
	见"docs/manual/测试调试手册"

## 服务化配置
	见"docs/manual/测试调试手册"

## 构建
	./build.sh
	输出: ./output/AIservice

## 部署依赖
 - ./output
 - python2.7
 - numa

## 体验测试
	见"docs/manual/测试调试手册"