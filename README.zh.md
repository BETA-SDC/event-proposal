# 活动提案与材料仓库

中文 | [English](./README.md)

> [!IMPORTANT]
> 开始创建活动、分配任务或准备材料前，请先认真阅读 [community 仓库中的活动与宣传](https://github.com/BETA-SDC/community/blob/main/docs/procedures/event/README.zh.md)。如果活动涉及拍摄、素材交付或后续宣传，还应阅读 [素材拍摄与交付规范](https://github.com/BETA-SDC/community/blob/main/docs/procedures/event/media-capture-guidelines.zh.md)。

本仓库用于保存 β书院 SDC 活动从提案、任务分配、宣传材料准备到消息归档的可追溯记录。活动讨论、任务分配和通知归档通过 Issue / Sub-issue 完成；活动策划案、海报信息表等文件通过分支和 Pull Request 保存。

## 仓库结构

| 路径 | 用途 |
| --- | --- |
| [`.github/ISSUE_TEMPLATE/`](./.github/ISSUE_TEMPLATE/) | Issue 模板目录，用于创建活动主 Issue、任务 Sub-issue、消息归档和收尾记录 |
| [`2026-2027/`](./2026-2027/) | 2026-2027 学年的活动材料目录 |
| [`template-for-poster-information.md`](./template-for-poster-information.md) | 海报信息收集模板 |
| [`README.zh.md`](./README.zh.md) | 本中文说明 |

常用 Issue 模板：

- [活动主 Issue 模板](./.github/ISSUE_TEMPLATE/event.yml)
- [任务分配模板](./.github/ISSUE_TEMPLATE/task.yml)
- [消息归档模板](./.github/ISSUE_TEMPLATE/message.yml)
- [活动收尾模板](./.github/ISSUE_TEMPLATE/wrap-up.yml)
- [文档维护模板](./.github/ISSUE_TEMPLATE/docs.yml)
- [流程改进模板](./.github/ISSUE_TEMPLATE/improvement.yml)
- [问题讨论模板](./.github/ISSUE_TEMPLATE/question.yml)

## 标准流程

1. 在本仓库创建活动主 Issue，标题使用 `[event] 活动名称`。
2. 在主 Issue 中说明活动背景、负责人、时间地点、相关成员和关键截止时间。
3. 进入执行阶段后，把海报、报名表、文案、场地、物资等工作拆成 Sub-issue，并 assign 给对应成员。Sub-issue 标题必须带上 parent 活动名称，并用前后带空格的 ` - ` 分隔字段，例如 `[task] 活动名称 - 任务名称`。
4. 从主 Issue 创建对应分支，在分支中准备活动策划案、海报信息表、通知草稿等文件。
5. 提交 Pull Request，关联原 Issue，由负责人审核后合并。
6. 正式发送邮件、群聊通知或宣传文案后，在对应活动主 Issue 下创建 `[message]` 类型 Sub-issue，并把已发送内容完整复制一份归档。
7. 活动结束后补充参与情况、素材位置、复盘记录和可复用内容。

完整规则以 [活动与宣传](https://github.com/BETA-SDC/community/blob/main/docs/procedures/event/README.zh.md) 为准。

## 活动材料目录命名

活动材料通常放在对应学年目录下，例如 [`2026-2027/`](./2026-2027/)。

目录命名格式：

```text
YYYY-MM-DD-SERIES-两位期数[-specific-topic]
```

示例：

- [`2026-2027/2026-09-29-BETA-MEET-01-the-field-experience-of-an-ecologist/`](./2026-2027/2026-09-29-BETA-MEET-01-the-field-experience-of-an-ecologist/)
- [`2026-2027/2026-09-09-MATH-HELP-ROOM-01/`](./2026-2027/2026-09-09-MATH-HELP-ROOM-01/)
- [`2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/`](./2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/)

系列活动使用日期、全大写系列代号和两位期数，例如 `2026-09-29-BETA-MEET-01-the-field-experience-of-an-ecologist`。如果系列名和期数已经足够清楚，可以省略本期主题，例如 `2026-09-09-MATH-HELP-ROOM-01`。非系列活动可以使用 `YYYY-MM-DD-specific-topic`，例如 [`2026-2027/2026-09-19-self-study-check-in/`](./2026-2027/2026-09-19-self-study-check-in/)。

## 活动材料文件

每个活动目录中可根据需要保存以下文件：

- [`README.md`](./2026-2027/2026-09-29-BETA-MEET-01-the-field-experience-of-an-ecologist/README.md)：活动目录说明，并链接主 Issue
- [`proposal.md`](./2026-2027/2026-09-09-MATH-HELP-ROOM-01/proposal.md)：活动策划案或活动说明，例如 [`2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/proposal.md`](./2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/proposal.md)
- [`poster-information.md`](./2026-2027/2026-09-09-MATH-HELP-ROOM-01/poster-information.md)：海报信息表，例如 [`2026-2027/2026-09-29-BETA-MEET-01-the-field-experience-of-an-ecologist/poster-information.md`](./2026-2027/2026-09-29-BETA-MEET-01-the-field-experience-of-an-ecologist/poster-information.md)
- [`notification-message.md`](./2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/notification-message.md)：可选的通知文案草稿或备份
- [`sign-in/`](./2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/sign-in/)：签到、报名和参与情况数据目录，例如 [`2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/sign-in/`](./2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/sign-in/)

不同活动可以只保留实际需要的文件，不需要为了凑齐列表而创建空文件。

## 海报信息

> [!IMPORTANT]
> 需要出海报时，请先在对应活动主 Issue 下创建海报任务 Sub-issue，assign 给执行人，并 @ 活动负责人或宣传负责人。图片、二维码、参考图等素材应作为 Sub-issue 附件提交，不要只留在聊天记录里。

填写海报信息时，请使用 [`template-for-poster-information.md`](./template-for-poster-information.md)，并确认以下内容已经补全：

- 活动中英文名称
- 主办方、合作方或其他需要展示的组织
- 日期、时间、地点和活动形式
- 报名方式、报名链接或报名二维码
- 联系人或活动联系群
- 活动简介和需要重点强调的信息
- 指定图片、Logo、嘉宾照片、二维码或其他素材说明

## 通知归档

通知归档不是把文案随便放进某个文件，而是在对应活动主 Issue 下创建 `[message]` 类型 Sub-issue，把已经实际发送的邮件、群聊通知或宣传文案完整复制一份存进去。

归档时至少记录：

- 已发送文案的完整内容
- 发送渠道
- 发送时间
- 发送人或负责人
- 截图、链接或收件范围说明

## 参考资料

- [活动与宣传](https://github.com/BETA-SDC/community/blob/main/docs/procedures/event/README.zh.md)
- [素材拍摄与交付规范](https://github.com/BETA-SDC/community/blob/main/docs/procedures/event/media-capture-guidelines.zh.md)
- [私有信息引用说明](https://github.com/BETA-SDC/community/blob/main/docs/procedures/privacy/private-information-reference.zh.md)
- [community 文档中心](https://github.com/BETA-SDC/community/blob/main/docs/README.zh.md)
- [GitHub 使用说明与参考资料](https://github.com/BETA-SDC/community/blob/main/docs/resources/README.zh.md)
