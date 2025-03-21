# 学术主页 Academic Page

基于Hugo的学术个人主页模板，设计简洁易用，适合学者、研究人员展示个人学术成果。

## 特点

- 单页面设计，以简洁的方式展示所有重要信息
- 悬浮个人资料卡片，展示头像和个人简介
- 支持暗黑/明亮模式切换
- 多语言支持 (目前支持中文和英文)
- 响应式设计，适配各种设备
- 简单的配置文件修改即可个性化内容

## 如何使用

1. 克隆此仓库到本地:
```
git clone https://github.com/yourusername/academic-page.git
```

2. 根据需要修改`hugo.toml`配置文件

3. 编辑`content/en/_index.md`和`content/zh/_index.md`修改内容

4. 将个人头像放在`static/images/profile.jpg`位置

5. 本地预览:
```
hugo server -D
```

6. 构建网站:
```
hugo
```

## 自定义

- **个人信息**: 修改`hugo.toml`中的`[params]`部分
- **社交媒体链接**: 修改`hugo.toml`中的`[[params.social]]`部分
- **内容**: 编辑`content/`目录下的markdown文件

## 许可

MIT License 