# LiuNengAI Subscription Cost Calculator · 订阅成本计算器

比较两份订阅的月均费用、全年费用和每个实际使用日的成本。免费、免登录，输入在当前浏览器计算；单个 HTML 文件可离线使用。

[在线使用计算器](https://liunenglabs.xyz/guides/subscription-cost/) · [English calculator](https://liunenglabs.xyz/guides/subscription-cost/en/) · [查看免费工具与指南](https://liunenglabs.xyz/guides/?utm_source=github)

## 下载使用

[下载 v1.0.0 离线 HTML](https://github.com/a941249849/liunengai-subscription-cost/releases/download/v1.0.0/liunengai-subscription-cost.html) · [版本说明与 SHA-256 校验](https://github.com/a941249849/liunengai-subscription-cost/releases/tag/v1.0.0)

打开仓库中的 `index.html`，点击 GitHub 的 **Download raw file** 下载，保存后用浏览器打开。也可以下载整个仓库的 ZIP 后打开该文件。无需安装、账号、API 密钥或 AI 订阅。工具界面为中文；导航链接需要联网，离线文件中的站内相对导航请改用上面的在线链接。

## 如何比较

1. 给方案 A / B 填写名称、每次付款金额和付款周期（月付或年付）。金额按人民币填写。
2. 输入每月实际使用天数（1～31 的整数），查看结果。
3. 核对后可复制结果或下载文本分享。示例数字用于演示，不是当前市场报价或购买承诺。

月付：全年费用 = 每次金额 × 12；月均费用 = 每次金额。
年付：全年费用 = 每次金额；月均费用 = 每次金额 ÷ 12。
每个使用日成本 = 月均费用 ÷ 每月实际使用天数。

例如：月付 99 元与年付 1,200 元、每月使用 20 天，折合月均 99 元与 100 元；全年 1,188 元与 1,200 元；每个使用日 4.95 元与 5.00 元。这不是实际按天计费。

计算假设价格不变且连续使用 12 个月。不判断两份方案的功能是否相同，也不包含未填写的税费、优惠或额外费用。

## 隐私与范围

- 全部应用代码在一个 HTML 文件中，无外部脚本或依赖。
- 输入不上传、不写入本地存储；该文件不含统计脚本。
- 不调用 AI、不拉取实时价格、不处理付款。
- 页面链接点击后会访问其他网站或本站页面；那些页面有自己的统计与隐私说明。

## English

A free Chinese-language calculator for comparing two CNY-denominated subscription plans: monthly equivalent, annual total and cost per active day. Choose monthly or annual billing and enter the number of active days per month.

[Download the offline HTML release](https://github.com/a941249849/liunengai-subscription-cost/releases/tag/v1.0.0) or [try the live calculator](https://liunenglabs.xyz/guides/subscription-cost/). You can also download `index.html` using GitHub's **Download raw file**, then open it locally. The application is a single self-contained HTML file with no dependencies, signup, AI calls, input uploads or local-storage persistence. Navigation links need an internet connection; relative navigation in the offline file is best replaced by the live link above.

Example: CNY 99/month versus CNY 1,200/year at 20 active days per month gives monthly equivalents of 99 and 100, annual totals of 1,188 and 1,200, and daily equivalents of 4.95 and 5.00. These are entered assumptions, not current offers, real per-day billing or a claim that the plans have equal features.

## License and operator

MIT © 2026 LiuNeng AI. See [LICENSE](LICENSE). This republishes the tool's existing public MIT source without changing its calculation logic. Documentation was prepared with AI assistance.

由刘能AI / LiuNengAI 独立运营。网站另有付费的自有账号 ChatGPT 订阅充值服务；计算器免费，不要求购买。我们不是 OpenAI 官方网站。

LiuNengAI is an independent operator, not OpenAI. The associated website has a separate paid service for ChatGPT subscription recharge on customers' own accounts; this free calculator requires no purchase.

## English interface

[Use the English calculator](https://liunenglabs.xyz/guides/subscription-cost/en/) or download [`index.en.html`](index.en.html) with GitHub’s **Download raw file** and open it in your browser. Both interfaces use CNY; no currency conversion is performed. The English interface was adapted with AI assistance from the existing MIT source, keeping the numeric formula and validation limits.

The current source fixes the reset button in both interfaces. The older Chinese v1.0.0 release remains available unchanged and predates that fix; use the current HTML files for the corrected reset behavior.
