# pregnancy-body-changes

数据来源：宝宝树孕育app(v8.7.0)

*bady_data.json* 记录宝宝从第21天开始至第287天每日变化

*mom_data.json* 记录妈妈从第21天开始至第287天每日变化

---
## **baby_data.json**

部分字段含义：

|  key   | 含义  |
|  ----  | ----  |
| title  | 主题 |
| summary  | 总结，其实和title一样 |
| day_num  | 怀孕第几天（从第21天开始），与age_type有关 |
| baby_weight  | 宝宝体重（可能为空） |
| baby_length  | 宝宝长度（可能为空） |
| age_type  | 等于2，才是孕期；等于3，是宝宝出生 |

## **mom_data.json**

部分字段含义：

|  key   | 含义  |
|  ----  | ----  |
| title  | 主题 |
| summary  | 总结，其实和title一样 |
| day_num  | 怀孕第几天（从第21天开始），与age_type有关 |
| content  | 内容 |
| age_type  | 等于2，才是孕期；等于3，是宝宝出生 |
