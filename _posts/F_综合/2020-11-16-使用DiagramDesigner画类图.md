---
layout: post
title: 使用DiagramDesigner画类图
category: 综合
tags: Essay
keywords: 
---


### 类图简要画法

#### 类

类由三个单元格的矩形表示：
第一格：类名称（如果是抽象类，名称标注为斜体字）
第二格：类属性名称
第三格：类操作名称

类属性或者操作的访问修改符的标注：
public用加号标注
private用减号标注
protected用#号标注


#### 接口

接口由两个单元格的矩形表示：
第一格：接口名称（名称前面要加入接口标注<>）
第二格：操作名称


#### 继承关系

继承相当于：is-a
实线+空心三角形表示继承
箭头方向说明：箭头方向由子类指向父类

#### 接口实现关系

实现相当于：has-a
虚线+空心三角形表示实现
箭头方向说明：箭头方向由子类指向接口

#### 依赖关系

依赖相当于：use-a
虚线+箭头表示依赖
箭头方向说明：箭头由类指向被依赖类

#### 关联关系 

关联相当于：always-use-a （强依赖）
实线+箭头表示关联
箭头方向说明：箭头由类指向被关联类

#### 聚合关系

聚合相当于：get together by (甲是由乙聚合成的，甲弱拥有乙)
空心菱形+实线+箭头表示聚合
箭头方向说明：箭头由整体指向部分

#### 组合关系

组合相当于：made up of （甲是由乙组成的，甲强拥有乙）
实心菱形+实线+箭头表示组合
箭头方向说明：箭头由整体指向部分
