# ICIS论文写作框架指南

## 一、ICIS基本要求

根据[ICIS 2024官方指南](https://icis2024.aisconferences.org/submissions/types-of-submissions/)：

### 1.1 页数限制

| 类型 | 页数限制 | 摘要 |
|------|----------|------|
| **Completed Research** | 16页（单倍行距） | ≤150词 |
| Research-in-Progress | 8页 | ≤150词 |

**注意**：标题、作者、摘要、关键词、参考文献**不计入**页数；正文、图表、附录**计入**页数。

### 1.2 格式要求

- 必须使用ICIS官方模板（PDF格式提交）
- 图片必须为JPG或GIF格式
- 匿名审稿：正文中不能出现作者姓名/机构

---

## 二、论文结构框架（16页版本）

### 建议页数分配

```
┌─────────────────────────────────────────────────────────────┐
│  ICIS Completed Research Paper Structure (16 pages)         │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  1. Introduction                          [2-2.5 pages]     │
│     ├── Hook & Problem Statement                            │
│     ├── Research Gap                                        │
│     ├── Research Questions                                  │
│     └── Contribution Preview                                │
│                                                              │
│  2. Literature Review                     [3-3.5 pages]     │
│     ├── Theoretical Foundation                              │
│     ├── Related Work                                        │
│     └── Research Gap (detailed)                             │
│                                                              │
│  3. Theoretical Framework/Model           [1-1.5 pages]     │
│     ├── Conceptual Model (if applicable)                    │
│     └── Propositions/Framework                              │
│                                                              │
│  4. Methodology                           [2-2.5 pages]     │
│     ├── Research Design                                     │
│     ├── Data Collection                                     │
│     ├── Sample Description                                  │
│     └── Data Analysis Approach                              │
│                                                              │
│  5. Findings                              [4-5 pages]       │
│     ├── Main Findings (with evidence)                       │
│     ├── Tables & Figures                                    │
│     └── Illustrative Quotes                                 │
│                                                              │
│  6. Discussion                            [2-2.5 pages]     │
│     ├── Interpretation of Findings                          │
│     ├── Theoretical Contributions                           │
│     └── Practical Implications                              │
│                                                              │
│  7. Conclusion                            [0.5-1 page]      │
│     ├── Summary                                             │
│     ├── Limitations                                         │
│     └── Future Research                                     │
│                                                              │
│  References                               [不计入页数]        │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

---

## 三、各部分详细写作指南

### 3.1 Introduction（2-2.5页）

**目标**：在2页内让读者理解"为什么这个研究重要"

#### 结构模板：

```markdown
**Paragraph 1: Hook（开门见山）**
- 用一个惊人的数据或现象开场
- 例如："Despite 66% of professionals using GenAI daily, only 46%
  report trusting it (KPMG 2025)"

**Paragraph 2-3: Problem & Gap**
- 指出现有研究的不足
- 例如："Prior research assumes trust and use are positively
  correlated, yet our data reveals a counterintuitive pattern..."

**Paragraph 4: Research Questions**
- 明确提出1-3个研究问题
- 例如：
  RQ1: How do expert users calibrate trust in GenAI over time?
  RQ2: Why do declining trust levels not lead to reduced use?

**Paragraph 5: Contribution Preview**
- 预告本文的3个核心贡献
- 例如：
  1. We identify the Trust-Use Paradox in GenAI adoption
  2. We propose a Trust Ceiling concept
  3. We develop a framework for understanding appropriate reliance
```

#### 您的论文应用：

```markdown
**Hook**：
"A recent global study of 48,000 individuals across 47 countries
reveals a puzzling phenomenon: as AI adoption increases, trust
decreases (KPMG/Melbourne Business School 2025). Our in-depth
investigation of 49 young professionals uncovers why the most
skeptical users are often the heaviest users."

**Gap**：
"Existing literature on trust calibration (Lee & See 2004) assumes
trust and reliance move together. However, emerging evidence of a
'trust paradox' (PLOS One 2023) challenges this assumption..."

**RQ**：
RQ1: What patterns of trust calibration emerge among expert GenAI users?
RQ2: How do users resolve the tension between declining trust and
     increasing dependence?
RQ3: What coping strategies do users develop to manage skill
     degradation concerns?
```

---

### 3.2 Literature Review（3-3.5页）

**目标**：展示你对领域的深度理解，并明确定位你的贡献

#### 结构模板：

```markdown
**2.1 Trust in Automation and AI** [~1 page]
- Lee & See (2004) definition
- Trust beliefs vs. behaviors (Wang et al. 2008)
- Recent developments in GenAI trust

**2.2 The Trust-Use Paradox** [~1 page] ← NEW SECTION
- AI Trust Paradox definition (Wikipedia, PLOS One 2023)
- Global evidence (KPMG 2025)
- Theoretical explanations

**2.3 Cognitive Offloading and Skill Concerns** [~0.5 page] ← NEW SECTION
- Deskilling literature (Thiele 2025)
- Cognitive atrophy concerns (Polytechnique Insights)
- User awareness of skill degradation

**2.4 Appropriate Reliance** [~0.5 page]
- Definition (Talone 2019)
- Relationship to trust calibration
- Gap: How do users achieve AR in practice?

**2.5 Research Gap** [~0.5 page]
- Summarize what we don't know
- Position your study
```

---

### 3.3 Methodology（2-2.5页）

**目标**：让读者相信你的方法是严谨的

#### 对于定性研究的关键要素：

```markdown
**3.1 Research Design**
- Qualitative exploratory study
- Justification for qualitative approach

**3.2 Data Collection**
- Semi-structured interviews
- Interview protocol summary
- Duration and format

**3.3 Sample**
| Characteristic | Description |
|----------------|-------------|
| Sample Size | 49 participants |
| Age Range | Early 20s to mid-40s |
| Background | Young professionals, researchers, students |
| Experience | 2-5 years of GenAI use |
| Geography | Singapore, China, Malaysia, Mexico |

**3.4 Data Analysis**
- Thematic analysis approach
- Coding process (initial → axial → selective)
- Trustworthiness measures
```

#### 表格示例（您的数据）：

| Demographics | N | % |
|--------------|---|---|
| **Gender** | | |
| Male | 35 | 71% |
| Female | 14 | 29% |
| **Education** | | |
| PhD/Postdoc | 18 | 37% |
| Masters | 15 | 31% |
| Undergraduate | 10 | 20% |
| Professional | 6 | 12% |
| **Primary Tool** | | |
| ChatGPT | 38 | 78% |
| Claude | 5 | 10% |
| Multiple | 6 | 12% |

---

### 3.4 Findings（4-5页）— 最重要的部分

**目标**：用数据讲故事，让发现"活"起来

#### 结构建议（Triple Paradox框架）：

```markdown
**4.1 Trust Trajectories Overview** [~1 page]
- Table summarizing 5 patterns
- Distribution across sample

**4.2 Paradox 1: Trust-Use Decoupling** [~1.5 pages]
- Pattern description
- Key cases: R46, R45
- Illustrative quotes
- Table: Trust level vs. Usage frequency

**4.3 Paradox 2: Skill Anxiety-Dependence Loop** [~1 page]
- Pattern description
- Key cases: R47, R48, R49
- Illustrative quotes
- User coping strategies

**4.4 Paradox 3: Sycophancy-Skepticism Tension** [~1 page]
- Pattern description
- Key cases: R47, R48
- User expectations vs. AI behavior
```

#### 引用格式示例：

> **Trust-Use Decoupling**
>
> Counterintuitively, participants who reported declining trust often exhibited the highest usage frequency. R46, whose trust dropped from 50% to 30% over two years, exemplifies this pattern:
>
> *"I seem to trust the AI less...maybe around 30. [But] I use it every day...I built my own chatbot using API calls to various models."* (R46, Learning Science Masters Student)
>
> This participant's response illustrates a sophisticated form of engagement where distrust does not lead to disuse, but rather to more selective and validated use.

---

### 3.5 Discussion（2-2.5页）

**目标**：解释发现的意义，连接回文献

#### 结构模板：

```markdown
**5.1 Theoretical Contributions**
- Contribution 1: Trust-Use Decoupling concept
  - How it extends Lee & See (2004)
  - Alignment with KPMG (2025) global findings

- Contribution 2: Trust Ceiling phenomenon
  - New concept from grounded data
  - Quote: "My cap will be around 75%" (R45)

- Contribution 3: Informed Distrust as adaptive behavior
  - Reframe: Declining trust ≠ failure
  - Alignment with Appropriate Reliance

**5.2 Practical Implications**
- For AI Design: Support healthy skepticism
- For Training: Acknowledge the paradox
- For Organizations: Policy implications

**5.3 Limitations & Future Research**
- Sample limitations
- Methodological limitations
- Future directions
```

---

### 3.6 Conclusion（0.5-1页）

**目标**：简洁有力地总结

```markdown
**Summary** (1 paragraph)
Restate main findings and contributions

**Key Takeaway** (1-2 sentences)
"Trust degradation in GenAI should not be viewed as failure,
but as epistemic maturation—a sign that users are developing
appropriate reliance through informed skepticism."

**Closing** (1 sentence)
End with forward-looking statement
```

---

## 四、ICIS审稿人关注点

根据[AIS审稿标准](https://aisel.aisnet.org/misqe/reviewprocess.html)，审稿人会评估：

| 评估维度 | 关键问题 |
|----------|----------|
| **Contribution** | 对IS领域有什么新贡献？ |
| **Theoretical Grounding** | 理论基础是否扎实？ |
| **Methodological Rigor** | 方法是否严谨？ |
| **Clarity** | 写作是否清晰？ |
| **Relevance** | 对实践有什么意义？ |

---

## 五、您的论文改进清单

### 立即行动：

- [ ] 更新样本量：14 → 49
- [ ] 完成"AI Anxiety"章节
- [ ] 添加Trust-Use Paradox文献
- [ ] 增加Skill Degradation文献
- [ ] 更新人口统计表

### 结构调整：

- [ ] Introduction增加"paradox"角度的hook
- [ ] Literature Review增加2.2和2.3节
- [ ] Findings重组为Triple Paradox框架
- [ ] Discussion增加3个明确贡献

### 内容强化：

- [ ] 增加R43-R49的引用
- [ ] 添加Trust Ceiling概念
- [ ] 引用2024-2025最新文献

---

## 六、参考文献来源

- [ICIS 2024 Submission Guidelines](https://icis2024.aisconferences.org/submissions/types-of-submissions/)
- [ICIS Paper Templates](https://icis2024.aisconferences.org/paper-templates-pcs-guide-for-authors/)
- [MISQ Author Guidelines](https://misq.umn.edu/misq)
- [AIS Electronic Library](https://aisel.aisnet.org/)
- [ICIS 2024 Best Papers](https://aisnet.org/news/690199/ICIS-2024-Best-Paper-Awards-Showcase-Groundbreaking-IS-Research.htm)
- [Trust in AI Research](https://www.nature.com/articles/s41599-024-04044-8)
- [Qualitative Research Writing Guide](https://delvetool.com/blog/guide-qualitative-research-paper-formats)

---

*指南完成时间：2025年1月*
