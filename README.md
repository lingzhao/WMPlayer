# WMPlayer
WMPlayer视频播放器，AVPlayer的封装，继承UIView，想怎么玩就怎么玩。支持播放mp4、m3u8、3gp、mov，网络和本地视频同时支持。全屏和小屏播放同时支持。
cell中播放视频，全屏小屏切换自如。

![image](https://github.com/zhengwenming/WMPlayer/blob/master/WMPlayer/Resource/WMPlayer.gif)   

#用法，继承UIVIew，初始化传frame和URLString，调用play方法播放
1.初始化

    wmPlayer = [[WMPlayer alloc]initWithFrame:playerFrame videoURLStr:self.URLString];
    [self.view addSubview:wmPlayer];
    [wmPlayer.player play];
    
2.切换视频

        [wmPlayer setVideoURLStr:model.mp4_url];



依赖库为Masonry。
使用过程中有bug，请联系我，我会及时修复。谢谢大家的支持。

#欢迎加入iOS开发技术支持群，487599875，进群必须改名，格式：城市-iOS-名字，例如广州-iOS-文明
#欢迎关注我的斗鱼直播间，用手机斗鱼TV，直接搜索“文明直播间”或者“极端恐惧”就可以找到我的直播。iOS技术分享直播。进来点一下关注，谢谢，开播会有推送到大家手机。（个人直播，非机构，适合初级iOS和中级iOS，高级iOS不用进来喷我了，谢谢）。
