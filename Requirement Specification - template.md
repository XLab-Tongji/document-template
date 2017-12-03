# Requirement Specification (需求规约)

## Project Introduction (项目介绍)

The backgroud and the purpose of the project

## Rquirement Analysis (项目需求分析)

Using a KAOS diagram to decompose the project form high-level goals to user scenarios

## Use Case Analysis (用例分析)

Based on the Requirement Analysis, make a Use Case Diagram for the project, and write use case specifications for each use case.

Here gives a sample template of a use case:

```flow
st=>start: 开始
e=>end: 结束
op=>operation: 我的操作
cond=>condition: 确认？

st->op->cond
cond(yes)->e
cond(no)->op
```