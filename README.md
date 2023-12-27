# CSharp 作业

------

清华大学电子系科协软件部 2023 暑期培训作业

------
123
## 题目及要求

- 根据Program.cs中IProgress的要求修改Progress类中的代码
- 作业地址[https://github.com/shangfengh/EESAST-hw2023-CSharp1/tree/main](https://github.com/shangfengh/EESAST-hw2023-CSharp1/tree/main)

## 提交方式

GitHub 提交

- fork 仓库：[shangfengh/EESAST-hw2023-CSharp1(github.com)](https://github.com/shangfengh/EESAST-hw2023-CSharp1/tree/main)到个人仓库，按要求修改好后，从个人仓库提pr到原本的仓库，pr信息填写为：`CSharp_姓名_班级` （如：`CSharp_大佬_无29`）。

## 截止日期

由yxgg决定

## 本作业存在问题

- 设置却没有检测Num
- 应当在类外调用 FinishedProgress，因为即便设置了属性，类内依旧可以访问字段（只要属性是复杂逻辑），属性更像对类外操作的要求（只要不开放set访问器），所以在方法内处理也十分合理
