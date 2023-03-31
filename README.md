# BIT_document-shareing_electrospray
use zotero and onedrive to realize document shareing

1.安装Zotero

	参考：https://www.bilibili.com/video/BV1ZE411p7qT/?spm_id_from=333.788.recommend_more_video.1&vd_source=7ffe3eed83b239ebb952bdc2208dc83e

2.安装插件
	
	已上传插件压缩包zotero plugins.zip（直接拖到插件安装位置）

	参考：https://www.bilibili.com/video/BV1gP4y1y7yH/?spm_id_from=333.337.search-card.all.click&vd_source=7ffe3eed83b239ebb952bdc2208dc83e
	

3.使用onedrive（windows自带）

	登录账号：查看“登录onedrive.zip”，解压密码询问本课题组杜泽*。
	该云盘需要storage,styles,translators三个文件夹内容,切勿在随意云盘上传文件。

4.将onedrive云和自己的zotero绑定
		
	参考：https://zhuanlan.zhihu.com/p/408027026

	4.1删除自己zotero软件储存位置处（D:\*\*...\zetero）的storage,styles,translators文件夹。
	4.2进行关联：在windows搜索窗口输入cmd，打开命令提示符；输入mklink /J  “自己zotero储存位置路径”  “onedrive云盘位置路径”
		具体输入如下：（一定要先删掉zotero存储路径下的三个文件夹）
		mklink /J "D:\Zotero\storage" "C:\Users\***\OneDrive\Zotero\storage"
		mklink /J "D:\Zotero\styles" "C:\Users\***\OneDrive\Zotero\styles"
		mklink /J "D:\Zotero\translators" "C:\Users\***\OneDrive\Zotero\translators"

5.为提升体验需对zotero设置

	5.1 编辑-首选项-同步-将自动同步取消勾选，文件同步下两个也要取消勾选

	
