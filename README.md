## 项目模块结构

- **gmall-v4.0**：父工程，包含所有依赖包管理
  - **speed-common**：公共模块
    - base包：业务代码的基类
    - bean包：所有实体类
    - constant包：所有常量类
    - function包：所有函数类
    - util包：所有工具类
  - **speed-dim**：维度表模块（依赖common）
  - **speed-dwd**：明细表模块（依赖common）
  - **speed-dws**：聚合表模块（依赖common）