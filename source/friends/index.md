---
title: 友情链接
date: 2021-06-17 15:30:30
onlyTitle: true # 只显示title
toc: false # 不显示文章目录
# type: "friends" # 这个不要了
# layout: "friends" # 这个不要了
---

```markdown
{% issues sites | api=https://gitee.com/api/v5/repos/yuang01/friends/issues?sort=updated&state=open&page=1&per_page=100&labels=active %}
```