---
title: 关于 GitHub Enterprise Support
intro: '{{ site.data.variables.product.prodname_ghe_server }} Support 可以帮助您排查 {{ site.data.variables.product.prodname_ghe_server }} 设备上出现的问题。'
redirect_from:
  - /enterprise/admin/enterprise-support/about-github-enterprise-support
versions:
  enterprise-server: '*'
---

{% note %}

**注意**：{{ site.data.reusables.support.data-protection-and-privacy }}

{% endnote %}

### 关于 {{ site.data.variables.contact.enterprise_support }}

{{ site.data.variables.product.prodname_ghe_server }} 包括英语版和日语版的 {{ site.data.variables.contact.enterprise_support }}。

您可以通过我们的支持门户联系 {{ site.data.variables.contact.enterprise_support }} 以获取以下帮助：
 - 安装和使用 {{ site.data.variables.product.prodname_ghe_server }}
 - 识别并验证可疑错误的原因

除了 {{ site.data.variables.contact.enterprise_support }} 的所有好处外，{{ site.data.variables.contact.premium_support }} 还提供：
  - 通过我们的支持门户网站全天候提供书面支持
  - 全天候电话支持
  - 保证初始响应时间的服务等级协议 (SLA)
  - 高级内容访问权限
  - 按时健康状态检查
  - 管理的服务

更多信息请参阅“[关于 {{ site.data.variables.product.prodname_ghe_server }} 的 {{ site.data.variables.contact.premium_support }}](/enterprise/admin/guides/enterprise-support/about-github-premium-support-for-github-enterprise-server)”。

{{ site.data.reusables.support.scope-of-support }}

### 联系 {{ site.data.variables.contact.enterprise_support }}

{{ site.data.variables.contact.enterprise_support }} 客户可以使用 {{ site.data.variables.contact.contact_enterprise_portal }} 以书面形式报告问题。

### 运行时间

#### 英语支持

对于标准的非紧急问题，我们提供每天 24 小时、每周 5 天的英语支持，不包括周末和美国国家法定节假日。 </em>GitHub 每天二十四 (24) 小时、每周五 (5) 天（不包括周末和美国全国性假日）对软件提供标准技术支持，不收取额外费用。 标准响应时间为 24 小时。

对于紧急问题，我们每周 7 天、每天 24 小时提供服务，即使在美国法定节假日也不例外。 </em>GitHub 每天二十四 (24) 小时、每周五 (5) 天（不包括周末和美国全国性假日）对软件提供标准技术支持，不收取额外费用。

#### 日语支持

对于非紧急问题，日语支持的服务时间为周一至周五上午 9:00 至下午 5:00（日本标准时间），不包括日本的法定节假日。 对于紧急问题，我们每周 7 天、每天 24 小时提供英语支持，即使在美国法定节假日也不例外。 </em>GitHub 每天二十四 (24) 小时、每周五 (5) 天（不包括周末和美国全国性假日）对软件提供标准技术支持，不收取额外费用。

For a complete list of U.S. 有关 {{ site.data.variables.contact.enterprise_support }} 遵守的美国和日本法定节假日的完整列表，请参阅“[节假日安排](#holiday-schedules)”。

### 节假日安排

For urgent issues, we can help you in English 24 hours per day, 7 days per week, including on U.S. and Japanese holidays.

#### 美国的节假日

{{ site.data.variables.contact.enterprise_support }} observes these U.S. holidays. {{ site.data.variables.contact.enterprise_support }} 会庆祝这些美国节假日，但我们的全球支持团队可以回答紧急事件单。

| U.S. 美国节假日  | Date observed in {{ "now" | date: "%Y" }} |
| ----------- | ------------------------- | ------------- |
| 元旦          | 1 月 1 日                   |               |
| 马丁·路德·金纪念 日 | 1 月的第三个星期一                |               |
| 总统日         | 2 月的第三个星期一                |               |
| 阵亡将士纪念日     | 5 月的最后一个星期一               |               |
| 独立日         | 7 月 4 日                   |               |
| 劳动节         | 9 月的第一个星期一                |               |
| 老兵节         | 11 月 12 日                 |               |
| 感恩节         | 11 月的第四个星期四               |               |
| 感恩节后的第一天    | 11 月的第四个星期五               |               |
| 平安夜         | 12 月 24 日                 |               |
| 圣诞节         | 12 月 25 日                 |               |
| 圣诞节后的第一天    | 12 月 26 日                 |               |
| 新年除夕        | 12 月 31 日                 |               |

#### 日本节假日

{{ site.data.variables.contact.enterprise_support }} 在 12 月 28 日至 1 月 3 日以及 [国民の祝日について - 内閣府](https://www8.cao.go.jp/chosei/shukujitsu/gaiyou.html)中所列的节假日不提供日语支持。

{{ site.data.reusables.enterprise_enterprise_support.installing-releases }}

### 为支持事件单分配优先级

联系 {{ site.data.variables.contact.enterprise_support }} 时，可为事件单选择以下四种优先级之一：{{ site.data.variables.product.support_ticket_priority_urgent }}、{{ site.data.variables.product.support_ticket_priority_high }}、{{ site.data.variables.product.support_ticket_priority_normal }} 或 {{ site.data.variables.product.support_ticket_priority_low }}。

{{ site.data.reusables.support.github-can-modify-ticket-priority }}

{{ site.data.reusables.support.ghes-priorities }}

### 解决和关闭支持事件单

{{ site.data.reusables.support.enterprise-resolving-and-closing-tickets }}

### 延伸阅读

- [关于 {{ site.data.variables.product.prodname_ghe_server }} 的常见问题](https://enterprise.github.com/faq)
- 关于“[{{ site.data.variables.product.prodname_ghe_server }} 许可协议](https://enterprise.github.com/license)”中支持的第 10 节
- “[联系 {{ site.data.variables.contact.github_support }}](/enterprise/admin/guides/enterprise-support/reaching-github-support)”
- “[准备提交事件单](/enterprise/admin/guides/enterprise-support/preparing-to-submit-a-ticket)”
- “[提交事件单](/enterprise/admin/guides/enterprise-support/submitting-a-ticket)”