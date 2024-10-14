# 程序设计英语词汇列表

本列表中的单词是英语类计算机书籍、文档、文章以及程序设计竞赛中高频常见的技术词汇，也是程序员工作中常见的英语词汇，最终目的是希望程序员集合自身的英语基础，在掌握列表中的词汇后，可以无障碍阅读英语技术文章和文档。

官网：https://english.scpc.team/

## 贡献 

- 如发现有错误翻译，或者更合适的翻译，也可以通过 Pull Request 来更新列表（单词列表在 `_posts` 文件夹里）
- 请按照单词首字母顺序进行更新
- 单词首字母请小写，翻译请使用中文标点符号
- 请进入 `_post` 文件夹，添加一个 `.md` 文件以记录单词，格式见下
- 格式:
  - 命名为:`日期-单词.md`, eg:`2020-01-01-analogy.md`, 短语词组中的空格请使用 `-` 替换
  - 一个 `.md` 文件只能记录一个单词
  - 文件内部格式:
    ```
    ---
    word: analogy
    meaning: 类比，比喻
    correct: /əˈnælədʒi/
    note:
    category: 名词
    ---
    ```
    - `word`: 单词
    - `meaning`: 翻译
    - `correct`: 音标
    - `note`: 实例应用
    - `category`: 词性/组别
    - 上下的 `---` 是必须的，特殊符号请使用中文符号
- 提交 PR 教程：[MAA-纯网页端 PR 教程](https://maa.plus/docs/zh-cn/develop/pr-tutorial.html)

## Feature Request

- 请直接提 issue 来增加需要添加的新功能或单词列表

## 本地化部署 Get Started

1. Install Ruby: `brew install ruby` # 安装 Ruby
2. Install Bundler globally: `sudo gem install bundler --no-user-install` # 安装 bundler
3. Clone the repo # 克隆仓库
4. Install dependencies: `bundle install`  # 安装依赖
5. Launch the project from local server: `bundle exec jekyll serve` # 启动
6. Visit `http://127.0.0.1:4000` # 访问

## Anki 记忆卡片

- [程序员英语词汇宝典记忆卡片](most-frequent-technology-english-words.apkg)

## 鸣谢 Acknowledgement

- [most-frequent-technology-english-words](https://github.com/Wei-Xia/most-frequent-technology-english-words)