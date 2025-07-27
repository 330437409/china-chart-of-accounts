# china-chart-of-account
Template of China Chart of Account for ERPNext 12+


注意：下载模板后，请在模板中填写详细信息，如下面实例屏幕截图所示。请确保为科目类型“Cost of Goods Sold”，“Depreciation”，“Fixed Asset”，“Payable”，“Receivable”，“Stock Adjustment”创建科目。这些帐户的根类型必须是Asset，Liability，Income，Expense 和 Equity 中的一种。科目类型只能定义为“科目类型中英文对应表”中的内容或者留空，并且 Bank, Cash, Stock 这 3 个类型只能定义为分组且不包含子科目。

![](https://cdn.jsdelivr.net/gh/r3f/img/2020/04/10/image-13:39:17.png)

# Contributions
![](https://cdn.jsdelivr.net/gh/r3f/img/2020/04/10/image-13:45:26.png)
# 科目与跟类型

| Account Name  | Root Type |
| ------ | --------- |
| 资产 | Asset |
| 负债 | Liability |
| 权益 | Equity |
| 收入 | Income ||
| 费用 | Expense |

# 科目类型中英文对应表

| Account Type  | 科目类型 |
| ------------- | ------------- |
| Asset Received But Not Billed | 在途资产科目（已收到，未开票） |
| Bank | 银行 |
| Cash | 现金 |
| Chargeable | 可记账的 |
| Capital Work in Progress | 在途资本 |
| Cost of Goods Sold | 销货成本 |
| Depreciation | 折旧 |
| Equity | 权益 |
| Expense Account | 费用科目 |
| Expense Included In Asset Valuation | 包含在资产评估价中的费用科目 |
| Expense Included In Valuation | 计入库存评估价的费用科目 |
| Fixed Asset | 固定资产 |
| Income Account | 收入科目 |
| Payable | 应付 |
| Receivable | 应收账款 |
| Round Off | 四舍五入 |
| Stock | 库存 |
| Stock Adjustment | 库存调整 |
| Stock Received But Not Billed | 已收货未开票/在途物资:GR/IR |
| Tax | 税项 |
| Temporary | 临时 |


介绍
ERPNext 中国会计科目表. 逐渐完善中. 现在大项已经完成.

软件架构
json 文件, 贴上即可用.
将json文件贴到 /URL2your_erpnext/apps/erpnext/erpnext/accounts/doctype/account/chart_of_accounts/verified

使用说明
在创建公司时选择标准模板,科目表选择"CN-2016-2020会计准则科目表" 输入图片说明
# License
[GNU GPL V3](https://github.com/r3f/china-chart-of-accounts/blob/master/LICENSE)
