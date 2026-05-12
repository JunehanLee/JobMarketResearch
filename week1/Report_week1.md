# Week 01: Market-Level Signals and AI Capability Evidence

## 1. Objective

The objective of this week is to assess whether market-level evidence suggests increasing pressure in the UK junior / entry-level job market, and whether AI adoption and capability progress may be changing why employers hire juniors and what they expect from them.

This is an interim, signal-based analysis. The goal is not to conclude that AI has caused junior hiring declines, but to identify whether there are strong enough market and AI-related signals to motivate the next phase of research: JD-level text analysis using crawling and LLM-assisted classification.

---

## 2. Research Questions

This week’s analysis is guided by four research questions:

1. Has the UK job market become tighter, especially for entry-level and junior roles?
2. Do pressured categories overlap with white-collar roles that are more exposed to AI?
3. Are AI adoption and AI capability trends strong enough to plausibly affect junior task expectations?
4. What should be tested next using job-description-level data?

---

## 3. Data Sources

| Source | Used For | Notes |
|---|---|---|
| ONS Vacancy Survey | Overall UK vacancy trend | Used as macro labour-market context |
| Adzuna Job Market Reports | Jobseekers per vacancy, advertised vacancies, salaries, and category-level hiring pressure | Used as directional market evidence |
| GOV.UK AI Adoption Research | AI use cases, business areas using AI, and reported productivity/process impact | Used to understand where AI is being applied in businesses |
| ONS AI adoption studies | Business-level AI adoption trends | Used to assess whether business AI use is increasing |
| YouGov AI at Work survey | Individual worker AI usage | Used to capture bottom-up AI use at work |
| Epoch AI benchmarks | Frontier AI capability progress | Used to assess AI performance in coding, reasoning, and multimodal tasks |

---

## 4. Methodology

This week uses secondary, market-level evidence rather than raw job description data.

The analysis combines three layers of evidence:

1. **UK labour-market context**  
   I use ONS vacancy data and Adzuna market indicators to assess whether the UK job market has become tighter overall.

2. **Category-level hiring pressure**  
   I use Adzuna annual-change charts to identify whether Graduate and white-collar categories repeatedly appear under pressure.  
   February reports are treated as a proxy for January hiring momentum, while November reports are treated as a proxy for the October graduate / junior recruitment cycle.

3. **AI adoption and capability signals**  
   I combine business adoption evidence, individual usage evidence, and AI benchmark trends to assess whether AI is becoming relevant to junior knowledge-work tasks.

Adzuna category charts are treated as **directional evidence**, not precise raw time-series data.  
The purpose of this week is to identify signals that justify deeper JD-level analysis, not to establish causality.

---

## 5. Key Findings

### Finding 1: The UK job market appears tighter than the post-pandemic peak period.

ONS vacancy data shows that UK vacancies have fallen from the post-pandemic peak and declined again in early 2026. Adzuna’s jobseekers-per-vacancy indicator also suggests that competition has increased.

This suggests that the overall labour market has become more competitive for jobseekers.

**Figure 1. UK vacancy trend**

![ONS vacancy trend](./figures/fig01_ons_vacancy_trend.png)

**Figure 2. Jobseekers per vacancy**

![Jobseekers per vacancy](./figures/fig02_adzuna_jobseekers_per_vacancy.png)

---

### Finding 2: Graduate and several white-collar categories show repeated negative signals.

Adzuna category-level charts suggest repeated pressure in Graduate and several white-collar or knowledge-work-adjacent categories, including:

- Graduate
- IT
- Admin
- PR / Advertising / Marketing
- Accounting & Finance
- Consultancy
- Scientific & QA
- HR & Recruitment

At the same time, some categories such as Teaching, Trade & Construction, Travel, Legal, and some physical or people-facing roles appear more resilient in selected periods.

This does not prove why these roles are under pressure, but it shows where pressure appears.

**Figure 3. Category-level hiring pressure: January hiring momentum**

![Adzuna category pressure Feb 2026](./figures/fig03_adzuna_category_pressure_feb2026.png)

**Figure 4. Category-level hiring pressure: October graduate / junior cycle**

![Adzuna category pressure Nov 2025](./figures/fig04_adzuna_category_pressure_nov2025.png)

---

### Finding 3: AI adoption is increasing in both businesses and individual work practices.

Business-level evidence suggests that AI adoption is increasing across UK firms, especially in larger organisations and data-intensive or professional sectors.

Individual-level evidence also suggests that AI is increasingly used at work, particularly for tasks such as:

- Summarising information
- Research
- Editing and checking text
- Writing support
- Coding support
- Analysis and documentation

This matters because these tasks overlap with many routine junior white-collar responsibilities.

---

### Finding 4: Frontier AI capability is improving in tasks relevant to junior knowledge work.

Epoch AI benchmark data shows rapid improvement across several capability areas:

| Benchmark | What it measures | Relevance to junior white-collar work |
|---|---|---|
| SWE-bench Verified | Real software issue resolution | Coding support, debugging, technical junior work |
| GPQA Diamond | Expert scientific reasoning | Research-heavy knowledge work |
| VPCT | Visual / physical reasoning | Charts, slides, dashboards, visual material interpretation |
| FrontierMath Tier 4 | Hard abstract reasoning | Capability ceiling and advanced reasoning progress |

SWE-bench Verified is particularly relevant because it evaluates real-world software issue resolution, which overlaps with junior technical and data-related work.

**Figure 5. Frontier AI capability progress**

![Epoch AI benchmark trends](./figures/fig05_epoch_ai_benchmarks.png)

---

### Finding 5: Current evidence suggests a plausible pressure mechanism, not proof of causality.

The current evidence does not prove that AI caused junior hiring declines.

However, there is a notable overlap between:

- categories showing hiring pressure, and
- task areas where AI is increasingly adopted or rapidly improving.

This suggests a working hypothesis: AI may be increasing augmentation or substitution pressure on routine junior white-collar tasks, making employers more selective in entry-level hiring.

---

## 6. Interim Interpretation

At this stage, the evidence should be interpreted as **market-level signals**, not final proof.

The UK labour market appears tighter overall, and Graduate / white-collar categories show repeated pressure in Adzuna snapshots. At the same time, AI adoption is increasing among businesses and individuals, while frontier AI models are improving rapidly in coding, reasoning, research, and multimodal understanding.

The most reasonable interim interpretation is:

> AI may not be the sole cause of junior hiring pressure, but it may be contributing to a shift in how employers value routine entry-level knowledge-work tasks.

This hypothesis needs to be tested using actual job description data.

---

## 7. Limitations

This analysis has several limitations:

- The current evidence is based on macro and category-level sources, not individual job descriptions.
- Adzuna category charts provide directional signals rather than raw downloadable time-series data.
- Vacancy decline does not automatically imply AI-driven job replacement.
- AI adoption does not necessarily mean headcount reduction.
- AI benchmark performance does not fully represent workplace performance.
- Causality cannot be established at this stage.

Because of these limitations, the next phase will move from market-level evidence to JD-level analysis.

---

## 8. Next Steps

The next phase will test whether the market-level signals identified this week are reflected in actual job descriptions.

### Planned next phase: JD-level text analysis

1. Collect UK junior / graduate / entry-level job descriptions.
2. Classify roles by JD content rather than job title.
3. Use LLM-assisted keyword extraction and clustering.
4. Track skill requirements, AI-related language, business impact, communication, ownership, and experience inflation.
5. Compare role clusters across:
   - Data Analyst
   - Data Scientist
   - AI Engineer / ML Engineer
   - Analytics Consultant
   - Business Analyst
   - Product / Commercial Analyst

### Expected outputs

- Keyword frequency dashboard
- Role cluster map
- Skill and requirement matrix
- Market pressure matrix
- Evidence-based positioning framework

The next phase will move from market-level signals to role-level evidence, testing whether the pressure seen in hiring data is reflected in JD language and requirements.

---

## 9. References

A separate reference list is maintained in [`references.md`](./references.md).

Key source categories include:

- ONS labour market and vacancy data
- Adzuna UK job market reports
- GOV.UK AI adoption and business data use reports
- YouGov AI at Work survey
- Epoch AI benchmark data
