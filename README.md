涂鸦sdk This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices. For more information, please check Tuya Developer Website.

一、方案标题

宠物自动喂食饮水机

二、方案应用

需求：
宠物主人平时需要上班，偶尔经常出远门，喂养宠物不方便，宠物在自由采食的情况下不能自己控制采食量。同时也有一些极端情况，比如在20年初新冠疫情爆发，导致很多家有宠物人由于突发隔离而不能喂养宠物，宠物只能在家被饿死而宠物主人无能为力的情况。 

场景地点：室内；

功能：

1.实体按键按压手动投送食物，如果时间足够加，增加APDS_9960手势感应模块，隔空控制进行食物投送；

2.APP上可以单次快速投送；

3.称重模块检测食物余量；上传APP,利用APP功能定制计划，一天投送几次，一次投送多少，也可以根据自己的行程计划在APP上修改计划；

4.12V减速电机控制食物投送,12V电磁阀控制饮水，市面上都只有干粮，进行了创新;

5.两种供电方式：12V适配器以及锂电池，断电断网也正常喂食，饮水。通过涂鸦平台的方案功能点，可以周期性进行食物投送，最多可以持续两周，低功耗设计；



三、开发计划

1）3月12前准备物料：  1.现有：stm32电路板；
                      2.涂鸦赠送或自行购买：三明治开发套件（语音开发板、电源、直流电流电机驱动模块）；                  
                      3.淘宝购买：亚克力板定制，12V直流电机模块（带减速）,12V电磁阀,装水容器，水管等；

2）3月12-25日用自己现有的stm32电路板进行嵌入式开发，以及连接涂鸦wifi模块，添加涂鸦SDK上云

3）3月31日前整体调试
