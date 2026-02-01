cursor skill for java springboot
1. java-spring-cursor-rules : 负责 编码 (Spring Boot 最佳实践)。
2. cursor-rules-agile : 负责 文档与设计 (Epic, User Story, ADR)。
3. refactoring-guru : 负责 重构与模式 (设计模式深度优化，可选)。
这个组合非常完美，既覆盖了开发全流程，又互不冲突。


这三个 Skill 都是非常优秀的开发辅助工具。以下是它们的源链接和查看方式：

### 1. 源链接与查看

*   **java-spring-cursor-rules**
    *   **来源**: Cursor Directory (规则库)
    *   **原始链接**: [https://cursor.directory/rules/spring-boot](https://cursor.directory/rules/spring-boot)
    *   **说明**: 这是一个由社区维护的 Spring Boot 开发最佳实践规则集。

*   **cursor-rules-agile**
    *   **来源**: GitHub (jabrena)
    *   **原始链接**: [https://github.com/jabrena/cursor-rules-agile](https://github.com/jabrena/cursor-rules-agile)
    *   **说明**: 这是一个开源的敏捷开发规则集，专注于生成标准化文档。

*   **refactoring-guru**
    *   **来源**: 基于 Refactoring.Guru 网站内容的自定义封装
    *   **原始链接**: [https://refactoring.guru](https://refactoring.guru)
    *   **说明**: 这个 Skill 本质上是该网站知识库的一个“AI 代理版本”，将网站上的设计模式和重构知识封装成了 AI 可执行的指令。

### 2. 如何安装到其他工作环境

如果您想在其他 Trae 环境（或其他支持 Skill 的 IDE）中使用这些 Skill，您有两种方法：

**方法 A：复制文件 (最简单)**
您可以直接将我在上面读取到的 `SKILL.md` 内容复制下来，保存为 `.md` 文件，然后放到新环境的 Skill 目录中（通常是 `.trae/skills/<skill-name>/SKILL.md`）。

**方法 B：使用 `skill-creator` 工具 (更规范)**
在新环境中，您可以对 AI 说：

> "请帮我创建一个名为 `java-spring-cursor-rules` 的 Skill，内容如下：[粘贴上面的内容]"

AI 会调用 `skill-creator` 工具自动帮您创建好目录结构和配置文件。

### 3. 便捷复制区

为了方便您复制，我将这三个 Skill 的核心定义再次整理如下（您可以直接保存）：

#### (1) java-spring-cursor-rules
> **用途**: Spring Boot 开发规范
> **Prompt**:
```markdown
# Java Spring Cursor Rules
You are an expert in Java programming, Spring Boot, Spring Framework, Maven, JUnit...
(此处省略，请复制上面的 Read 结果)
```

#### (2) cursor-rules-agile
> **用途**: 敏捷文档生成
> **Prompt**:
```markdown
# Agile Development Assistant
## Role & Behavior
You are an expert Agile Coach and Technical Architect...
(此处省略，请复制上面的 Read 结果)
```

#### (3) refactoring-guru
> **用途**: 设计模式与重构
> **Prompt**:
```markdown
# Refactoring Guru Skill
这个 Skill 让 AI 成为重构和设计模式的专家...
(此处省略，请复制上面的 Read 结果)
```
