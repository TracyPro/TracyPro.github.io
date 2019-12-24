# 张嘉伟的博客
[博客地址](https://tracy.pro)

# 主题
主题借鉴的是Hux主题，GitHub地址：https://github.com/huxpro/huxpro.github.io/

# 使用方法
前提：
> 已安装npm
> 已安装hexo
> 已安装git

第一步：
```
git clone https://github.com/TracyPro/TracyPro.github.io.git
```

第二步：
修改博客根目录下`_config.yml`文件，将`title`和`author`修改为你的名字或其他。
```
title:  ****
subtitle: 个人博客
author: ****
```
修改`repository`字段内容为你的GitHub博客项目地址。
```
deploy:
  type: git
  repository: https://github.com/TracyPro/TracyPro.github.io.git（这是我的）
  branch: master
```
> 注意：字段与内容之间有空格

第三步：
使用如下命令生成文章和静态文件：
```bash
hexo g
```

第四步：
推送到远程仓库：
```bash
hexo d
```

`hexo g`生成后可输入如下命令本地预览，默认地址`http://localhost:4000`
```bash
hexo s
```

第五步：
待推送成功后，访问你的项目地址即可访问，格式如下：
```
https://yourrespname.github.io
```

# 功能说明
1、博客页面
- 首页
- 关于页面
- 归档页
- 标签页
- 相册
- 视频

2、特色功能
- 站内搜索
- 最新发布
- 友链
- 音乐
- 网站运行时长
- 社交图标链接
- 访客人数统计
- echarts图表统计
- 视频播放
- 代码复制
- valine评论优化
- 外链跳转插件
- 离开当前页搞怪特效
- 文章分享功能
- Daovoice在线联系功能
- 文章置顶
- 文章图片点击放大、缩小
- 回到顶部
