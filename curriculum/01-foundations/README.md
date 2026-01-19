# 01 基础入门（语法与核心概念）

**目标：**掌握 NetLogo 语法、Agent 类型与基础交互。  

## 理论讲解
- NetLogo 的四类 agent：turtles / patches / links / observer。  
- 变量作用域：`globals` 与 `turtles-own` 的差异。  
- 时间步：`tick` 与模型进度记录。  

## 实践任务（建议 5 课时）
1. **认识界面**：打开 Models Library 的 “Wolf Sheep Predation”，观察按钮、slider、plot 的作用。  
2. **语法与流程**：写 `setup` / `go` 让 turtles 随机移动。  
3. **状态管理**：为 turtles 添加 `energy` 并在能量为 0 时死亡。  
4. **环境交互**：为 patches 添加 `food` 并让 turtles 在有食物处补充能量。  
5. **界面联动**：增加 slider 控制数量与速度，plot 显示存活数量。  

## 代码 Demo
- 见 `demos/01-random-walk.nls`（随机游走 + 能量消耗）。  

## 理论要点速记
- `ask turtles` 表示并行执行每个个体规则。  
- `globals` 适合记录总体统计量或时间步。  
