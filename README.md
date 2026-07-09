# POC 订阅测试仓库

> 用于测试 [NucleiScanner Enhanced](https://github.com/xmoeo/nuclei-scanner-enhanced) 的 POC 订阅管理功能

## 仓库结构

```
├── cves/                    # CVE 漏洞模板 (critical/high)
│   ├── CVE-2025-test-poc1.yaml  # SQL注入 - critical
│   └── CVE-2025-test-poc2.yaml  # XSS - high
├── vulnerabilities/          # 漏洞模板 (medium)
│   └── CVE-2025-test-poc3.yaml  # 路径遍历 - medium
└── misconfig/               # 配置问题模板 (low)
    └── CVE-2025-test-poc4.yaml  # 信息泄露 - low
```

## 使用方式

在 NucleiScanner Enhanced POC 管理 → 订阅管理中，添加本仓库地址：

```
https://github.com/xmoeo/poc-subscription-test
```

## 模板说明

| 模板 | 严重程度 | 分类 | 描述 |
|------|---------|------|------|
| CVE-2025-test-poc1 | critical | cves | SQL 注入检测 |
| CVE-2025-test-poc2 | high | cves | XSS 检测 |
| CVE-2025-test-poc3 | medium | vulnerabilities | 路径遍历检测 |
| CVE-2025-test-poc4 | low | misconfig | 信息泄露检测 |
