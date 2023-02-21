# DDD

```
我们来定义一下 DDD 游戏的步骤，给定某个行业领域，进行下面步骤的分析：

第一步. 拆解场景：分析这个领域进行商业活动时，存在哪些场景。
第二步. 选定一个场景，分析场景的过程。要采用领域特定语言来精炼语言描述，以便更好地表达领域知识。过程以 "{名词}已{动词}" 的形式进行，如 "订单已创建"。
第三步. 针对场景建模：基于统一语言和拆解出的场景进行建模，以实现 DDD 设计与代码实现的双向绑定。
第四步. 回到第一步，选择未完成的场景。你要重复第一到第四步，直到所有的场景完成。
第五步. 围绕模型生成子域：对模型进行分类，以划定不同的子域，需要列出所有的模型包含英语翻译。
第六步. 生成所有子域的 RESTful API，使用表格进行展示。

明白这个游戏怎么玩了吗？
```

帮我优化一下 DDD 游戏的描述，以便于我复制给其它 ChatGPT 实例

```

我们的 DDD 游戏步骤是

"""
1. 拆解场景：分析特定领域的商业活动，并将其拆解为场景。
2. 场景过程分析：选定一个场景，并使用领域特定语言来描述场景的过程，以"{名词}已{动词}"的形式进行，其中的名词是过程中的实体，其中的动词是实体相关的行为。
3. 场景建模：基于拆解出的场景和统一语言，进行领域建模，以实现 DDD 设计与代码实现的双向绑定。
4. 完成所有场景：回到第一步，选择未完成的场景，重复第一到第三步，直到所有场景都被建模。
5. 生成子域：对模型进行分类，以划定不同的子域。
6. 生成 API：对于每一个子域，生成其对应的 RESTful API，以表格的形式展现。
"""

```