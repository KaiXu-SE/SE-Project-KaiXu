# KaiXu（开序）

KaiXu 是面向高校学生的课程学习计划与课程项目协作系统。它以“课程”和“项目”为基本工作区，把分散在教学平台、课程群和口头通知里的任务、日程和学习资料收进同一个入口，帮助学生把截止日期落到具体执行时间，并在小组项目中共享目标的同时保住个人排期隐私。

## 要解决的实际问题

1. **通知太散**：作业和考试安排分布在 Canvas、微信/QQ 群和老师口头提醒里，容易漏记或记错截止时间。
2. **只记截止、没排时间**：普通待办只提醒哪天交，临近期末多门课程项目和复习撞在一起时，很难提前安排每天做什么。
3. **资料难找且会过期**：课件、作业要求和小组文件散落在本地文件夹和群聊里，微信群文件过期后还要反复找人重发。
4. **小组进度和个人时间脱节**：小组作业需要同步分工和截止时间，但每个人的课表和空余时间不同，成员也不想把私人时间安排公开给全组。

## 项目章程摘要

Windows 桌面端是主工作台。学生无需登录即可在本机使用，登录后断网仍能编辑，恢复联网后自动补传。Android 端供学生登录并联网后查看日程、快速录入任务、更新状态、调整本人已有的工作时段和使用番茄钟。

项目分三版交付，每版都用学生的实际操作验收。

- **M1（v0.1.0）个人工作区与时间规划。** 在桌面按课程或项目整理任务、日程、链接和笔记，也可单独记录个人事项。学生手动建任务，把一次作业分到多个工作时段，排期与课表重叠或超过截止日期时会收到提示。
- **M2（v0.2.0）账号同步与小组协作。** 桌面离线修改可在重连后同步。项目所有者管理成员，组员共享任务分工、进度、共同事件和资料。服务端按成员资格检查访问，个人时段、剩余估时和专注记录仅本人可见。
- **M3（v0.3.0）外部接入与完整验收。** 只读拉取 Canvas 作业，预览学期课表并在确认后建立课程和上课事件。交付任务资料关联、附件版本、规则排程和 Android 番茄钟。课程群消息的 AI 提取是扩展项，候选任务和排程均经学生确认后保存。

完整范围、角色权限、团队分工、各版验收条件和主要风险见[项目章程](docs/governance/project-charter.md)。

## 项目文档索引

- 协作与提交规范：[CONTRIBUTING.md](CONTRIBUTING.md)
- 文档总索引：[docs/README.md](docs/README.md)
- 团队分工与角色：[docs/governance/team.md](docs/governance/team.md)
- 调研计划表：[docs/requirements/research-plan.md](docs/requirements/research-plan.md)
- 用户访谈记录：[docs/requirements/interviews.md](docs/requirements/interviews.md)
- 竞品分析：[docs/requirements/competitive-analysis.md](docs/requirements/competitive-analysis.md)
- 需求调研报告：[docs/requirements/research-report.md](docs/requirements/research-report.md)
- 用户故事清单初稿：[docs/requirements/user-stories.md](docs/requirements/user-stories.md)

## 当前阶段进度

- [x] 建立仓库、配置 `main` 分支保护和基础标签
- [x] 完成模板、文档索引、团队分工与文档检查 CI 合并（Issue #1）
- [x] 提交选题 Issue 并完成立项确认
- [x] 合并需求调研计划、访谈纪要、竞品分析、调研报告与用户故事初稿
