---
{{/* 标题 */}}title: {{ replace .Name "-" " " | title }}
{{/* 关键 */}}keywords: []
{{/* 摘要 */}}description: ""
{{/* 日期 */}}date: '{{ now.Format "2006-01-02 15:04:05" }}'
{{/* 作者 */}}author: ""
{{/* 标签 */}}tags: []
{{/* 分类 */}}categories:  []
{{/* 草稿 */}}draft: true
# You can also close(false) or open(true) something for this content.
# P.S. comment can only be closed
{{/* 目录 */}}toc: false
{{/* 评论 */}}comment: false
{{/* 日期 */}}publishdate: '{{ now.Format "2006-01-02 15:04:05" }}'
{{/* 日期 */}}lastmod: '{{ now.Format "2006-01-02 15:04:05" }}'
---