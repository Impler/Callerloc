# CallerlocChina.json 中国大陆手机号码归属地库

##示例
| 号码段   | 省份  |  城市  |地区代码(区号) |邮政编号(邮编) |运营商 |
| -------- | ----- | ---- 	|----           |----           |----   |
| 1300000  | 山东  | 济南市 |0531           |250000         |联通   |
| 1300001  | 江苏  | 常州市 |0519           |213000         |联通   |
| 1300002  | 安徽  | 巢湖市 |0565           |238000         |联通   |
| 1300006  | 江苏  | 南京市 |025            |210000         |联通   |

##更新
* 2016-06-01 343198条记录
* 2016-05-15 335588条记录
* 2016-04-15 335169条记录
* 2016-03-24 334447条记录
* 2016-03-01 331878条记录
* 2016-02-01 329833条记录


# CarrierChina 中国大陆手机号码运营商库
中国大陆手机号正则
```
^((13[0-9])|(14[5,7])|(15[^4,\\D])|(17[6-8])|(18[0-9]))\\d{8}$
```

##示例
| 分类     | MDN结构            |  国家代码 |MAC|
| -------- | -----:             | ----:  	|----:  |
| 中国移动 | 2G(GSM网络)        | 86 		|134x(0-8),135,136,137,138,139,150,151,152,158,159,182,183,184|
|          | 3G(TD-SCDMA网络)   | 86 		|157,187,188|
|          | 3G上网卡           | 86 		|147  |
|          | 4G  	            | 86 		|178|
|          | 虚拟运营商专属号段 | 86 		|1705|
|中国联通  | 2G(GSM网络)        | 86 		|130,131,132,155,156 |
|          | 3G(WCDMA网络)     	| 86 		|185,186 |
|          | 3G上网卡           | 86 		|145 |
|          | 4G  	            | 86 		|176,185|
|          | 虚拟运营商专属号段	| 86 		|1709|
| 中国电信 | 2G/3G(CDMA2000网络)| 86 		|133,153,180,181,189 |
|          | 3G上网卡	        | 86 		| |
|          | 4G	                | 86 		|177 |
|          | 虚拟运营商专属号段	| 86 		|1700 |
| 卫星通信 | 	                |  			|1349 |


# Zone 全球国家代码库

##示例
| 国家代码 | 英文名  |  中文名  |domain |timezone |rule(号码规则) |中文拼音|
| -------- | ----- | ---- 	|----           |----           |----   |----   |
| 1        | United States of America  | 美国 |US  |-13 |^\\d+   |meiguo |
| 1242     | Bahamas  | 巴哈马 |BS  |-13 |^\\d+   |bahama |
| 1264     | Anguilla  | 安圭拉岛 |AI  |-12 |^\\d+   |anguiladao |

##更新
* 2016-02-01 206条记录
