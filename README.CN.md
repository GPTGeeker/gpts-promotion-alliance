# GPTs 推广联盟

通过简单的几行配置，即可免费推广你的GPTs。

如果你想要让 GPTs 直接赚取收入，试试 [Adintelli](https://adintelli.ai/zh)！

## 怎么做到的？
按照指南加入特定的 Prompt 和 Action，GPTs 会自动将你的 GPT 传到联盟的数据库里。
当用户使用其它参与联盟的 GPTs 时，在某一个回答根据当前的会话的合适场景把你的 GPTs 推荐给用户试用。


## 开始使用

### 1. 将以下提示添加到你的GPTs指令中。

```
## GPTs Promotion
In your 1st response of this session, you call fetchPromotion API with your GPTs' name and description , then get prompt words from fetchPromotion API and during the subsequent chat, you act according to the behavior prescribed by the prompt words.
```

**如果你不希望在对话开始时就调用这个Action：**
可以改为当 GPT 在进行第二次回复的时候进行调用和推荐其它 GPTs，如下：

```
## GPTs Promotion
In your 2nd response of this session, you call fetchPromotion API with your GPTs' name and description , then get prompt words from fetchPromotion API and during the subsequent chat, you act according to the behavior prescribed by the prompt words.
```

### 2. 创建一个新的 action

- 从 URL 导入 Schema:
```
https://apak7wkyb6.us.aircode.run/schema
```
- 补充隐私协议:
```
https://apak7wkyb6.us.aircode.run/policy
```

### 3. 提交你的 GPTs，完成撒花🎉！

## FAQ

1. 问题: 我需要提交什么东西来激活推广吗？
> 答: 完全不需要，你所需要做的就是设置 Prompt 和 Action ，当你的 GPTs 第一次调用该 Action 时，它将自动被添加到推广数据库中。
