# 🏆 The Inclusive Engineer

## High-Impact Accessibility & Quality Audit

### 🌐 Target Website

https://ecommercebs.vercel.app/

## 🛠 Tools Used

- BrowserStack Website Scanner
- BrowserStack Workflow Analyzer
- WCAG 2.1 AA Standard

## 📊 Executive Summary

- Total Accessibility Issues (Scanner): **35 + 1 (Including Performance Issue)**
- Total Accessibility Issues (Workflow): **304**

### 🔎 Accessibility Scanner – Severity Breakdown

- critical: 17
- serious: 13
- moderate: 5

### 🔎 Workflow Analyzer – Severity Breakdown

- serious: 143
- critical: 111
- moderate: 50

## 🚀 Performance Snapshot (Top Metrics Preview)

Below is a preview of performance metrics extracted from BrowserStack Performance Report:

| URL                             | Score |     LCP |      TBT |        CLS |     FCP |    TTFB |
| :------------------------------ | ----: | ------: | -------: | ---------: | ------: | ------: |
| https://ecommercebs.vercel.app/ |    65 | 4.82237 | 0.025115 | 0.00152012 | 4.76318 | 0.01424 |

## 🎯 Key Accessibility Risks Identified

- Missing alternative text for images.
- Low color contrast violations.
- Form fields without associated labels.
- Buttons without accessible names.
- Keyboard navigation and focus visibility issues.
- Improper or missing ARIA roles.

## 💡 Recommended Remediation

- Add meaningful `alt` attributes to images.
- Maintain minimum contrast ratio of 4.5:1.
- Associate inputs with `<label>` elements.
- Use descriptive text or `aria-label` for buttons.
- Ensure visible keyboard focus states.
- Validate ARIA roles against WAI-ARIA guidelines.

## 📂 Raw Reports Included in Repository

- Accessibility_Scan_Report.csv
- Ecommercebs Workflow_Report.csv
- performance_report_ecommercebs.vercel.app.csv

## 📎 Proof of Execution

All scans were executed using BrowserStack’s Accessibility, Performance, Visual, and Responsive testing tools. Public shareable reports are provided below:

---

### 🔍 Accessibility Reports

- **Workflow Analyzer Report**  
  🔗 https://accessibility.browserstack.com/public_report?type=workflowScan&token=tok_d9d77faebb9788eaccfaae36d9c20d42a68335741fb9dc43c30c6c8e2a1322d82a77906e0071000b07dfa09a5b4469f9bd5cbadf26f38f707e71d20026ae2acc

- **Website Scanner Accessibility Report**  
  🔗 https://accessibility.browserstack.com/public_report?type=scanner&token=tok_af3888b7f465a20f3c2be367a19c1e9309231552cc646494af999db01beedddaf5abe9be3adc3692d70a4a37e1259b12c416f3086e79f5a591a002aa9a9d1c2d

---

### ⚡ Performance Report

- **BrowserStack Performance Scanner Report**  
  🔗 https://scanner.browserstack.com/public-report/performance?token=tok_2f7b979392a81e7948e01ac3ebcd26b238d46d71d853242ac4bc6aaaf62df0ea_default

---

### 🎨 Visual & Responsive Reports

- **Visual Regression Scan (Percy)**  
  🔗 https://percy.io/b7c8f725/visual_scanner/CS_ecommercebs.vercel.app-20_CS-3cd67a86/builds/47117362/changed/2494691911?aiToggleEnabled=disabled&browser=firefox&browser_ids=69%2C70&group_snapshots_by=similar_diff&subcategories=approved&viewLayout=side-by-side&viewMode=new&width=1280&widths=1280

- **Responsive Design Scan (Percy)**  
  🔗 https://percy.io/b7c8f725/responsive_scanner/CS_ecommercebs.vercel.app-20_CS-3cd67a86/builds/47117363/changed/2494691916?aiToggleEnabled=disabled&browser=firefox&browser_ids=69%2C70&group_snapshots_by=similar_diff&subcategories=approved&viewLayout=side-by-side&viewMode=new&width=1920&widths=375%2C1280%2C1920

---

### 🧾 Additional BrowserStack Checks (0 issues found)

The following checks returned **no issues** (CSV exports were empty), so the CSVs are **not** included in the repository — the public report links are provided below for verification:

- **Broken Link Report (Functional Scanner)**  
  🔗 https://scanner.browserstack.com/public-report/functional?token=tok_0f009fffb23021cac96b2fb5f10e02089abfd6ffc4afdd9c36d036db393487fb_default

- **Website Form Report (Form Checker)**  
  🔗 https://scanner.browserstack.com/public-report/form_checker?token=tok_720f44d5fbe452f26f16ed6c802beac26cb3a03e9aa048a21d67f53fa707d77a_default

- **Spell Report (Content Checker)**  
  🔗 https://scanner.browserstack.com/public-report/content_checker?token=tok_896fbe064218232adc1911c840445024a324c011a02b5ebbb4d39e6eb25495f2_default

> **Note:** The three reports above were clean (0 issues), so I did not add empty CSV files to the repository — only the public report URLs are included here.

---

Report for Hackathon Submission – The Inclusive Engineer

---
