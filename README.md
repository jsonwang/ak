###我不是程序员我是AK
##商店首页信息表结构store_main_tbl
|字段名|备注|类型|
|:------|:------	| :-------------: | :------------ |
|category_id|分类列表id|Integer|
|category_type|分类类型|Integer|
|category_img_url|分类图片|Text|
|category_img_select_url|分类点击图片|Text|
|version|版本号|Integer|

##商店下载分类表结构
####请求参数：category_id(分类),page(页数)

|字段名|备注|类型|
|:------|:------	| :-------------: | :------------ |
|catgory_id|分类id|Integer|
|group_id|贴贴组id|Integer|
|group_cover|贴贴封面url|Text|
|group_cover_small|卡槽封面url|Text|
|group_name|贴贴组名称|Text|
|group_price|贴贴组价格|Double|
|group_version|贴贴组版本号|Integer|

###商店贴贴项关联表结构
|字段名|备注|类型|
|:------|:------	| :-------------: | :------------ |
|group_id|组id|Integer|
|item_id|贴贴id|Integer|
|item_cover|贴贴封面url|Text|
|item_seq|贴贴项顺序|Integer|
|item_url|贴贴url|Text|
|item_frame|贴贴帧信息|Double|
|item_ttf|字体文件url|Text|
|item_sound|音频url|Text|
|item_delay_times|帧延迟时间1^2^3^...|Text|
|item_sequence|帧播放顺序0^1^2^...|Text|
|item_box|坐标(四个点)0.1^0.2^0.3^0.4|Double|
|item_type|贴贴类型 0-普通贴贴 1-磁力贴贴 2-文本贴贴 3-滤镜 4-其他|Integer|
|item_downloaded_status|下载后状态 0-正常 1-需解锁 2-禁止|Integer|
|item_auto_download|自动下载标识 0-关闭 1-开启|Integer|

###相关信息定义
|字段名|备注|类型|
|:------|:------	| :-------------: | :------------ |
|item_type|组id 贴贴类型 1-普通贴贴 2-磁力贴贴 3-文本贴贴 4-滤镜 5-其他|Integer|
|item_downloaded_status|下载后状态 1-正常 2-需解锁 3-禁止|Integer|
|item_auto_download|自动下载标识 1-关闭 2-开启|Integer|



