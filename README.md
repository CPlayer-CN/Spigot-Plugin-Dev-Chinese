翻译时间 2018年1月29日21:35:38 - 2018年1月29日21:59:05  
原文链接 https://www.spigotmc.org/wiki/spigot-plugin-development

# Spigot 插件开发

这部分仅针对Spigot开发人员。本指南假定读者在 Minecraft 中没有以前的修改(modding)经验。因此, 指南可以/应该以渐进的顺序读取。拥有丰富游戏经验的，可以忽略某些部分。在适用的情况下，将展示每个指南的Eclipse和IntelliJ版本。

**向导**
- ~~[Java速成](https://github.com/PChenWillPlay/Spigot-Plugin-Development-Chinese/blob/master/crash-course-to-java.md)~~
- 创建一个空白插件(Eclipse | IntelliJ | NetBeans |...)
- 创建离线Javadoc（可选）
- 创建并注册一个基础命令
- 使用事件API
- 创建一个配置文件
- 使用Eclipse进行插件调试
- 使用IntelliJ IDEA进行插件调试
- NoSQL / MongoDB与你的插件集成
- 带有Morphia的MongoDB（简易数据库存储）
- MySQL数据库与你的插件集成
- plugin.yml

**资源**
- [Spigot API](https://hub.spigotmc.org/stash/projects/SPIGOT)
- [Spigot Javadoc](https://hub.spigotmc.org/javadocs/spigot/)
---
# Spigot Plugin Development

This section is dedicated to Spigot plugin developers. This guide assumes that the reader has no prior modding experience in Minecraft. Hence, the guides can/should be read in a progressive order. Experienced modders, feel free to skip ahead. Where applicable, Eclipse and IntelliJ version of each guide is shown.

**Guides**
- [Crash Course to Java](https://www.spigotmc.org/wiki/crash-course-to-java/)
- Creating a blank plugin ([Eclipse ](http://www.spigotmc.org/wiki/creating-a-blank-spigot-plugin-in-eclipse/?noRedirect=1)| [IntelliJ](http://www.spigotmc.org/wiki/creating-a-blank-spigot-plugin-in-intellijidea/) | [NetBeans](https://www.spigotmc.org/wiki/creating-a-blank-spigot-plugin-in-netbeans/) |...)
- [Creating offline Javadoc](https://www.spigotmc.org/wiki/creating-offline-javadoc-for-the-spigot-api/) (optional)
- [Create and register a basic command](https://www.spigotmc.org/wiki/create-a-simple-command/)
- [Using the Event API](http://www.spigotmc.org/wiki/using-the-event-api/?noRedirect=1)
- [Creating a Config File](http://www.spigotmc.org/wiki/creating-a-config-file/)
- [Plugin debug with Eclipse](http://www.spigotmc.org/wiki/eclipse-debug-your-plugin/?noRedirect=1)
- [IntelliJ IDEA Plugin Debug](https://www.spigotmc.org/wiki/intellij-debug-your-plugin/)
- [NoSQL/MongoDB integration with your plugin](http://www.spigotmc.org/wiki/using-mongodb/)
- [MongoDB with Morphia](https://www.spigotmc.org/wiki/mongodb-with-morphia/) (Easy Database Storage)
- [MySQL database integration with your plugin](http://www.spigotmc.org/wiki/mysql-database-integration-with-your-plugin/)
- [Plugin.yml](https://www.spigotmc.org/wiki/plugin-yml/)

**Resources**
- [Spigot API](https://hub.spigotmc.org/stash/projects/SPIGOT)
- [Spigot Javadoc](https://hub.spigotmc.org/javadocs/spigot/)
