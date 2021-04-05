Change Log
==========

Version 1.0.8 *(2021-04-05)*
----------------------------

* 从 JCenter 迁移到 JitPack

Version 1.0.7 *(2019-10-15)*
----------------------------

* fix #7 ArrowDrawable设置阴影，箭头无法居中

Version 1.0.6 *(2019-9-17)*
----------------------------

* fix #5 支持非 AndroidX

Version 1.0.5 *(2019-9-5)*
----------------------------

* TransformersTip 新增 setDismissOnTouchOutside 方法，设置点击浮窗外部时是否自动关闭浮窗
* SimpleTextTip 新增 setTextGravity 方法，设置文字对其方式
* SimpleTextTip 新增 setLineSpacingMultiplier、setLineSpacingExtraDp、setLineSpacingExtraRes 方法，设置行间距

Version 1.0.4 *(2019-9-1)*
----------------------------

* 不直接对外暴露 ArrowDrawable，而是通过 TransformersTip 来设置
* 新增 SimpleTextTip，适用于只有文字的浮窗，不用再写布局文件了

Version 1.0.3 *(2019-8-31)*
----------------------------

* 优化 TransformersTipLinearLayout 和 TransformersTipRelativeLayout 在布局文件中的预览效果，提升开发效率

Version 1.0.2 *(2019-8-31)*
----------------------------

* fix #2，新增四周阴影功能
  * ad_shadowSize 设置阴影宽度
  * ad_shadowColor 设置阴影颜色
  * ArrowDrawable 新增 setShadowSizeDp 和 setShadowSizeRes 方法设置阴影宽度 
  * ArrowDrawable 新增 setShadowColor 和 setShadowColorRes 方法设置阴影颜色
* 之前的背景色属性名 ad_background 改为 ad_bgColor

Version 1.0.1 *(2019-8-22)*
----------------------------

* TransformersTip 新增 setBackgroundDimEnabled 方法，设置是否允许浮窗的背景变暗

Version 1.0.0 *(2019-8-21)*
----------------------------

* Initial release