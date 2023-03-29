# DSM_Login_BingWallpaper
把脚本复制加入群晖DSM的计划任务（请选择root用户）里面即可自动更换登录界面的背景为bing今日美图，并且替换欢迎信息为美图简介.   
Test for DSM5.x,DSM6.x. DSM 7.x 
```sh
# 如需收集保存壁纸,请去掉下面注释,设置保存文件夹路径
# 在FileStation里面右键文件夹属性可以看到路径

#savepath="/volume1/myshare/wallpaper"

# 如需下载4k分辨率,请设置res=4k
# 如需下载体积更大的4k以上分辨率的原始图片,请设置res=raw
# To download 4K resolution, set res=4K
# To download a larger original picture, set res=raw

#res=4k

# 修改用户桌面壁纸,注释后会替换系统的wallpaper1
# 你需要清空浏览器缓存查看效果，仅在DSM7.x上测试.
# Modify user desktop wallpaper.Only test for DMS7.x.
# System "Wallpaper1" will replaced by remove the comment.
# You need to clear the browser cache to see the effect.

#desktop=yes
```
