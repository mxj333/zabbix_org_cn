zabbix中文简体语言包
============

ZABBIX中文简体的汉化语言包

安装方法：

1、修改 include/ locales.inc.php 文件里面的：

'zh_CN' => array('name' => _('Chinese (zh_CN)'),        'display' => false),
为
'zh_CN' => array('name' => _('Chinese (zh_CN)'),        'display' => true),

2、进入用户配置界面，选择zh_CN即可。

更多内容请前往[zabbix-web 没有“中文”语言] (http://zabbix.org.cn/viewtopic.php?f=13&t=178)

由[ZABBIX中文社区](http://www.zabbix.org.cn)整理翻译

============

基于zabbix2.4进行的翻译

详细信息请参阅 [zabbix](http://www.zabbix.com)

zabbix在线文档：http://www.zabbix.com/documentation/2.0/manual/installation/install