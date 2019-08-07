GBA.js
======
**版本 1.1-git — 版权所有 © 2012 – 2013 Jeffrey Pfau**
  转自原作者。
 GBA.js是一个从头开始编写的Game Boy Advance模拟器，它采用了Canvas和Web Audio等HTML5技术。它不使用插件，旨在在最先进的Web浏览器上运行。它[在GitHub](https://github.com/endrift/gbajs) 上托管，并根据2条款BSD许可提供。最新版本在 [http://endrift.github.io/gbajs/】(http://endrift.github.io/gbajs/)

## 浏览器兼容性
   已知目前版本的GBA.js可以在以下Web浏览器上使用
* Safari 6.0 或更新版本
* Chrome 22 或更新版本
* Firefox 25 或更新版本 (慢)

以下web浏览器也可使用, 但会降低功能（你可以自己试一试）:

* Firefox 15 或更新版本(无声音，运行缓慢)
* Opera 12.1x  或更新版本(无声音，运行缓慢)
* Internet Explorer 10  或更新版本(无声音，运行缓慢, 像素化显示不起作用)
* Chrome 20, 21 (像素化显示不起作用)

以下浏览器无法使用：:

* Safari 5.1.x 或更老的版本 (没有用于将游戏上传到JavaScript的文件API)
* Firefox 14  或更老的版本(没有DataView，用于内存)
* Internet Explorer 9 or older

所有其他浏览器都未经过测试。

## GBA兼容性
有关经过测试的游戏列表，请参阅[GitHub wiki上的兼容性列表](https://github.com/endrift/gbajs/wiki/Compatibility-List)   请注意，GBA.js针对商业游戏进行了调整，目前缺乏对自制游戏的良好支持。

## 功能列表
目前，Game Boy Advance硬件的每个部分，除了一些较少使用的功能和链接电缆都实现。
模拟器还具有以下功能：

* 可下载和上传的存档游戏
* 截图
* 暂停模拟
* 支持包含实时时钟的游戏包(例如口袋妖怪红宝石和蓝宝石)

将来可能实施的功能包括：
* Savestates
* 可重映射的控件
* 游戏手柄支持
* Link cable over Web Sockets
* 作弊码支持（老金一时爽，存档火葬场）
* 全屏支持
* 支持具有其他传感器的游戏(e.g. WarioWare Twisted!, Boktai)

## License
Copyright © 2012 – 2013, Jeffrey Pfau
All rights reserved.

如果满足以下条件，则允许以源代码和二进制形式重新分发和使用（无论是否进行修改）：

* 源代码的重新分发必须保留上述版权声明，此条件列表和以下免责声明。

* 二进制形式的再分发必须在随分发提供的文档和/或其他材料中复制上述版权声明
  此条件列表和以下免责声明。
<b>本软件由版权所有者和贡献者按“原样”提供，并且不承担任何明示或暗示的保证，
包括但不限于对适销性和特定用途的适用性的暗示保证。 在任何情况下，
版权所有者或贡献者均不对任何直接，间接，偶然，特殊，惩戒或后果性损害承担责任
（包括但不限于采购替代商品或服务;损失使用，数据或利润; 或者商业中断）
无论如何引起责任和任何责任理论，无论是在使用本软件的任何方式下产生的合同，
严格责任或侵权（包括疏忽或其他），即使被告知此类损害的可能性也是如此。</b>
