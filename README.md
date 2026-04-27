# zitie-images

人教版语文 1-6 年级 12 册教材封面/目录预览图，供 [www.txtqk.com](https://www.txtqk.com) 通过 jsDelivr CDN 拉取。

## 结构
```
textbooks/{id}/
  preview/
    page_01.jpg ... page_09.jpg     # 原图 1200×1695，给 lightbox 放大
    thumbs/
      page_01.jpg ... page_09.jpg   # 360px 宽缩略图，给首页条带
  meta.json                         # 教材元数据（unit/lesson 结构）
  vocabulary.json                   # 写字表 + 识字表（仅已就绪的册有）
```

## CDN 链接
```
https://cdn.jsdelivr.net/gh/bwnian/zitie-images@main/textbooks/{id}/preview/thumbs/page_01.jpg
```

## 来源
原图来自[国家中小学智慧教育平台](https://basic.smartedu.cn/)公开发布的电子教科书，同步脚本见主仓 `tools/sync_smartedu.py`。
