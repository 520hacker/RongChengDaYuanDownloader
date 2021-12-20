## site rip Tool for 'Rong Cheng Da Yuan'
this project is a site rip tool for special video (asia bondage video) site RongChengDaYuan .
I.E. 
You can use this tool download all of the videos of this small site . 
when you are free client for this site , then you can download preview videos .
when you are payed client for this site , then you can download full videos .

--------------------------------------
### 警示
视频内容均为专业演技人员\从业者\爱好者演出,并非常规世俗所能接受.
请勿在未经得他们同意和支持的情况下进行学习实践.

### License
本工程引用了M3U8下载开源项目 N_m3u8DL-CLI https://github.com/nilaoda/N_m3u8DL-CLI/releases
故所有的协议均遵循\继承自该项目.

### 文件说明
#### data.json
- 数据文件,保存所有将下载数据

### 配置说明
#### cookies.txt 
- 如果您是会员,则可以将您的COOKIES 信息填充到本文件里面,这样您就能下载到完整的视频,而非预览版.
- 目前网站重置 cookies 的时间为 01:00 AM,GMT+8 
- 不建议会员分享COOKIES,给网站带来负载压力会导致站长关站或者进行针对性封杀.

#### start.txt
- 填写asc,从最早的视频开始下载.
- 填写mid,从中部的视频开始下载.
- 填写任意数字,从指定的数字开始下载.

#### page.txt
- 默认值5，填写数字，代表您将获取下载更新的页的数量，每页为120

#### 依赖
- 本程序使用 ffmpeg 进行视频合并，确实其则无法执行合并操作。

#### 默认检查
- 本程序默认会过滤预览视频，仅下载会员视频，因此需要会员登录的cookies方能正确执行。
- 站点默认设计是AM01:00自动注销所有cookies，所以每天至少需要手动更新一次cookie才能操作
- cookies的获取请自行百度

### 断点续传原则
- 所有的数据都会被下载到 Downloads 目录
- 第二次启动应用的时候会检查未完成的任务,并进行断点续传.
- 如果该视频已经被下载并且被编译为MP4,则被是为已完成,会自动跳过.
