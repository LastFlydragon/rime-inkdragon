**龙象方案：** 
本方案为万象双拼和魔龙墨奇版合并后的增强版
最强双拼(乱序加四声音调)配上最强辅码,只要学会并炼成此绝世内功,输入速度会不可限量!

### 龙象音形
#### 使用万象双拼的方案引擎, 词库使用了魔龙墨奇版的自然龙码词库, 用词频进行了优化, 并加上了ac造词等万象和魔龙没有的功能

#### 使用方法：

###### 安装rime平台

###### 设置好之后,找到用户目录,把龙象的zip包解压到用户目录里去
保存后部署方案即可！
开启了＂，＂和＂．＂键翻页候选字，完全是个人习惯。
其实用了龙码和墨奇，候选字就应该不用翻页啦
我基本上只用2选和3选, 用";"和","按钮

    **其它亮点功能**

     **日期时间：** 
      输入：`date        time   week    datetime                   timestamp`
    
      得到：` 2024-07-04  19:37  星期四  2024-07-04T19:38:47+08:00  1720093174`
     **农历：**  lunar 获得当前日期的农历值
     **Unicode：**  大写 U 开头，如 U62fc 得到「拼」。
     **数字、金额大写：**  大写 R 开头，如 R1234 得到「一千二百三十四、壹仟贰佰叁拾肆元整」。
     **农历指定日期：**  大写 N 开头，如 N20240210 得到「二〇二四年正月初一」。
      **/模式：**  通过输入 /sx 快捷输入关于“数学”的特殊符号，具体能输入什么可以打开 symbols.yaml学习。
     **计算器：**  通过输入大写V引导继续输入如：V3+5  候选框就会有8和3+5=8，基础功能 `+ - * / % ^` 还支持 `sin(x) cos(x)` 等众多运算方式 [点击全面学习](https://github.com/gaboolic/rime-shuangpin-fuzhuma/blob/main/md/calc.md)
    * **自动上屏：**  例如：三位、四位简码唯一时，自动上屏如`jjkw岌岌可危` `zmhu怎么回事` 。默认未开启，方案文件中`speller:`字段下取消注释这两句开启 `#  auto_select: true  #  auto_select_pattern: ^[a-z]+/|^[a-df-zA-DF-Z]\w{3}|^e\w{4}`
     **快符：** 例如 ```'q``` 通过单引号键引导的26字母快速符号自动上屏，双击''重复上一个符号；
     **辅助码提示：** 任意长度候选词的辅助码提示能力，默认开启1个字的辅助码，Ctrl+a开启和关闭辅助码，Ctrl+p墨奇专属拆字辅助，Ctrl+z自然码拆分辅助，这些都是共用配置可在开关中按自己需求配置，保留一个；
     **音调显示：** 在辅助码配置中有tone这一参数，可以将音调拼音显示到注释里，通过Ctrl+s可以使得输入码显示全拼并加音调；
     **用户词删除：** 不管什么删除都不能直接作用于固定词典，使用Ctrl+del是rime系统删除用户词，基于lua的实现：对选中的候选词操作，使用Ctrl+d 删除，Ctrl+x隐藏，Ctrl+j降低词频，删除的词都在lua下文件中记录，你可以清空重新部署恢复，也可以根据列出去清除固定词典的编码，从而持续迭代。
     **Tab循环切换音节：**  当输入多个字词时想要给前面补充辅助码，可以多次按下tab循环切换，这种可能比那些复杂的快捷键好用一些；
     **翻译模式：**  输入状态按下Ctrl+E快捷键进入翻译模式，原理是opencc查表进行中英文互译，能否翻译取决于词表的丰富度；
     **反查：** 支持oh引导状态下的虎码反查。
     更多功能可以编辑方案文件依据注释说明开启


- 主要配置文件:
  - schema: longxiang # 龙象

### [FAQ]<[安装简要指南](https://github.com/LastFlydragon/rime-moqi-huma/blob/main/docs/INSTALL.md)>
（常见问题请参考墨奇音形的[文档](https://github.com/gaboolic/rime-shuangpin-fuzhuma/blob/main/md/FAQ.md)
或加入ＱＱ群讨论）q羣696353204

### 鸣谢
[万象基础版本](https://github.com/amzxyz/rime_feisheng_dict)
[墨奇音形](https://github.com/gaboolic/rime-shuangpin-fuzhuma)
[魔龙](https://github.com/jack2game/rime-molong)

### 更新日志
[更新日志]<https://github.com/LastFlydragon/rime-inkdragon/blob/main/docs/update-log.md>


5. **墨奇音形:**

    墨奇音形是一个基于一种新型开源的字形描述信息、递归拆分至最小字形，最后取首末双形音托的方案。查墨奇码的拆分：加群696353204 ②群10885687 输入“墨奇码拆 想拆的字”。支持4万字

   [拆分规则](https://github.com/gaboolic/rime-shuangpin-fuzhuma/wiki/%E5%A2%A8%E5%A5%87%E7%A0%81%E6%8B%86%E5%88%86%E8%A7%84%E5%88%99)[](https://github.com/gaboolic/rime-shuangpin-fuzhuma/wiki/%E5%A2%A8%E5%A5%87%E7%A0%81%E6%8B%86%E5%88%86%E8%A7%84%E5%88%99)

