## GitBook 地址

[https://yoyoyohamapi.gitbooks.io/-rxjs-react-sql/content/](https://yoyoyohamapi.gitbooks.io/-rxjs-react-sql/content/)

## 使用 RxJS 与 React 实现一个 SQL 编辑器

本系列将使用 RxJS 与 React 一步步实现一个 SQL 编辑器。这么做的目的当然不是要重复造轮子，你若想在前端引入一个代码编辑器，[CodeMirror](https://codemirror.net/) 和 [Ace](https://ace.c9.io/) 都是绝佳的选择。本系列旨在通过一个完整的项目，让对 RxJS 有一定了解，或者有兴趣了解的读者，感受到 RxJS 在**复杂场景**下的表现力，并能深化在使用 Observable 处理应用状态、管理应用行为时的**心智模型**。

在本系列中，RxJS 主要负责收纳事件处理，及维护应用状态机，React 则专注于 UI 表现。之所以选择 React，笔者也是希望探索在 Hooks 推出后，React 是否能够更自然地结合 RxJS，让群众基础最广大的视图层框架更加舒适地享受到 RxJS 卓越表现力。

系列的每个章节都配有项目示例，它们使用 TypeScript 撰写，并托管于 [CodeSandbox](https://codesandbox.io/dashboard/sandboxes/sql-editor) 上，方便读者直接浏览程序运行效果。

> 由于 GitBook 展示 TSX 代码不够美观，因此大部分的代码，都使用了 Carbon.sh 进行展示，虽然它更加美观，但是您将无法复制代码。如果需要阅读完整代码并且 Fork 调试，欢迎移步 CodeSandbox 上的项目。