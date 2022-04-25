# laydate
用于年选择器、年月选择器、日期选择器、时间选择器、日期时间选择器等功能<br>
<img src="http://www.wware.org/img/datetime001.png?_684e" width="400px"><br>
普通属性<br>
data-laydateid	设置id号,每个元素在使用前都要设置id.注意id不能重复.	test1<br>
data-laydatevalue	是否设定有限范围内的日期或时间值,如果为true,可以自定义时间限制,该属性是配合设置data-laydatemin/data-laydatemax这两个属性使用,单独使用无效果。	false/true<br>
data-theme	设置主题default（默认简约）、molv（墨绿背景）、#颜色值（自定义颜色背景,例如#393D49）、grid（格子主题）	grid<br>
data-type	year(年选择器,只提供年列表选择),month(年月选择器,只提供年、月选择),date(日期选择器,可选择：年、月、日。type默认值，一般可不填),time(时间选择器,只提供时、分、秒选择),datetime(日期时间选择器,可选择：年、月、日、时、分、秒)。	<br>
data-calendar	设置了一些我国通用的公历重要节日，通过设置 true 来开启。国际版不会显示。	false/true<br>
data-lang	cn（中文版）、en（国际版，即英文版）	cn/en<br>
data-format	设置显示格式;yyyy(年份),MM(月份),dd(日期),HH(小时),mm(分钟),ss(秒数).默认值：yyyy-MM-dd),可任意排版。	yyyy-MM-dd<br>
data-range	开启左右面板范围选择(即显示两个月的时间面板);	false/true<br>
data-laydatemin	设置最小范围内的时间值(可以为负值 -7)即当前日期前七天。	-7<br>
data-laydatemax	设置最大范围内的时间值(设置7)即当前日期后七天。	7<br>
控制属性<br>
data--value	可以自己设置日期(必须遵循format参数设定的格式),通常情况下不需要填写,默认为空。	2018-05-16<br>
输出属性<br>
data-x-laydatevalue	输出年月日即时分秒都根据文本框显示内容显示<br>
#### 时间格式排版
| 格式	| 示例值 |
|  ----  | ----  |
| yyyy-MM-dd HH:mm:ss	| 2017-08-18 20:08:08| 
| yyyy年MM月dd日 HH时mm分ss秒| 	2017年08月18日 20时08分08秒| 
| yyyyMMdd| 	20170818| 
| dd/MM/yyyy| 	18/08/2017| 
| yyyy年M月	| 2017年8月| 
| M月d日	| 8月18日| 
| 北京时间：HH点mm分	| 北京时间：20点08分| 
| yyyy年的M月某天晚上，大概H点	| 2017年的8月某天晚上，大概20点| 
 
