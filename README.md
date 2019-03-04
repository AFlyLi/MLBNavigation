# MLBNavigation

[![Version](https://img.shields.io/cocoapods/v/MLBNavigation.svg?style=flat)](https://cocoapods.org/pods/MLBNavigation)
[![License](https://img.shields.io/cocoapods/l/MLBNavigation.svg?style=flat)](https://cocoapods.org/pods/MLBNavigation)
[![Platform](https://img.shields.io/cocoapods/p/MLBNavigation.svg?style=flat)](https://cocoapods.org/pods/MLBNavigation)  

为什么要做这个？  
平时使用原生导航栏，处理返回手势的时候，自己做不到像QQ那样处理的很完美，所以做这个，很简单，需要的参考，大神绕道。

## 示例

![Image text](https://github.com/longmaboy/MLBNavigation/blob/master/Example/111.gif)

## 安装

下载demo，将MLBNavigation拖入项目中即可，或者cocopods安装。  
pod search MLBNavigation 搜索不到，请先更新pod setup

```ruby
pod 'MLBNavigation'
```

## 使用方法

支持StoryBoard和纯代码使用  
创建UIViewController的时候，直接继承MLBBaseController.h即可，详情可看demo  
最好是自己创建一个BaseController继承我的的MLBBaseController，然后BaseController还可以做你想做的事情  
若是你的导航栏很复杂，那直接隐藏导航栏，自己做一个导航栏就好。

## 注意事项
因为原生导航栏被隐藏了，所以原生导航栏上的功能不能再使用，需要自己去实现  
1、prefersLargeTitles大标题功能没法使用  
2、UISearchController
 
## Author

使用过程中有任何问题，请issue我或者给我发邮件  
751824643@qq.com

## License

MLBNavigation is available under the MIT license. See the LICENSE file for more info.
