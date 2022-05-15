[<- Back 返回目录](README.md)

# Write Tasks Not User Stories

# 编写任务而不是用户故事

At Linear, we don’t write user stories and think they’re an anti-pattern in product development. We write short and simple issues that describe the task in plain language instead.

在 Linear，我们不写用户故事（User Story），并且认为它们是产品开发中的一种反模式。我们写短而简单的问题（Issue），用简单的语言描述任务。

The point of writing an issue is to communicate a task. It needs to be clear enough so that the assignee can perform it and also give enough context so that teammates who need to know understand what work is being done. So the goal when writing issues should be to do this as effectively and quickly as possible.

写问题的目的是为了传达任务。它需要足够清晰，以便被指派者能够执行，同时也要提供足够的背景，以便团队成员能够了解正在进行的工作。因此，写问题时的目标应该是尽可能有效和快速地完成这个任务。

## Why user stories are obsolete

## 为什么用户故事已经过时了

User stories evolved over twenty years ago as a way to communicate what a customer wanted into product requirements that a software team could deliver. Fast forward to today and a lot of things have changed about how we build software. Customers are tech-savvy enough to articulate basic product requirements. We’ve developed standards for common features such as shopping carts, todo lists, and notifications so there is no need to explain how they should work. The best product and engineering teams understand their users deeply and are familiar with how their product should work.

用户故事是在 20 多年前发展起来的，这种方式可以将客户的要求，转化为软件团队需要交付的产品需求。时至今日，我们构建软件的方式已经发生了很大的变化。对技术精通的客户，可以阐明基本的产品需求。常见的功能也已经标准化，如购物车、任务列表和消息通知等，因此没有必要过多解释它们。最好的产品和工程团队应该是非常了解用户的，并且也熟悉他们自己的产品应该是什么样子的。

User stories have become a cargo cult ritual that feels good but wastes a lot of resources and time. They’re a roundabout way to describe tasks, obscuring the work to be done. User stories are time-consuming to write and read and can silo engineers into a mechanical role where they code to the issue requirements instead of thinking about the user experience holistically at the product level. One reason user stories are complicated and difficult to scope is because they bring what should be product-level details into the task level. And frankly, they don’t match how we communicate about software in real conversations.

用户故事已经成为一种仪式崇拜，感觉不错，但却浪费了大量的资源和时间。它们迂回的描述任务，掩盖了要做的工作。用户故事的编写和阅读都很耗时，而且会使工程师陷入机械化，他们根据要求进行编码，而不是在产品层面上全面地考虑用户体验。用户故事之所以复杂和难以确定范围，是因为它们把本应属于产品层面的细节带到了任务层面。坦率地说，它们与我们在实际对话中对软件的交流方式不一致。

## A better way to write issues

## 撰写问题的更好方法

Write clear, simple issues that describe tasks in plain language. Write your own issues. Discuss the user experience at the product and feature level, not the task level. Instead of spending time creating user stories, spend it talking to users and thinking through features before building them.

编写清晰、简单的问题，用平实的语言描述任务。自己提交问题。在产品和功能层面讨论用户体验，而不是在任务层面讨论。与其花时间创建用户故事，不如花时间与用户交谈，在构建功能前思考。

### Describe concrete tasks or problems

### 描述具体的任务或问题

An issue should describe a task with a clear, defined outcome. This could be a piece of code, design, document, or action to be taken. If it’s not a task, then it doesn’t belong in the issue tracker. Maybe it’s a project idea that needs to be fleshed out in a document or conversation or a larger feature that should be broken down into smaller, tangible pieces of work.

问题（Issue）应该描述一个有明确结果的任务。这可能是一段代码、设计、文件或要采取的行动。如果它不是一个任务，那么它就不应该被记录到问题列表。也许它是一个想法，需要记录在文档或者发生在对话中，或者是一个较大的功能，应该被分解成较小的、有形的任务。

There will be exceptions to this rule. For example, before working on a feature you’ll spend time exploring the design and technical approach. You can create placeholder issues in these instances to break down later (e.g. Explore design) or frame it as a deliverable (e.g. Write project spec).

这条规则也会有例外。例如，在进行一项功能工作之前，你会花时间探索设计和技术方法。在这种情况下，你可以创建一个占位问题，以便以后分解（如探索设计），或将其作为一个可交付的事务（如编写项目规格）。

### Write clearly and directly

### 清楚和直接

Write short and simple issue titles that directly state what the task is. The title should be easy to scan, since most people will read it on a list or board in the context of other issues. Descriptions should be optional–not required–and can include relevant thoughts or context as well as links to deeper discussions. Write only as much as you need to share to perform the task and communicate relevant information to the team.

写短而简单的问题标题，直接说明任务是什么。标题应该容易扫描，因为大多数人都会在列表或黑板上结合其他问题来阅读它。描述应该是可选的，而不是必须的，可以包括相关的想法或背景，以及更深入的讨论的链接。只写执行任务需要知道的内容，其他相关内容可以直接和团队沟通。

When sharing a feature request or bug report, quote user feedback directly instead of summarizing it. Often, a customer describes the pain point more authentically than you could summarize it and it’s faster to copy and paste, too. Link to the customer conversation so that if more information is needed, it’s easy to get.

当分享一个功能需求或错误报告时，直接引用用户的反馈，而不是对其进行总结。通常情况下，客户描述的痛点比你总结的更真实，而且复制和粘贴也更快。链接到客户的对话，这样，如果需要更多的信息，就很容易得到。

### Write your own issues

### 自己提交问题

Everyone on the team should write their own issues. It’s faster and easier for the person who understands how to do the work to write issues describing it. It also sets up your team to do a better job. When you write your own issues, it forces you to think through the problem at a deep level. This creates space to come up with even better approaches and makes it easier to spot shortcuts or missing parts in the plan. The practice also reframes how you approach work entirely. Instead of building to mark a task done or check off a list of requirements, your focus is on the product or project deliverable.

团队中的每个人都应该自己提交问题。让更了解问题的人写问题，会更快更容易。这也为你的团队做更好的工作做了准备。当你自己写问题时，你被迫在深层次上思考问题。这为提出更好的方案创造了空间，并使你更容易发现计划中的捷径或缺失部分。这种做法也完全重塑了你对待工作的方式。你的重点是产品或项目的可交付性，而不是为了标记任务的完成或核对需求的清单。

In some cases, it makes more sense to write issues for others such as when filing a bug report. This should be encouraged with the caveat that issues are written slightly differently. When writing the issue, frame it as an ask or describe the problem. Let the assignee come up with the solution and then rewrite the issue as a task.

在某些情况下，为别人写问题更有意义，比如在提交错误报告时。我们应该鼓励这种做法，但要注意问题的写法略有不同。在写问题的时候，把它写成一个请求或者仅仅描述下问题本身。让实际解决问题的人去想解决方案，然后把问题改写成一个任务。

### Keep user experience discussions at the product level

### 将用户体验的讨论保持在产品层面上

Discuss the customer experience at the product level when you spec out projects and build your roadmap. Engage the full team in these conversations–designers, engineers, and customer-facing folks–so that everyone has a deep understanding of the user needs, limitations, and product requirements. Then delegate the work to project teams and expect them to deliver. They’ll understand the user experience intuitively, so you don’t need to clarify it at the task level.

当你设计项目和建立路线图时，在产品层面上讨论客户体验问题。让整个团队参与这些对话--设计师、工程师和面向客户的人员--以便每个人都能深入了解用户需求、限制和产品要求。然后把工作委托给项目组，并期望他们能够完成。他们会凭直觉理解用户体验，所以你不需要在任务层面上澄清它。

### ✨ ProTip: How we work at Linear

### 小提示：我们在 Linear 如何工作

We discuss a feature or project deeply before deciding on an implementation plan. The project owner writes specs and gathers feedback until we feel like we have the right approach. Only then do we start writing code. It’s not uncommon to take a couple weeks to think through a feature before building it but once we’ve come up with the right plan, it’s straight into execution mode. The project owner delegates the work, starting with individuals writing up their own issues.

在决定实现方案之前，我们会深入讨论一个功能。项目负责人撰写规范并收集反馈，直到我们觉得我们有了正确的方法。只有到那时，我们才开始写代码。在建立一个功能之前，花几周的时间来思考是很常见的，但是一旦我们想出了正确的计划，就会直接进入执行模式。项目负责人授权工作，首先从每个人写自己的任务开始。

## 说明

* Linear 是一款研发项目管理工具（[https://linear.app](https://linear.app)）。
* 这些文章是 Linear 发布的一系列他们团队的工作原则和实践。
* 文章使用 [DeepL](https://www.deepl.com/translator) 翻译，然后人工优化。
* 如果你觉得哪里翻译的可以优化，请[提交 issue](https://github.com/flanker/linear-method-zh-cn/issues/new) 或者 [PR](https://github.com/flanker/linear-method-zh-cn/pulls)
* 版权归 Linear 团队所有。
