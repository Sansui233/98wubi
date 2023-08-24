本仓库为基于 RIME 制作的 [小狼毫-98五笔版](http://98wb.ysepan.com/) 自修改配置，更符合喜欢打词组的用户习惯。具体改动包括但不限于：

- Tab 选择下一个词
- 开启逐码提示
- 关闭多码清屏，方便临时英文单词混输（没关四码唯一自动上屏，只能混输无匹配码的单词，个人经验常用英文单词的重合率一半一半）
- 恢复无词组时按空格编码上屏，一是方便中英混输，二是修正空格确认编码的功能性，删除只由backspace与delete做。三是输入法不应该出现让人感到“输入失效”的行为
- [仿 mac 亮色皮肤](https://github.com/NavisLab/rime-pifu)

![Rime 98Wubi](https://raw.githubusercontent.com/Sansui233/98wubi/master/Rime-98wubi-custom.jpg)

## 计划改动

- zz 特殊符号集（和现有拼音反查冲突。计划拼音反查改zx）

## 使用

此仓库所有文件替换用户文件夹同名文件。注意，替换的为[此页面中的小狼毫-98五笔版](http://98wb.ysepan.com/) ，而非 Rime 原版，否则会有部分文件缺失



## 参考资料

- [Rime Wiki](https://github.com/rime/home/wiki/CustomizationGuide#%E7%A9%BA%E7%A2%BC%E6%99%82%E6%8C%89%E7%A9%BA%E6%A0%BC%E9%8D%B5%E6%B8%85%E7%A9%BA%E8%BC%B8%E5%85%A5%E7%A2%BC)

以下为原仓库对于输入法的功能说明：

===

本档作为 opencc 配置的 schema 样板，永久存档，不再更新。新版配置文件，转部基于 lua 实现。

你可以在 [软件分享](https://github.com/yanhuacuo/98wubi-tables/tree/master/%E8%BE%93%E5%85%A5%E6%B3%95%E8%BD%AF%E4%BB%B6) 里找到相关软件，或者在 [配置分享](https://github.com/yanhuacuo/98wubi-weasel) 中查看新的配置文件。

````````````````````````````````

分界

`````````````````````````````````


### 小狼毫98五笔版部分功能使用展示

#### 一、方案切换

###### 快捷键切换方式：

​	 ***Ctrl + `*** 或 ***F4*** （具体热键看配置设定）

###### 	关键字切换方式：	

​	具体关键字打help看帮助

![功能简介](https://gitee.com/wubi98/weasel-98wb/raw/master/pic/01.png)

#### 二、简繁转换/字集切换/拆分显隐/单字模式/三重注解

###### 	组合热键：

​		Ctrl+Shift+F、Ctrl+Shift+U、Ctrl+Shift+H、	Ctrl+Shift+K、Ctrl+Shift+J（具体热键看配置设定）

![功能简介](https://gitee.com/wubi98/weasel-98wb/raw/master/pic/02.gif)

######	关键字切换：

​		具体关键字打help看帮助

​		效果如下：

![功能简介](https://gitee.com/wubi98/weasel-98wb/raw/master/pic/03-1.png)

![功能简介](https://gitee.com/wubi98/weasel-98wb/raw/master/pic/03-2.png)

![功能简介](https://gitee.com/wubi98/weasel-98wb/raw/master/pic/03-3.png)

#### 三、精准造词

​	效果如下：造好的词上屏后不能回删，否则不记录。造好的词需再次上屏才能转正。

​	删词操作：定位到要删除的词条上面按Shift+Delete删除，此操作只对造词有效！

![功能简介](https://gitee.com/wubi98/weasel-98wb/raw/master/pic/%E7%B2%BE%E5%87%86%E9%80%A0%E8%AF%8D.gif)

#### 四、以形查音

​	效果如下：~引导单字以形查音，「 ~ 键为Shift + ` 」

![功能简介](https://gitee.com/wubi98/weasel-98wb/raw/master/pic/%E4%BB%A5%E5%BD%A2%E6%9F%A5%E9%9F%B3.gif)

#### 五、特殊符号输出

​	实现方式：/引导+符号编码（具体符号编码请查看symbols.yaml文件或开启小狼毫助手打字界面输入//查看指引。

​	效果如下：

![功能简介](https://gitee.com/wubi98/weasel-98wb/raw/master/pic/%E7%AC%A6%E5%8F%B7.gif)

#### 六、农历节气输出

​		具体关键字打help看帮助

​		效果如下：

![功能简介](https://gitee.com/wubi98/weasel-98wb/raw/master/pic/%E8%8A%82%E6%B0%94.png)

#### 七、公历日期时间

​		具体关键字打help看帮助

​		效果如下：

![功能简介](https://gitee.com/wubi98/weasel-98wb/raw/master/pic/%E6%97%B6%E9%97%B4.png)

#### 八、拼音反查编码

​		具体关键字打help看帮助

​		效果如下：

![功能简介](https://gitee.com/wubi98/weasel-98wb/raw/master/pic/%E6%8B%BC%E9%9F%B30.gif)

#### 九、金额转换｜农历公历互转

​		引导方法：任意大写字母开头+数字

​		具体引导打help看帮助（查询转换结果仅供参考）
