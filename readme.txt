用 idea 使用 kotlin 语言 写一个可以使用 deepseek 对话的插件，功能要求有以下几点 1. 该插件可以用在 android studio .idea pycharm clion 等IDE 中 ， 2.这些ide 安装插件后在ide的边栏有独立优美的对话框 3.选中ide 中的代码 可以有多个选项目（1. 解释选中的代码，2.重构选中的代码， 3查找选中代码的bug, 4,解释事个文件或整个类，5.重构整个文件或整个类 ，6.查找选中文件或类中的bug）

对话请求接口 文档如下，请认真阅读改文档
https://docs.siliconflow.cn/cn/api-reference/chat-completions/chat-completions



1.同时要做以下优化
2.RSyntaxTextArea 实现代码高亮
3.Markdown 解析库处理响应格式
4.使用Kotlin协程简化异步操作
5.实现消息持久化存储

6.添加详细的错误处理
7.实现速率限制和重试机制
8.增加消息发送状态指示
9.支持流式响应显示
10.添加代码差异对比功能（用于重构建议）

另外求不要卡顿，界面优美 交互性好 ，类似聊天的界面  可以保留或清空聊天记录，请给出详细的思考过程 并给出完整的代码。