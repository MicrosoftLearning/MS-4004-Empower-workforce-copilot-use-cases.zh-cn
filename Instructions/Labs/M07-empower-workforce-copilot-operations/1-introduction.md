# 实验室设置：

在此模块中，我们将为 Microsoft 365 Copilot 创建引用文件的提示。 首先，让我们将所有必需的文件上传到 OneDrive，以确保它们在整个实验室中都可访问。


### 将文件上传到 OneDrive

按照以下步骤将所需的所有文件上传到 **OneDrive**：

1. 使用本地**管理员**帐户和密码 `Pa55w.rd` 登录到租户提供程序提供的虚拟机。
2. 在 Windows 任务栏上，选择“**Microsoft Edge**”。
3. 在地址栏中输入`https://www.office.com`。
4. 在“**欢迎使用 Microsoft 365**”下，选择“**登录**”。
5. 在“**登录提示符**”处，输入 `userx@yourtenant.onmicrosoft.com`（租户提供程序提供的用户名和租户），然后选择“**下一步**”。
6. 在“**输入密码**”屏幕上，输入用户帐户的密码（由租户提供程序提供），然后选择“**登录**”。
7. 如果系统提示“**保持登录**”，请选择“**不再显示**”，然后选择“**是**”。
8. 在 **Microsoft 365** 中，选择“**应用**”。
9. 在“**应用**”中，选择“**OneDrive**”。
10. 在 **OneDrive** 的左上角，选择“**+**”（添加新的）>“**文件上传**”。
11. 在**文件资源管理器**中，选择“**此电脑**” > “**本地磁盘 (C:)**”并打开 **ResourceFiles** 文件夹。
12. 选择 **ResourceFiles** 文件夹中的所有文件，然后选择“**打开**”以将其上传到 **OneDrive**。
13. 上传完成后，应该会在屏幕底部中央看到“**已上传 29 个项目到‘我的文件’**”。
14. 保持 **Edge** 打开，然后继续执行下一个任务。

### 在 Copilot 中引用文件

使用 Copilot 时，你可能会发现某些文件无法立即在建议中找到。 出现这种情况的原因是，某些 Copilot 体验仅引用“**最近使用(MRU)**”列表中的文件，而其他体验则允许你直接浏览 **OneDrive**。 若要确保文件显示在 **MRU** 列表中，只需在相关的 Microsoft 365 应用中将其打开，它就会自动添加。

> [!IMPORTANT]
> Microsoft 365 Copilot 只能处理保存到 **OneDrive** 的文件。 需要将存储在本地电脑上的文件移动到 **OneDrive** 中，以便 Copilot 访问它们。

随着本模块的深入，你将有机会在这些文件上尝试各种提示。 请随意尝试不同的方法，以提升你使用 Copilot 的技能。

# 简介
---
本模块为运营经理提供使用 Copilot 的 AI 支持的代码完成工具所需的技能和知识，以简化其工作流并提高其工作效率。 作为一名运营经理，你有效使用 Microsoft 365 Copilot 的能力对于以下方面至关重要：<br>

 -  项目管理****。 Copilot 可以帮助运营经理更高效地管理项目。 例如，它可以帮助他们分配任务、安排日程，甚至提供有关项目绩效的见解。
 -  流程自动化****。 Copilot 可帮助运营经理自动执行重复任务。 例如，它可帮助运营经理录入数据、生成报告，甚至进行校对。
 -  **协作**。 Copilot 可以帮助运营经理更有效地协作。 例如，它可以帮助他们进行团队沟通、文档共享，甚至可以提供提醒。
 -  自定义。 可以自定义 Copilot 以满足运营经理的独特需求。 例如，它可以帮助运营经理实现库存管理、供应链优化甚至是质量控制。

Microsoft 365 Copilot 是 AI 支持的写作助手。 它能够理解上下文、建议措辞，并帮助生成内容，所有这些都可提高工作质量。 本用例模块中的练习旨在帮助运营经理培养以下技能：

 -  使用 Whiteboard 中的 Microsoft 365 Copilot 来集思广益，提出安装新锅炉系统的项目计划创意。
 -  使用 Outlook 中的 Microsoft 365 Copilot 汇总实际电子邮件线程并生成回复。
 -  使用 Word 中的 Microsoft 365 Copilot 可创建一份报告，用于分析锅炉与火炉供热系统，同时还比较 Copilot 可以生成的输出类型。
 -  使用 PowerPoint 中的 Microsoft 365 Copilot，根据创作的分析锅炉和火炉供热系统的报告，来创建演示文稿。
