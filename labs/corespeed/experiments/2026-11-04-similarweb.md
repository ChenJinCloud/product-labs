# CoreSpeed Similarweb 抓取工具实测

测试日期：2026-11-04。通过 CoreSpeed MCP 工具目录查找并运行三个第三方 Similarweb 抓取器；它们读取公开数据，并非 Similarweb 官方 API。[CoreSpeed 说明](https://corespeed.io/blog/corespeed-for-seo)

## 结果

| 域名 | 抓取器 | 结果 | 费用 |
|---|---|---|---:|
| corespeed.io | `tri_angle/fast-similarweb-scraper` | 完成，0 条 | 1.05 credits |
| corespeed.io | `curious_coder/similarweb-scraper` | 完成，0 条 | 7.5 credits |
| wikipedia.org | `tri_angle/fast-similarweb-scraper` | 完成，0 条 | 1.05 credits |
| wikipedia.org | `curious_coder/similarweb-scraper` | 完成，0 条 | 7.5 credits |
| wikipedia.org | `radeance/similarweb-scraper` | 完成，1 条 | 13.5 credits |

五次合计 30.60 credits，按 [1,000 credits = $1](https://corespeed.io/docs/billing) 换算约 $0.0306。空结果也收取了运行费；成功的一次按当时工具显示为启动 1.5 credits 加一条结果 12 credits。工具价格可能变化，运行前应重新查看。

## 可返回的数据与对照

成功结果包含月访问量、排名、跳出率、访问时长、每次访问页数、流量渠道和国家分布等字段。以 2026 年 9 月、全球流量的 Similarweb 页面作对照：CoreSpeed 返回维基百科约 33.7105 亿次访问、全球排名 11、跳出率 54.0879%、每次访问 3.2294 页；页面显示约 33.71 亿、排名 11、54.09%、3.23 页，均在页面显示精度内一致。

国家字段不一致：页面显示美国占 20.22%，抓取结果显示 27.07%。抓取结果同时给出的美国月访问量约 913 万，与总量 33.71 亿乘 27.07% 得出的约 9.13 亿不自洽。原因未核实，不能直接采用该国家明细。

这次检查的是抓取结果与另一个 Similarweb 页面的一致性，没有与网站自身分析数据比较，不能计算对真实流量的误差。两次空结果也不足以确定是工具问题还是数据覆盖限制。
