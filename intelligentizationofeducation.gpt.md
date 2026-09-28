# Intelligentization of Education: Research, Academic Literature, and Real-World Implementation

As of **2026**, “intelligentization of education” has moved beyond the earlier concept of simply digitizing teaching materials or putting courses online. The research field is increasingly concerned with how **AI, learning analytics, intelligent tutoring systems, generative AI, multimodal models, knowledge graphs, adaptive learning, and educational data infrastructures** can change the way teaching, learning, assessment, administration, and educational governance operate.

A useful distinction is:

> **Digitalization** makes educational processes digital; **intelligentization** makes those digital processes adaptive, predictive, generative, personalized, and increasingly capable of supporting or automating decisions.

The evidence, however, is uneven. There is relatively mature evidence for **intelligent tutoring systems (ITS), adaptive learning, and learning analytics**, while evidence for **generative-AI-based education is much newer and more mixed**, particularly concerning long-term learning.

---

## 1. Conceptual framework

I would conceptualize intelligent education as a system with **six interacting layers**:

| Layer                         | Main technologies                                 | Typical applications                                 |
| ----------------------------- | ------------------------------------------------- | ---------------------------------------------------- |
| 1. Digital infrastructure     | Cloud, LMS, platforms, APIs, IoT                  | Digital classrooms, online learning                  |
| 2. Educational data           | Student records, clickstream, assessment data     | Learning analytics, dashboards                       |
| 3. Adaptive intelligence      | ML, knowledge tracing, recommender systems        | Personalized learning paths                          |
| 4. Intelligent interaction    | NLP, speech AI, computer vision, agents           | AI tutors, conversational assistants                 |
| 5. Generative intelligence    | LLMs, multimodal GenAI                            | Content creation, feedback, tutoring                 |
| 6. Institutional intelligence | Predictive analytics, AI agents, decision support | Student support, administration, curriculum planning |

This means that **ChatGPT is only one component of educational intelligentization**. The broader research field existed decades before generative AI.

A 2024 meta-review covering **143 AIED literature reviews** found that research is concentrated particularly in China and the United States and that higher education receives substantially more attention than special education. It also found that most research focuses on supporting teachers and students rather than school leaders and other stakeholders. ([Springer Nature][1])

---

# 2. Historical development

The field can roughly be divided into five stages.

### Stage 1 — Computer-Assisted Instruction

**1960s–1980s**

Early systems attempted to provide:

* programmed instruction
* automated exercises
* immediate feedback
* rule-based tutoring

The underlying idea was already close to today's intelligent tutoring:

> diagnose what the learner knows → provide an appropriate task → observe the response → adapt the next task.

---

### Stage 2 — Intelligent Tutoring Systems

**1980s–2000s**

The field developed explicit models of:

* learner knowledge
* domain knowledge
* pedagogical strategies
* misconceptions
* feedback

Representative systems included:

* AutoTutor
* Cognitive Tutor
* Andes
* ALEKS
* ASSISTments

This remains one of the strongest research foundations for intelligent education.

A major meta-analysis covering **107 effect sizes and 14,321 participants** found ITS learning outcomes superior to large-group teacher-led instruction, non-ITS computer instruction, and textbooks/workbooks, while finding no significant difference from individualized human tutoring or small-group instruction. ([DOI][2])

Another meta-analysis of 50 controlled evaluations reported a median improvement of approximately **0.66 standard deviations**, although the magnitude depended substantially on how learning was assessed and how well the implementation aligned with instructional objectives. ([Sage Journals][3])

---

### Stage 3 — Learning Analytics and Adaptive Learning

**2000s–2010s**

With LMS platforms and large educational datasets, research expanded into:

* student behavior prediction
* dropout prediction
* knowledge tracing
* recommendation systems
* adaptive sequencing
* automated feedback
* early-warning systems
* learning dashboards

This represents a major transition:

**from intelligent instruction → intelligent analysis of learning.**

Research increasingly treats the learner as a continuously changing state rather than simply a test score.

---

### Stage 4 — AI + Big Data + Learning Analytics

**2010s–2022**

Machine learning enabled:

* automated essay scoring
* speech recognition
* computer vision
* affective computing
* predictive analytics
* recommender systems
* intelligent assessment
* personalized learning

At the institutional level, AI began supporting:

* admissions
* student retention
* academic advising
* resource allocation
* scheduling
* educational management.

---

### Stage 5 — Generative AI and AI Agents

**2022–present**

The emergence of ChatGPT and foundation models fundamentally changed the research agenda.

The system is no longer merely:

> **“AI determines which question the student should answer.”**

It can now:

> **generate explanations → conduct dialogue → ask questions → critique answers → create examples → summarize → translate → generate learning materials → simulate roles → assist teachers.**

The OECD's 2026 Digital Education Outlook describes GenAI as substantially different from previous educational technologies because it is widely accessible outside institutional control and can function as a **tutor, partner, and assistant**. ([OECD][4])

---

# 3. Major research streams

## 3.1 Intelligent Tutoring Systems

This is probably the most mature research stream.

Typical architecture:

```text
Student
   ↓
Interaction data
   ↓
Learner model
   ↓
Knowledge / competency diagnosis
   ↓
Pedagogical model
   ↓
Next learning activity
   ↓
Feedback
   ↓
Student
```

Important research questions include:

* Can AI accurately diagnose misconceptions?
* How should learner knowledge be represented?
* How should difficulty be adapted?
* What feedback produces durable learning?
* When should AI intervene?
* When should the teacher intervene?

The historical evidence is comparatively strong, although modern LLM-based tutoring should not simply be assumed to reproduce the effects of older ITS.

---

# 4. Learning analytics and educational data mining

This research stream uses data such as:

* test results
* LMS activity
* assignment submissions
* time-on-task
* interaction sequences
* discussion participation
* attendance
* competency profiles.

Typical outputs include:

### Predictive

> “This student has an elevated probability of dropping out.”

### Diagnostic

> “The student appears to have difficulty with quadratic equations.”

### Prescriptive

> “Recommend these three learning activities.”

### Adaptive

> “Change the student's learning pathway based on current mastery.”

A 2024 systematic review of human-centred learning analytics and AIED analyzed **108 papers** and found that although human control was receiving attention, actual end-user involvement in system design remained limited. It specifically highlights student/teacher participation, safety, reliability, trustworthiness, and the balance between human control and automation as important research gaps. ([ScienceDirect][5])

---

# 5. Generative AI in education

This is currently the fastest-growing research area.

Research can be divided into four major uses.

### A. Student → AI

Examples:

* asking questions
* explanations
* language practice
* brainstorming
* coding assistance
* personalized tutoring
* feedback.

### B. Teacher → AI

Examples:

* lesson-plan generation
* quiz generation
* rubric creation
* differentiated materials
* feedback assistance
* translation
* curriculum alignment.

### C. Student + AI

Examples:

* collaborative problem solving
* Socratic dialogue
* debate
* role-play
* writing revision
* inquiry-based learning.

### D. Institution → AI

Examples:

* student advising
* curriculum analysis
* resource classification
* administrative automation
* research assistance
* educational management.

A 2025 systematic review of pedagogical applications in higher education documented the rapid integration of generative AI during its first two years and emphasizes that adoption needs to be considered in relation to teaching and learning design rather than merely tool availability. ([Springer Nature][6])

---

# 6. What does the empirical evidence say?

This is one of the most important issues.

The evidence does **not** support a simple proposition such as:

> “More AI = better education.”

Instead, the emerging evidence suggests:

### AI can improve performance

A 2025 systematic review and meta-analysis examined **69 experimental studies** of ChatGPT interventions. It reported positive effects on academic performance, affective-motivational outcomes and higher-order-thinking propensities, while also identifying methodological limitations and the need for stronger long-term and objective assessments. ([DOI][7])

### But performance ≠ learning

This distinction is fundamental.

A student can produce a better essay with AI without acquiring the underlying ability to write the essay independently.

The OECD's 2026 review explicitly makes this distinction: GenAI can improve task performance without producing learning gains when cognitive work is simply outsourced to the model. Conversely, pedagogically designed GenAI interventions can produce learning gains. ([OECD][4])

A 2025 randomized controlled study of 120 undergraduate students found lower delayed knowledge retention among students who used ChatGPT as a study aid compared with the traditional-learning group. The result was measured 45 days after learning, illustrating why long-term retention needs to be distinguished from immediate task performance. ([DOI][8])

At the same time, another 2025 randomized controlled trial found that a purpose-built AI tutor using research-based pedagogical design produced greater learning in less time than an active-learning classroom condition among college students. ([DOI][9])

These apparently different results are important: **the educational design of AI use is a major moderator.**

---

# 7. The emerging research principle

The research is increasingly moving from:

> **“Does AI improve education?”**

toward:

> **“Under what pedagogical conditions does AI improve learning?”**

This is a much more sophisticated research question.

A useful causal model is:

```text
AI capability
      ↓
AI system design
      ↓
Pedagogical design
      ↓
Teacher orchestration
      ↓
Student interaction
      ↓
Cognitive engagement
      ↓
Learning process
      ↓
Learning outcomes
```

AI capability by itself does not determine the final educational outcome.

---

# 8. Teacher-AI-student relationship

One of the most important conceptual changes is the transition from:

**Teacher → Student**

to:

**Teacher ↔ AI ↔ Student**

UNESCO's 2024 AI Competency Framework for Teachers explicitly describes this emerging teacher–AI–student relationship and proposes **15 teacher competencies** across five dimensions:

1. human-centred mindset
2. ethics of AI
3. AI foundations and applications
4. AI pedagogy
5. AI for professional learning. ([UNESCO][10])

UNESCO also developed a student framework containing **12 competencies** across:

1. human-centred mindset
2. ethics of AI
3. AI techniques and applications
4. AI system design. ([UNESCO][11])

This is significant because intelligentization is increasingly treated as a **human-AI educational ecosystem**, not merely software automation.

---

# 9. AI literacy becomes part of education itself

There are now two separate questions:

### AI for education

Using AI to teach mathematics, language, science, etc.

### Education for AI

Teaching students:

* what AI is
* how models work
* data and algorithms
* AI limitations
* hallucinations
* bias
* privacy
* ethics
* evaluation of AI outputs
* AI-assisted problem solving.

A 2024 scoping review examined 46 studies of AI learning tools in K–12 education and found growing emphasis on AI literacy, pedagogical strategies, learning tools and assessment. ([Springer Nature][12])

A separate systematic review of 47 empirical K–12 studies found positive outcomes from well-designed hands-on AI learning tasks but also identified teacher/student apprehension, difficulties with conceptual understanding, and hardware/resource constraints. ([ScienceDirect][13])

---

# 10. Intelligent assessment

Assessment is likely to be one of the areas most affected by intelligentization.

Traditional:

```text
Teach → Assign → Test → Grade
```

Intelligent:

```text
Teach
 ↓
Continuous evidence collection
 ↓
Knowledge-state estimation
 ↓
Adaptive task
 ↓
AI feedback
 ↓
Teacher review
 ↓
Competency assessment
```

Research areas include:

* automated essay scoring
* automated feedback
* adaptive testing
* knowledge tracing
* AI-generated questions
* oral assessment
* multimodal assessment
* competency-based assessment.

But this introduces a major methodological issue:

**Can an AI-generated assessment accurately measure learning if AI is simultaneously participating in the learning process?**

This is becoming a central research question.

---

# 11. Intelligent educational administration

Intelligentization is not limited to classroom teaching.

AI can be applied to:

### Student services

* academic advising
* career guidance
* student support
* early-warning systems.

### Institutional management

* scheduling
* enrollment
* resource allocation
* facility management
* curriculum planning.

### Educational governance

* system monitoring
* education-quality indicators
* resource allocation
* regional disparities
* forecasting.

The OECD's 2026 report specifically identifies potential uses in institutional operations, including research, learning-pathway analysis, study advising, assessment-item design and educational-resource classification. ([OECD][4])

---

# 12. Real-world implementation: global situation

The implementation landscape can be summarized as follows.

| Area                           | Research maturity | Real-world adoption |
| ------------------------------ | ----------------: | ------------------: |
| LMS/digital platforms          |         Very high |           Very high |
| Learning analytics             |              High |                High |
| Adaptive learning              |              High |       Moderate–high |
| Intelligent tutoring           |              High |            Moderate |
| Automated assessment           |              High |            Moderate |
| AI student advising            |          Moderate |             Growing |
| Generative AI tutoring         |          Emerging |     Rapidly growing |
| AI teacher assistants          |          Emerging |     Rapidly growing |
| AI agents                      |             Early |        Experimental |
| Fully autonomous teaching      |        Very early |             Limited |
| AI-based high-stakes decisions | Contested/limited |             Limited |

The important point is that **research maturity and implementation maturity are not the same thing**.

---

# 13. China: particularly important implementation case

China is one of the most important cases for studying intelligentization at **national education-system scale**.

China launched its National Smart Education Public Service Platform in 2022 as part of the national education digitalization strategy.

By December 2025, China's Ministry of Education reported that the platform had:

* more than **130,000 primary/secondary educational resources**
* more than **12,500 vocational education courses**
* more than **145,000 higher-education courses**
* more than **178 million users**
* users in more than **200 countries and regions**. ([China Ministry of Education][14])

China's 2025 implementation moved explicitly toward intelligentization.

The Ministry reported that the upgraded platform introduced AI-oriented functions, including intelligent agents and AI-supported resource discovery, while describing the strategic direction as moving from digital education toward **smart/intelligent education**. ([China Ministry of Education][15])

The Chinese Ministry of Education also reported that AI applications were being expanded into:

* teaching
* assessment
* admissions/examinations
* employment services
* campus governance.

([China Ministry of Education][14])

This makes China particularly interesting for research because it allows researchers to examine **system-level intelligentization**, rather than only individual AI tools.

---

# 14. United States

The United States has a different implementation model.

Rather than one centralized national education platform, intelligentization is distributed among:

* universities
* school districts
* technology companies
* research universities
* EdTech providers
* federal and state initiatives.

The U.S. Department of Education's Office of Educational Technology published **Artificial Intelligence and the Future of Teaching and Learning** in 2023, addressing AI's implications for teachers, students, educational leaders, policymakers and technology developers. ([ERIC][16])

The research ecosystem is particularly strong in:

* AI tutoring
* educational psychology
* learning sciences
* AI assessment
* human-AI interaction
* university experimentation.

---

# 15. Europe

European implementation emphasizes:

* trustworthy AI
* privacy
* data governance
* teacher competencies
* digital competence
* interoperability
* ethical AI.

The European Commission's Digital Education Action Plan has provided a framework for member-state cooperation and digital education development, with implementation milestones documented through 2025. ([European Education Area][17])

Compared with some highly centralized systems, the European approach places relatively strong emphasis on governance and rights alongside technological adoption.

---

# 16. United Kingdom

The UK Department for Education has developed specific support materials for schools and colleges on using AI safely and effectively. Its current collection, launched in 2025 and updated for the 2026–27 academic year, covers staff and school/college leaders. ([GOV.UK][18])

This represents an important implementation pattern:

> **Government does not necessarily provide one AI teaching system; instead, it provides institutional guidance and capability-building frameworks.**

---

# 17. International policy infrastructure

Three UNESCO resources are particularly important for a literature review.

### 1. Guidance for Generative AI in Education and Research

UNESCO's guidance addresses:

* privacy
* age appropriateness
* ethical validation
* pedagogical design
* regulation
* human-centred AI
* research applications.

([UNESCO][19])

### 2. AI Competency Framework for Teachers

15 competencies / 5 dimensions / 3 progression levels. ([UNESCO][10])

### 3. AI Competency Framework for Students

12 competencies / 4 dimensions / 3 progression levels. ([UNESCO][11])

Together, these provide a useful international conceptual framework for measuring intelligentization.

---

# 18. Major research problems

The literature identifies several unresolved problems.

## 18.1 Learning gains vs. performance gains

This may become the central issue of the field.

Researchers need to distinguish:

**AI-assisted performance**

from

**actual learning acquisition.**

For example:

> Student + AI → excellent essay

does not necessarily imply:

> Student without AI → can independently produce an excellent essay.

---

## 18.2 Short-term vs. long-term effects

Much AI research measures:

* immediate test scores
* student satisfaction
* engagement
* perceived usefulness.

Far fewer studies measure:

* retention after 6–12 months
* transfer
* independent problem-solving
* metacognition
* creativity
* conceptual understanding
* dependence on AI.

UNESCO's broader technology review similarly warns that robust evidence on educational technology's added value remains limited and uneven. ([GEM Report 2023][20])

---

# 19. Teacher role transformation

The central question is not simply:

> “Will AI replace teachers?”

The more researchable question is:

> **Which teacher tasks should be automated, augmented, delegated, or retained as fundamentally human responsibilities?**

A useful analytical framework is:

| Task                  | AI role          |
| --------------------- | ---------------- |
| Information retrieval | Automate         |
| Routine feedback      | Augment/automate |
| Question generation   | Augment          |
| Differentiation       | Augment          |
| Student diagnosis     | AI-assisted      |
| Motivation            | Human + AI       |
| Emotional support     | Primarily human  |
| Ethical judgment      | Human            |
| High-stakes decisions | Human oversight  |
| Relationship building | Human            |
| Curriculum design     | Human + AI       |

This is consistent with UNESCO's emphasis on human agency and teacher competency. ([UNESCO][10])

---

# 20. Privacy and surveillance

Intelligentization requires substantially more student data.

Potential data include:

* behavioral data
* academic records
* voice
* video
* biometric information
* interaction histories
* psychological/affective indicators.

This produces a fundamental tension:

```text
More data
   ↓
More personalization
   ↓
Potentially better adaptation

BUT

More data
   ↓
Greater privacy/security risk
   ↓
Potential surveillance
```

The human-centred learning analytics literature specifically identifies privacy, safety, reliability, trustworthiness and human control as major unresolved issues. ([ScienceDirect][5])

---

# 21. Teacher readiness

Technology deployment is often faster than teacher capability development.

UNESCO's 2024 teacher framework notes that, as of 2022, only **seven countries** had developed AI competency frameworks or professional-development programmes for teachers. ([UNESCO Document Database][21])

Therefore, an intelligentization index should not measure only:

> “Does the school have AI?”

It should also measure:

> “Can teachers use AI pedagogically and critically?”

---

# 22. Digital inequality becomes AI inequality

There are several layers of inequality:

### Infrastructure inequality

Who has devices and connectivity?

### AI-access inequality

Who has access to advanced models?

### AI-literacy inequality

Who knows how to use AI effectively?

### Pedagogical inequality

Who has teachers capable of integrating AI?

### Data inequality

Who has enough data to train effective personalized systems?

### Institutional inequality

Which schools can afford sophisticated AI infrastructure?

Therefore:

> **AI may reduce educational inequality in some contexts while increasing it in others.**

UNESCO's technology research emphasizes access, governance and teacher preparation as system-wide conditions for realizing educational technology's potential. ([UNESCO IITE][22])

---

# 23. Key academic papers and reviews to start with

For a serious literature review, I would begin with the following groups.

### Foundational ITS research

**Ma et al. (2014)**
*Intelligent tutoring systems and learning outcomes: A meta-analysis.*

107 effect sizes, 14,321 participants. ([DOI][2])

**Kulik & Fletcher (2016)**
*Effectiveness of Intelligent Tutoring Systems: A Meta-Analytic Review.*

50 controlled evaluations. ([Sage Journals][3])

---

### Recent AIED reviews

**Mustafa et al. (2024)**
*A systematic review of literature reviews on artificial intelligence in education (AIED): a roadmap to a future research agenda.*

Particularly useful for mapping the overall research field because it synthesizes **143 reviews**. ([Springer Nature][1])

**Wang et al. (2024)**
*Artificial intelligence in education: A systematic literature review.*

Useful for categorizing AI applications, research topics, theories, methods and educational contexts. ([ScienceDirect][23])

**Fu, Weng & Wang (2025)**
*Examining AI Use in Educational Contexts: A Scoping Meta-Review and Bibliometric Analysis.*

Useful for understanding research trends across educational contexts. ([Springer Nature][24])

---

### Human-centred AI

**Human-centred learning analytics and AI in education: A systematic literature review** (2024).

Particularly useful for research on:

* human agency
* trust
* safety
* privacy
* stakeholder participation. ([ScienceDirect][5])

---

### Generative AI

**Albadarin et al. (2024)**
*A systematic literature review of empirical research on ChatGPT in education.*

Useful for understanding the first wave of empirical ChatGPT research. ([Springer Nature][25])

**Deng et al. (2025)**
*Does ChatGPT enhance student learning? A systematic review and meta-analysis of experimental studies.*

Important because it focuses specifically on experimental evidence rather than perceptions alone. ([DOI][7])

**Qian (2025)**
*Pedagogical Applications of Generative AI in Higher Education: A Systematic Review of the Field.*

Useful for higher-education pedagogical applications. ([Springer Nature][6])

---

# 24. Major research reports and policy materials

These should be treated as **core research materials**, even though they are not journal articles.

### UNESCO

* *Global Education Monitoring Report 2023: Technology in Education*
* *Guidance for Generative AI in Education and Research*
* *AI Competency Framework for Teachers*
* *AI Competency Framework for Students*

([GEM Report 2023][20])

### OECD

* *Digital Education Outlook 2021*
* *Digital Education Outlook 2023*
* *Digital Education Outlook 2026*
* *Country Digital Education Ecosystems and Governance*

The **2026 Outlook** is particularly important for a current literature review because it synthesizes emerging evidence concerning educational GenAI. ([OECD][4])

### United States

* U.S. Department of Education, *Artificial Intelligence and the Future of Teaching and Learning* (2023). ([ERIC][16])

### China

* *China Smart Education White Paper* (2025)
* National Smart Education Public Service Platform materials
* National Education Digitalization Strategy materials
* Education Digitalization Strategy Action 2.0 materials. ([China Ministry of Education][15])

---

# 25. Research-material database strategy

For an academic project, I recommend searching across several databases rather than relying on Google Scholar alone.

### International

* Web of Science
* Scopus
* ERIC
* IEEE Xplore
* ACM Digital Library
* ScienceDirect
* SpringerLink
* PubMed
* Google Scholar

### China

* CNKI / 中国知网
* Wanfang Data / 万方
* VIP / 维普
* Chinese Ministry of Education
* National Smart Education Platform

Useful Chinese search terms include:

```text
智慧教育
教育智能化
人工智能+教育
人工智能赋能教育
智能教育
教育数字化
教育数字化转型
生成式人工智能 教育
大模型 教育
教育智能体
智能教学
个性化学习
自适应学习
智能导师系统
学习分析
教育数据挖掘
智能评价
```

---

# 26. Recommended literature-review structure

If your objective is an **academic paper, master's thesis, PhD dissertation, or international comparative study**, I would structure the literature review like this:

### Chapter 1 — Conceptual foundations

**Digitalization → Digital transformation → Intelligentization**

### Chapter 2 — Technologies

* AI
* ML
* NLP
* LLM
* GenAI
* knowledge graphs
* learning analytics
* adaptive learning
* intelligent tutoring
* AI agents

### Chapter 3 — Pedagogy

* personalized learning
* adaptive learning
* intelligent tutoring
* collaborative learning
* inquiry learning
* AI-assisted learning
* teacher-AI collaboration

### Chapter 4 — Assessment

* automated assessment
* adaptive testing
* formative assessment
* competency assessment
* AI-generated assessment

### Chapter 5 — Teacher transformation

* AI literacy
* teacher competencies
* teacher workload
* teacher-AI collaboration
* professional development

### Chapter 6 — Institutional transformation

* AI administration
* student services
* educational governance
* resource allocation
* predictive analytics.

### Chapter 7 — Outcomes

Measure:

* learning achievement
* learning efficiency
* engagement
* motivation
* self-regulation
* critical thinking
* creativity
* retention
* equity.

### Chapter 8 — Risks

* privacy
* bias
* hallucination
* academic integrity
* cognitive offloading
* digital divide
* algorithmic dependence
* teacher autonomy.

### Chapter 9 — Implementation

Compare:

**China / Japan / United States / EU / UK / Singapore **

### Chapter 10 — Research gaps

Then develop your own **Education Intelligentization Index**.

---

# 27. A useful conceptual model for measuring intelligentization

For quantitative research, I would not measure intelligentization simply by asking:

> “How much AI does a school use?”

A better model is:

$$
EI = f(I,D,A,P,T,G,O)
$$

where:

* **I = Infrastructure**
* **D = Educational Data**
* **A = AI Capability**
* **P = Pedagogical Integration**
* **T = Teacher Competency**
* **G = Governance**
* **O = Educational Outcomes**

A practical 0–100 index could contain approximately:

| Dimension                     | Suggested weight |
| ----------------------------- | ---------------: |
| Intelligent infrastructure    |              15% |
| Educational data capability   |              15% |
| AI technology adoption        |              15% |
| Intelligent pedagogy          |              20% |
| Teacher AI competency         |              15% |
| Governance / ethics / privacy |              10% |
| Measured educational outcomes |              10% |
| **Total**                     |         **100%** |

The important methodological principle is that **technology adoption should not dominate the index**.

A school possessing 1,000 AI-enabled devices is not necessarily more intelligentized educationally than a school using a smaller number of AI systems that substantially improve personalized instruction.

---

# 28. The most important research gap

The field is currently moving through a transition:

```text
2020
Digital Education
       ↓
2022
AI-assisted Education
       ↓
2023
Generative AI Education
       ↓
2024–2026
AI + Learning Analytics + Agents
       ↓
Emerging
Intelligent Educational Ecosystems
```

The major unresolved question is therefore no longer merely:

> **“Can AI be used in education?”**

There is already abundant evidence that it can.

The more important research question is:

> **“Under what technological, pedagogical, organizational, institutional, and governance conditions does educational intelligentization produce durable improvements in learning while preserving teacher agency, student autonomy, equity, privacy, and educational quality?”**

That question connects the **AI/EdTech literature** with the **digital-transformation, learning-sciences, educational-management, and policy literature**.

The latest OECD evidence is especially useful here: its 2026 synthesis concludes that GenAI is most educationally promising when it is used with **clear pedagogical intent**, while simply outsourcing cognitive work to general-purpose AI can increase task performance without producing corresponding learning. ([OECD][4])

---

## 29. A concise research map

```text
                 INTELLIGENTIZATION OF EDUCATION
                              │
          ┌───────────────────┼───────────────────┐
          │                   │                   │
     TECHNOLOGY            PEDAGOGY           GOVERNANCE
          │                   │                   │
     AI / LLM              Adaptive           Privacy
     GenAI                 learning           Ethics
     ML                    ITS                Equity
     NLP                   AI tutoring        Regulation
     Agents                AI assessment      Human agency
     Knowledge graphs      AI collaboration   Accountability
          │                   │                   │
          └───────────────────┼───────────────────┘
                              │
                         EDUCATIONAL DATA
                              │
                    ┌─────────┴─────────┐
                    │                   │
               Learning analytics   Educational
                    │                 data mining
                    │                   │
                    └─────────┬─────────┘
                              │
                         OUTCOMES
                              │
       ┌────────────┬─────────┼──────────┬────────────┐
       │            │         │          │            │
   Achievement  Retention  Motivation  Equity    Teacher
                                                   capacity
```

### Bottom line

The literature now supports viewing intelligentization as **a systemic transformation of education**, rather than simply the introduction of AI tools. The strongest established evidence comes from intelligent tutoring, adaptive learning, and learning analytics; generative AI has generated a rapidly expanding experimental literature, but its long-term educational effects remain less settled. Real-world implementation is already substantial at the platform, classroom, teacher-support, student-service, and institutional levels, with China providing an especially large-scale national implementation case. ([Springer Nature][1])

For a research project, the next useful step is to turn this landscape into a **systematic literature review matrix**—for example, **50–100 key papers from 2015–2026**, classified by country, education level, technology, research method, sample size, dependent variables, findings, limitations, and DOI—followed by a **0–100 Education Intelligentization Index** suitable for comparing **China, Japan, the US, EU, and Singapore**.

[1]: https://link.springer.com/article/10.1186/s40561-024-00350-5?utm_source=chatgpt.com "A systematic review of literature reviews on artificial intelligence in education (AIED): a roadmap to a future research agenda | Smart Learning Environments | Springer Nature Link"
[2]: https://doi.org/10.1037/a0037123?utm_source=chatgpt.com "Intelligent tutoring systems and learning outcomes: A meta-analysis."
[3]: https://journals.sagepub.com/doi/pdf/10.3102/0034654315581420?utm_source=chatgpt.com "Effectiveness of Intelligent Tutoring Systems - James A. Kulik, J. D. Fletcher, 2016"
[4]: https://www.oecd.org/en/publications/2026/01/oecd-digital-education-outlook-2026_940e0dd8.html?utm_source=chatgpt.com "OECD Digital Education Outlook 2026 | OECD"
[5]: https://www.sciencedirect.com/science/article/pii/S2666920X2400016X?utm_source=chatgpt.com "Human-centred learning analytics and AI in education: A systematic literature review - ScienceDirect"
[6]: https://link.springer.com/article/10.1007/s11528-025-01100-1?utm_source=chatgpt.com "Pedagogical Applications of Generative AI in Higher Education: A Systematic Review of the Field | TechTrends | Springer Nature Link"
[7]: https://doi.org/10.1016/j.compedu.2024.105224?utm_source=chatgpt.com "Does ChatGPT enhance student learning? A systematic review and meta-analysis of experimental studies - ScienceDirect"
[8]: https://doi.org/10.1016/j.ssaho.2025.102287?utm_source=chatgpt.com "ChatGPT as a cognitive crutch: Evidence from a randomized controlled trial on knowledge retention - ScienceDirect"
[9]: https://doi.org/10.1038/s41598-025-97652-6?utm_source=chatgpt.com "AI tutoring outperforms in-class active learning: an RCT introducing a novel research-based design in an authentic educational setting | Scientific Reports"
[10]: https://www.unesco.org/en/articles/ai-competency-framework-teachers?hub=253682&utm_source=chatgpt.com "AI competency framework for teachers | UNESCO"
[11]: https://www.unesco.org/en/articles/ai-competency-framework-students?hub=66682&utm_source=chatgpt.com "AI competency framework for students | UNESCO"
[12]: https://link.springer.com/article/10.1007/s40692-023-00304-9?utm_source=chatgpt.com "Artificial intelligence (AI) learning tools in K-12 education: A scoping review | Journal of Computers in Education | Springer Nature Link"
[13]: https://www.sciencedirect.com/science/article/pii/S2666920X24000183?utm_source=chatgpt.com "A systematic review of learning task design for K-12 AI education: Trends, challenges, and opportunities - ScienceDirect"
[14]: https://www.moe.gov.cn/fbh/live/2025/77791/mtbd/202512/t20251231_1425330.html?utm_source=chatgpt.com "[新华网]国家智慧教育公共服务平台用户总量突破1.78亿 - 中华人民共和国教育部政府门户网站"
[15]: https://www.moe.gov.cn/jyb_xwfb/xw_zt/moe_357/2025/2025_zt06/cgfb/202505/t20250507_1189603.html?utm_source=chatgpt.com "《中国智慧教育白皮书》和启动国家教育数字化战略行动2.0 - 中华人民共和国教育部政府门户网站"
[16]: https://eric.ed.gov/?id=ED631097&utm_source=chatgpt.com "ERIC - ED631097 - Artificial Intelligence and the Future of Teaching and Learning: Insights and Recommendations, Office of Educational Technology, US Department of Education, 2023-May"
[17]: https://education.ec.europa.eu/document/digital-education-action-plan-4-years-of-progress?utm_source=chatgpt.com "Digital Education Action Plan - Publications Office of the EU"
[18]: https://www.gov.uk/government/collections/using-ai-in-education-settings-support-materials?utm_source=chatgpt.com "Using AI in education settings: support materials - GOV.UK"
[19]: https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research?hub=83294&utm_source=chatgpt.com "Guidance for generative AI in education and research | UNESCO"
[20]: https://gem-report-2023.unesco.org/?utm_source=chatgpt.com "Home - 2023 GEM Report"
[21]: https://unesdoc.unesco.org/in/documentViewer.xhtml?ark=%2Fark%3A%2F48223%2Fpf0000391104%2FPDF%2F391104eng.pdf&file=%2Fin%2Frest%2FannotationSVC%2FDownloadWatermarkedAttachment%2Fattach_import_17145f52-ae3b-405f-8434-1ed2a2a0a881%3F_%3D391104eng.pdf&id=p%3A%3Ausmarcdef_0000391104&locale=en&multi=true&v=2.1.196&utm_source=chatgpt.com "1005_24_AI competency framework for teachers-V2.indd - 391104eng.pdf"
[22]: https://iite.unesco.org/news/global-education-monitoring-report-2023-technology-in-education-a-tool-on-whose-terms/?utm_source=chatgpt.com "Global Education Monitoring Report 2023: Technology in Education – UNESCO IITE"
[23]: https://www.sciencedirect.com/science/article/pii/S0957417424010339?utm_source=chatgpt.com "Artificial intelligence in education: A systematic literature review - ScienceDirect"
[24]: https://link.springer.com/article/10.1007/s40593-024-00442-w?utm_source=chatgpt.com "Examining AI Use in Educational Contexts: A Scoping Meta-Review and Bibliometric Analysis | International Journal of Artificial Intelligence in Education | Springer Nature Link"
[25]: https://link.springer.com/article/10.1007/s44217-024-00138-2?utm_source=chatgpt.com "A systematic literature review of empirical research on ChatGPT in education | Discover Education | Springer Nature Link"
