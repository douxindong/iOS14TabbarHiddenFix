# iOS14TabbarHiddenFix
解决iOS14下pop多层控制器至主页时，tabbar不显示问题

Demo运行过程：
  点击红色页面时会push至黄色页面，停留3s后又push黄色页面，持续3次，待不再push时，点击pop页面会进行popToRoot操作，可以看到tabbar并未被隐藏；
Demo中主要文件TianMuiOS14BugFix，拖拽至项目中即可，就不做cocoapods了