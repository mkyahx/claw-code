# Claw Code (Kimi Adapter Edition)

这是由 mkyahx 维护的 Claw Code 增强版。

## 🛠️ 本次核心改动
- **Kimi 适配**：成功在 rust/crates/api/src/providers/anthropic.rs 中适配了 Moonshot AI 协议，支持使用 moonshot-v1-8k 模型。
- **系统指令优化**：针对 Kimi 模型优化了 System Prompt，移除了道德说教，赋予了 AI 更强的文件操作执行力。
- **Git 集成**：AI 现在具备创建分支并自动提交代码的意识。

## 🚀 启动方式
export MOONSHOT_API_KEY="你的Key"
./target/release/claw --model moonshot-v1-8k

---
原作者: ultraworkers | 适配者: mkyahx