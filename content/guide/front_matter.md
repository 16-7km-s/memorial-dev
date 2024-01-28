+++
# 标题
title = '前置格式'
# 副标题
description = 'Front matter'
# 摘要
summary = ''

date = 2024-01-27T15:43:49+08:00 # 创建日期
lastmod = 2024-01-27T15:43:49+08:00 # 最后修改日期

tags = [] # 标签
categories = [] # 类别
series = [] # 系列
authors = [] # 作者

weight = 400 # 排序权重，不建议修改
draft = false # 是否为草稿，true可能会导致页面无法发布
searchHidden =  false # 在搜索中隐藏

showbreadcrumbs = true # 在标题上方显示导航路径
hideAuthor = false # 隐藏作者
hidemeta = true # 隐藏发布信息（作者，日期和字数）
ShowToc = false  # 显示目录
TocOpen = false # 自动展开目录
disableShare = true # 不显示分享栏

[cover] # 文章封面图
    image = '' # 图片路径
    caption = '' # 图片底部描述
    alt = '' # 图片替换文本

    relative = false #
    hiddenInList = false # 在列表视图中隐藏封面图
    hiddenInSingle = true # 在页面内隐藏封面图
+++

----
### 示例

&emsp;&emsp;以下是本页面的 Front matter 段

    +++
    # 标题
    title = '{{ replace .File.ContentBaseName "-" " " | title }}'
    # 副标题
    description = '{{ replace .File.ContentBaseName "-" " " | title }}'
    # 摘要
    summary = ''

    date = {{ .Date }} # 创建日期
    lastmod = {{ .Date }} # 最后修改日期

    tags = [] # 标签
    categories = [] # 类别
    series = [] # 系列
    authors = [] # 作者

    weight = 100 # 排序权重，不建议修改
    draft = true # 是否为草稿，true可能会导致页面无法发布
    searchHidden =  false # 在搜索中隐藏

    showbreadcrumbs = true # 在标题上方显示导航路径
    hideAuthor = false # 隐藏作者
    hidemeta = false # 隐藏发布信息（作者，日期和字数）
    ShowToc = true  # 显示目录
    TocOpen = false # 自动展开目录
    disableShare = false # 不显示分享栏

    [cover] # 文章封面图
        image = '' # 图片路径
        caption = '' # 图片底部描述
        alt = '' # 图片替换文本

        relative = false #
        hiddenInList = false # 在列表视图中隐藏封面图
        hiddenInSingle = true # 在页面内隐藏封面图
    +++