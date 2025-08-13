lowcode-vue/
├─ packages/
│  ├─ core/                 # 引擎内核：协议、命令系统、历史栈、事件总线
│  ├─ designer/             # 设计器壳：面板、画布、选中态、框选、标尺、栅格
│  ├─ renderer-vue3/        # Vue3 运行时渲染器（生产可只引入它）
│  ├─ materials-element/    # Element Plus 物料包（Button/Input/... 的 meta + 适配器）
│  ├─ setters-basic/        # 通用 Setter（输入框、选择器、表达式编辑、绑定器）
│  ├─ datasource/           # 数据源引擎：REST/GraphQL/自定义脚本
│  ├─ plugins/              # 常用插件（导入导出、页面管理、i18n、快捷键、对齐线）
│  └─ utils/                # 通用工具（深拷贝、唯一ID、快照、DSL校验）
├─ apps/
│  ├─ studio/               # 设计器应用（集成 designer + plugins）
│  └─ preview/              # 运行态预览应用（集成 renderer-vue3）
├─ examples/
│  └─ schema-examples/      # 示例页面 Schema
├─ pnpm-workspace.yaml
└─ package.json
