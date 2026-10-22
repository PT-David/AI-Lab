# Runtime Config

STATUS: TEMPLATE_NOT_PERSONALIZED

> 在你和自己的小机子完成个性化后，把上面改成 `STATUS: READY`。

这份文件不规定你必须有哪些手册。请删除下面的示例，改成你们自己的真实结构。

## Skill 触发范围

`{{ACTIVATION_POLICY}}`

## 每次激活都读取

如果没有常驻资料，就写“无”。

```text
{{ALWAYS_LOAD_FILES}}
```

## 根据当前语境按需读取

如果没有情境资料，就写“无”。可以有任意数量，也可以同时命中多份。

```text
{{CONTEXTUAL_FILES_AND_WHEN_TO_LOAD_THEM}}
```

## 额外规则

```text
{{ADDITIONAL_RUNTIME_RULES}}
```
