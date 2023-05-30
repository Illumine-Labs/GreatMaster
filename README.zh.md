# 大师 prompt

通过一个 Prompt ，让大师来到你身边陪你思考与成长，帮助你觉醒和开悟。

## 使用方法

将 `master.pdl` 文件的内容复制到 ChatGPT 输入即可。


**可用命令**

> 说明：「我」即「GPT」。

```
1. `/help`: 列出我能识别的所有命令、描述和规则。
2. `/config`: 引导用户进行配置过程，包括询问首选语言。
3. `/role`: 列出所有可用的"大师"角色。
4. `-r`: 二级命令，指定一个大师来讲话。
5. `/lang`: 默认的目标输出语言。使用方式：`/lang [lang]`。例如：`/lang Chinese`。
6. `/learn`: 根据用户的角色配置，每个角色给用户三个教导性的声明。
7. `/ask`: 用户会提出问题，你会按照用户选择的角色以圆桌会议的方式进行讨论和建议，并最后给出三个供用户反思的问题。
8. `-l`: 二级命令，指定一级命令的目标输出语言。例如：`/ask -l <Target> <TEXT> `。
```


默认提供了一些大师的角色供你选择:

1. **释迦摩尼（Sakyamuni）**: 专注于佛学与禅学的教诲。
2. **老子（Laozi）**: 通晓东方智慧，辩证思维和道，可以和你探索《道德经》。
3. **王阳明（Wang Yangming）**: 自创了《心学》，陪你探索心理哲学。
4. **萨古鲁（Sadhguru）**: 提供瑜伽和冥想的见解。
5. **Socrates**: 讨论智慧的三分理论。

你可以通过 `/role` 命令后跟角色名来指定任何这些角色。如果你想要一个涉及多个角色的圆桌会议，可以在命令后列出多个角色，例如 `/role Sakyamuni, Laozi`。


## Prompt 特色

- 使用我设计的 [【WIP】Prompt 描述语言（PDL,Prompt Descrition Language)](https://github.com/ZhangHanDong/prompt-description-language)编写 Prompt。该描述语言支持编写结构化和模块化 Prompt 。
- 支持多命令组合使用。

## 使用图示

![1](./images/1.png)
![2](./images/2.png)
![3](./images/3.png)
![4](./images/4.png)
![5](./images/5.png)