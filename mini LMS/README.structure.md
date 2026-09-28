Below is a research-oriented overview of the **digital education field as of September 2026**, covering peer-reviewed studies, major international reports, experimental evidence, and real-world implementation. I distinguish between **access/usage**, **learning outcomes**, and **implementation effectiveness**, because those are often conflated.

## 1. Executive synthesis

The strongest recent conclusion is not that “technology improves education” in general. It is that **well-designed digital interventions can improve learning when technology is tightly coupled to pedagogy, feedback, practice, teacher support, and an explicit learning objective**.

Several patterns are now quite consistent:

| Area                           | Current evidence                                              | Main conclusion                                                                                        |
| ------------------------------ | ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| Online/blended learning        | Relatively mature                                             | Can perform as well as or better than conventional instruction when pedagogy is well designed          |
| Adaptive/personalized learning | Moderately strong                                             | Often improves achievement, but implementation and context matter greatly                              |
| Generative AI                  | Rapidly growing, increasingly experimental                    | Promising, but general-purpose AI can improve task performance without producing durable learning      |
| AI tutoring                    | Emerging strong evidence                                      | Potentially powerful when designed around learning science and constrained to tutor rather than answer |
| AI feedback                    | Growing evidence                                              | Useful, especially for writing and formative feedback, but transfer and critical use remain problems   |
| Learning analytics             | Strong research base for prediction; weaker for causal impact | Prediction is mature; turning predictions into effective interventions is harder                       |
| Mobile learning                | Large research base                                           | Positive average effects, but very heterogeneous                                                       |
| VR/immersive learning          | Promising                                                     | Particularly useful for experiential, spatial, procedural learning                                     |
| Gamification                   | Positive but inconsistent                                     | Can increase motivation and achievement, but superficial reward mechanics are not sufficient           |
| OER/open content               | Relatively robust                                             | Associated with modest achievement/completion improvements and lower material costs                    |
| Digital equity                 | Major unresolved issue                                        | Device/connectivity access alone does not produce equitable learning                                   |
| Teacher role                   | Critical                                                      | Digital education works substantially better when teachers remain active instructional agents          |
| Privacy/data governance        | Major concern                                                 | Education is becoming increasingly data-intensive faster than governance mechanisms are maturing       |

UNESCO's global assessment remains an important counterweight to technological enthusiasm: evidence for the educational “added value” of technology has historically been weaker than the scale of adoption, and technology should support rather than displace human interaction. ([GEM Report 2023][1])

The **2026 OECD Digital Education Outlook** now makes the same distinction specifically for generative AI: AI can improve performance on tasks, but **performing a task better is not necessarily equivalent to learning**. Educationally designed or pedagogically guided AI has substantially more promising evidence than simply giving students unrestricted access to general-purpose chatbots. ([OECD][2])

---

# 2. The field has moved through several generations

Digital education is easier to understand as a progression rather than a single technology.

### Generation 1 — Digitization

Examples:

* electronic textbooks
* PowerPoint and multimedia
* learning management systems
* computer labs
* online repositories

Primary objective: **make existing education digital**.

Evidence generally shows modest benefits, with considerable dependence on instructional design.

### Generation 2 — Online and blended learning

Examples:

* MOOCs
* flipped classrooms
* LMS-based courses
* synchronous video teaching
* asynchronous modules

Primary objective: **change where and when learning takes place**.

This is now one of the most mature areas of digital-education research.

A 2023 meta-analysis focusing on teacher education found that online instruction was at least as effective as classroom delivery, while blended/flipped approaches performed better than classroom-only approaches; the authors emphasized that **pedagogy rather than technology itself explains much of the difference**. ([DOI][3])

### Generation 3 — Adaptive/personalized learning

Examples:

* mastery learning systems
* intelligent tutoring systems
* adaptive mathematics programs
* personalized reading systems
* recommendation engines

Primary objective: **change the content or difficulty to match the learner**.

Recent reviews are generally encouraging. A 2024 scoping review of personalized adaptive learning in higher education found improved academic performance in 59% of included studies and increased engagement in 36%, while also identifying technology and time resources as major implementation constraints. ([ScienceDirect][4])

A global 2024 meta-analysis of personalized/adaptive learning technologies found significant positive effects on reading literacy, while emphasizing the importance of contextual moderators. ([ScienceDirect][5])

### Generation 4 — Learning analytics

Examples:

* dashboards
* early-warning systems
* engagement prediction
* dropout prediction
* automated recommendations
* student-progress monitoring

Primary objective: **use behavioral data to understand and intervene in learning**.

A 2024 systematic review analyzed **400 studies** on learning analytics in distance education, indicating how rapidly this field has matured. Much of the work concerns prediction and intervention support rather than demonstrating large causal learning effects. ([Springer][6])

### Generation 5 — Generative AI and conversational tutoring

Examples:

* ChatGPT, Gemini, Claude
* AI tutors
* AI writing feedback
* AI teaching assistants
* AI curriculum assistants
* multimodal tutors

Primary objective: **provide interactive, individualized cognitive support at scale**.

This is the most rapidly developing research area from 2023 onward.

---

# 3. Generative AI is currently the most important research frontier

The evidence emerging in 2025–2026 is considerably more sophisticated than the first wave of “ChatGPT in education” studies.

## 3.1 Average effects are positive, but highly heterogeneous

A 2025 systematic review and meta-analysis of experimental and quasi-experimental GenAI studies identified **68 studies and 337 effect sizes**. It reported an overall standardized effect of approximately **0.45**, but with very high heterogeneity (**I² = 95%**). Effects differed significantly by education level, subject, intervention duration, and study design. ([ScienceDirect][7])

Another 2025 meta-analysis of 57 studies and 97 estimates reported a substantially larger overall effect (**g = 0.804**), with especially large estimates for language learning, while finding no statistically significant effect on metacognition. ([ScienceDirect][8])

The difference between those estimates is instructive: **the field does not yet have a single stable “effect size of AI in education.”** Results vary depending on what AI does, how students use it, how outcomes are measured, and how rigorous the experimental design is.

That is an important methodological lesson.

---

# 4. The crucial distinction: AI as a tutor vs. AI as an answer machine

This is probably the most important emerging conclusion.

A general-purpose chatbot can help a student:

> produce an essay → solve a problem → write code → summarize a text

But that does not necessarily mean the student has learned the underlying skill.

The OECD's 2026 synthesis explicitly warns that outsourcing cognitive work to GenAI can increase immediate task performance without producing comparable learning gains. In some cases, the advantage disappears when the student is subsequently tested without AI access. ([OECD][2])

By contrast, educational AI systems designed to:

* ask questions,
* provide hints,
* diagnose misconceptions,
* force retrieval,
* encourage explanation,
* adapt difficulty,
* require reasoning,
* provide feedback,

appear much more promising.

This leads to an increasingly important distinction:

**AI assistant ≠ AI tutor.**

The former helps the student complete a task.

The latter is designed to change the student's knowledge or capability.

---

# 5. The strongest recent AI tutoring experiment

One particularly important 2025 study was an RCT at Harvard involving **194 undergraduate physics students**.

Researchers compared a research-designed AI tutor with an active-learning classroom treatment. The AI tutor incorporated established principles from learning science rather than simply exposing students to a general chatbot.

Students using the AI tutor showed higher post-test performance and completed the lessons in less time; engagement and motivation were also higher. ([DOI][9])

This is significant because it tests something closer to:

> **AI + pedagogy**

rather than:

> **AI access**

That distinction is likely to dominate the next several years of research.

---

# 6. Even more important: large-scale real-world AI evidence is now appearing

By 2026, the field had begun moving beyond small university experiments.

### Tennessee — Khanmigo

An August 2026 NBER working paper reports a **two-year cluster-randomized trial across 18 Tennessee middle schools** using Khanmigo in remedial mathematics.

Assignment to the AI-tutor condition increased math achievement by approximately **1.3 national percentile ranks per term**, equivalent to roughly **0.06–0.08 SD over a school year**; estimated effects for a full year of active participation were larger.

However, actual AI use was limited: although 96% of students tried Khanmigo at least once, the median student used it on only about one-third of practice days and in only 17% of exercise sessions involving a mistake. ([National Bureau of Economic Research][10])

This produces a very interesting conclusion:

**An AI tutor can work without students using it heavily enough to transform the entire learning process—but the technology's theoretical capability is not the same as actual utilization.**

### Hamilton County, Tennessee

Another 2026 randomized experiment involving **more than 6,000 middle-school students** compared AI-supported mathematics practice with conventional computer-assisted learning.

The AI condition led to slower progression and fewer attempts, but greater accuracy conditional on an attempt; the strongest mechanism appeared after students made mistakes, where AI support improved subsequent responses and encouraged more time spent on the question. ([National Bureau of Economic Research][11])

This supports a more specific hypothesis:

> **The educational value of AI may lie less in producing answers and more in improving what happens immediately after a learner gets something wrong.**

---

# 7. Implementation can matter more than the software

One of the most striking 2026 studies comes from India.

Researchers conducted a randomized trial across **83 residential government middle schools in Uttar Pradesh**, involving more than 5,500 students using Khan Academy for mathematics.

Simply giving schools access to the platform produced limited usage.

The experimental intervention added dedicated implementation personnel whose responsibility was to:

* maintain connectivity,
* organize student accounts,
* protect scheduled practice time,
* supervise usage,
* coordinate the software with teachers,
* monitor progress.

Weekly usage increased from **7.2 to 47.4 minutes**, and mathematics achievement increased by approximately **0.44–0.47 standard deviations after 31 weeks**. ([National Bureau of Economic Research][12])

This is one of the most important findings for anyone planning a digital-education system.

The result was not simply:

> better software → better learning

It was:

> **software + organizational infrastructure + protected instructional time + human supervision → substantially greater usage → learning gains**

This is an important correction to technology-centric EdTech strategies.

---

# 8. The opposite result is equally important

Digital education also produces failures.

A 2025 University of Iowa pilot of Khanmigo Teacher Tools involved seven faculty members.

Faculty appreciated the concept, but actual use was **less than once per week**, and participants did not report significant effects on teaching. One practical problem was poor integration with the university LMS, requiring manual copying and pasting. The institution subsequently recommended against broader adoption in that form. ([Teaching and Learning Office][13])

This illustrates another central principle:

**A technically capable tool can fail because of workflow design.**

In institutional digital education, integration with:

* curriculum,
* timetable,
* assessment,
* LMS,
* identity systems,
* teacher workflow,
* professional development

can be more important than raw AI capability.

---

# 9. Adaptive and personalized learning

Adaptive learning is one of the stronger pre-GenAI research areas.

The fundamental model is:

**diagnose → prescribe → practice → measure → adapt**

rather than giving every student the same content at the same time.

The 2024 higher-education scoping review mentioned above found academic-performance improvement in 59% of studies and engagement improvements in 36%. ([ScienceDirect][4])

Research on adaptive/personalized reading also reports statistically significant positive effects, although moderators explain a considerable amount of variation. ([ScienceDirect][5])

The major unresolved issue is therefore not whether adaptive systems *can* personalize.

It is:

**Which adaptation strategies create durable learning rather than merely improving short-term performance?**

---

# 10. Mobile learning

Mobile learning now has an unusually large evidence base.

A 2025 meta-analysis synthesized **253 empirical studies**, involving more than **21,000 participants across 45 countries**, and reported a large aggregate effect on learning gains (**g ≈ 0.90**). However, the study also reported substantial heterogeneity. ([ScienceDirect][14])

This result should be interpreted carefully. A large pooled effect across many heterogeneous educational experiments does not mean that simply giving students smartphones will generate a large learning improvement.

The effectiveness appears to depend on what the mobile device is doing:

* retrieval practice,
* spaced learning,
* simulations,
* collaboration,
* field data collection,
* multimedia explanations,
* formative assessment

tend to have clearer pedagogical rationales than unstructured device use.

---

# 11. Digital game-based learning and gamification

Research increasingly separates two ideas.

**Digital game-based learning** uses games as learning environments.

**Gamification** adds game mechanics—points, badges, levels, leaderboards—to otherwise conventional educational activity.

A 2024 meta-analysis of 22 experimental studies found a positive effect of gamification on academic performance (**Hedges' g ≈ 0.78**), but the included studies were heterogeneous. ([British Educational Research Association][15])

A different 2024 meta-analysis of 35 interventions found a much smaller overall effect on intrinsic motivation (**g ≈ 0.257**), with stronger effects on perceived autonomy and relatedness than on perceived competence. ([Springer][16])

The conflicting magnitudes reinforce a broader lesson:

**“Gamification works” is too simplistic.**

Good game mechanics can increase motivation and practice. Bad game mechanics can simply turn education into a reward-collection system.

---

# 12. Virtual and augmented reality

VR is strongest where the learning objective itself is experiential.

Examples include:

* anatomy,
* laboratory procedures,
* engineering,
* medical simulation,
* spatial reasoning,
* dangerous or expensive environments,
* historical reconstruction,
* vocational training.

A 2024 systematic review of immersive VR identified 30 relevant studies and reported positive learning effects relative to other media, especially where learning required active manipulation and constructive engagement. ([DOI][17])

But the research also shows a significant limitation: a 2024 review comparing VR with traditional higher education found that very few studies involved students with disabilities or specific learning difficulties. ([DOI][18])

So VR's challenge is shifting from:

> “Does immersion work?”

toward:

> “For which learning objectives, which learners, and under what accessibility conditions?”

---

# 13. Automated and AI-generated feedback

Feedback is one of the areas where AI is particularly well matched to educational practice.

A 2024 meta-analysis of writing feedback found that:

* surface-level feedback improves surface-level outcomes;
* deep feedback improves deeper writing outcomes;
* combined feedback can improve both;
* peer feedback can also produce meaningful effects. ([DOI][19])

A 2026 three-level meta-analysis of AI-assisted feedback in second-language writing synthesized research involving **11,875 students** and found a modest positive overall effect (**d ≈ 0.271**), with a substantially larger effect on emotional engagement than on cognitive outcomes. ([ScienceDirect][20])

Another 2026 meta-analysis of algorithm-based writing feedback found general improvement around **g = 0.36**, with more persistent effects for deeper writing outcomes than surface-level outcomes. ([ScienceDirect][21])

The emerging design principle is therefore:

**AI feedback should not merely correct mistakes; it should make the learner think about why the mistake occurred.**

---

# 14. Learning analytics

Learning analytics has become a substantial research field.

Typical data include:

* LMS activity,
* login behavior,
* assessment results,
* time on task,
* discussion participation,
* assignment submission,
* interaction sequences.

The most mature application is **prediction**.

For example:

> “This student appears to be at high risk of dropping out.”

The harder question is:

> “What intervention should we now make, and will that intervention improve the student's outcome?”

AI-powered learning-analytics dashboards are increasingly being studied for prediction, self-regulated learning, and teacher-facing decision support. A 2025 systematic review identified 21 relevant studies and found these three functions dominant. ([Springer][22])

The field therefore has a growing distinction between:

**predictive validity**

and

**intervention effectiveness**.

The latter remains substantially less established.

---

# 15. Privacy and educational data

Learning analytics creates an unusually sensitive data environment because educational systems can collect:

* academic records,
* behavioral histories,
* attention indicators,
* social interactions,
* learning difficulties,
* biometric data,
* psychological or wellbeing indicators.

A systematic review of 47 papers identified eight interconnected categories of privacy and data-protection concerns across the learning-analytics lifecycle and found surprisingly little applied evidence demonstrating that proposed privacy solutions actually work. ([DOI][23])

The implication is important:

**privacy cannot be added after an analytics system is built.**

It needs to be designed into:

> collection → storage → analysis → prediction → intervention → reporting → deletion.

---

# 16. Open educational resources

Not all meaningful digital education requires sophisticated AI.

Open Educational Resources remain one of the most practical interventions.

A 2024 meta-analysis covering 26 studies found that OER-based courses were associated with:

* higher course completion,
* higher probability of earning at least a C or D,
* higher course grades.

The aggregate effect on course grade was around **d = 0.17**, with the authors identifying OER as potentially scalable and cost-effective while reducing the cost barrier for students. ([ScienceDirect][24])

This is particularly relevant in higher education because digital education is also an **access and affordability strategy**, not simply a technology strategy.

---

# 17. Digital education and distraction

A major problem is that the same device that delivers instruction can deliver distraction.

OECD analysis based on PISA data reports that roughly three-quarters of students in OECD countries spend more than an hour per weekday browsing social networks, while nearly one-third report classroom distraction from digital devices. ([OECD][25])

OECD's broader 2024 analysis stresses that the relationship between device use and learning is not simply linear: purposeful use for learning differs from recreational or distracting use. ([OECD][26])

This explains why:

> “more technology”

is not an educational objective.

The objective is:

> **more productive cognitive activity.**

---

# 18. Real-world implementation around the world

## Japan — GIGA School

Japan is now an important real-world case because it has moved beyond initial device deployment.

MEXT's GIGA School initiative established a 1:1 student-device environment and high-capacity school connectivity. The current policy phase is explicitly moving toward integrating ICT into individualized learning, collaborative learning, teacher work, special educational support, advanced technologies, and educational-data utilization. ([MEXT][27])

MEXT's latest national ICT survey is based on conditions as of **March 1, 2026**, covering public primary and secondary schools and teacher ICT instructional capability. ([MEXT][28])

Japan has therefore entered a second-stage problem:

> **The challenge is no longer primarily “give every child a device.”**

It is:

> **How should schools use the infrastructure to improve pedagogy, assessment, personalization and teacher work?**

This is broadly representative of where advanced digital-education systems are heading.

---

## India — DIKSHA

India's DIKSHA platform demonstrates what happens when digital education becomes national infrastructure.

A 2025 study of rural Rajasthan surveyed 100 teachers and 100 students. It reported that 96% of teachers had learned to use DIKSHA and 95% of students used it for digital textbooks and worksheets, while connectivity and interruptions remained significant problems. ([Indian Journal of Educational Technology][29])

The study is useful for implementation evidence, but it should **not** be interpreted as proof of causal learning improvement because of its design.

India provides a stronger causal example through the 2026 Khan Academy RCT described above.

Together, they demonstrate two different dimensions:

**platform reach ≠ learning effectiveness**

and

**organizational implementation is a major determinant of impact.**

---

## Uruguay — Plan Ceibal

Uruguay's Plan Ceibal is another foundational case. Beginning in 2007, it became one of the world's earliest nationwide one-laptop-per-child programs, combined with school connectivity. Subsequent research has followed students into early adulthood to examine longer-term educational outcomes. ([ScienceDirect][30])

Its importance is historical: it demonstrated that national digital education infrastructure could be treated as **public educational infrastructure**, rather than as individual school technology projects.

---

## Low-connectivity environments

Digital education increasingly includes **offline-first systems**, not just cloud platforms.

The World Bank reports that more than 94% of its education projects had an EdTech component by 2025, typically involving digital infrastructure, learning/management platforms, or digital skills. ([World Bank][31])

Recent programs in countries such as Ethiopia have also experimented with **offline-enabled LMS infrastructure** for refugee and host communities where continuous Internet access cannot be assumed. ([World Bank Blogs][32])

This is an important design trend:

> the future of digital education is not necessarily “always online.”

---

# 19. What seems to work consistently

Across the evidence, several design principles recur.

### 1. Start from the learning objective

The most successful sequence is:

**learning objective → pedagogy → technology**

not:

**technology → find something educational to do with it.**

This is consistent with UNESCO, OECD, and empirical EdTech research. ([GEM Report 2023][33])

### 2. Preserve productive cognitive effort

Technology should not systematically remove:

* retrieval,
* explanation,
* problem solving,
* reflection,
* writing,
* reasoning.

This is especially important with GenAI. ([OECD][2])

### 3. Give teachers an active role

Teachers increasingly become:

> instructor + designer + evaluator + AI supervisor + learner-support professional

rather than disappearing from the process.

UNESCO's 2024 Teacher AI Competency Framework identifies competencies covering human-centered practice, ethics, AI foundations, AI pedagogy and professional learning. ([UNESCO][34])

### 4. Make feedback immediate and actionable

Digital systems are particularly good at:

* formative assessment,
* hints,
* error diagnosis,
* repeated practice,
* spaced practice.

### 5. Build implementation capacity

The India experiment provides unusually strong evidence that **implementation staff and organizational routines can determine whether the same platform succeeds or fails**. ([National Bureau of Economic Research][12])

### 6. Measure learning, not engagement alone

Metrics such as:

* logins,
* screen time,
* completion rate,
* number of messages,
* time on platform

are not equivalent to learning.

The ultimate measurement needs to include independent assessment and, ideally, delayed transfer.

---

# 20. What does not have strong evidence yet

Several claims remain substantially ahead of the evidence.

### “AI will replace teachers”

There is no robust evidence supporting this as a general educational conclusion.

Current evidence is much more consistent with:

**AI augments teachers and tutoring capacity.** ([OECD][2])

### “Every student should have an AI tutor”

The technology is promising, but the evidence shows major questions around utilization, implementation, cost, curriculum alignment, safety and transfer.

### “More screen time means more digital learning”

Clearly unsupported.

Purpose and instructional design matter more than raw screen time. ([OECD][25])

### “AI-generated answers mean students learn faster”

Not necessarily.

The strongest recent research explicitly distinguishes **task performance from learning**. ([OECD][2])

### “Analytics can predict who will fail, therefore analytics improves outcomes”

Prediction alone is not an intervention.

---

# 21. Equity is becoming the central policy issue

The first digital divide was:

> Does the student have a device and Internet?

The second divide is:

> Does the student have the skills, support, environment and quality content required to use that technology effectively?

The third emerging divide is:

> Does the student have access to high-quality AI-enhanced learning while avoiding its risks?

UNESCO emphasizes equity, relevance, scalability and sustainability in evaluating educational technology. ([UNESCO][35])

The World Bank similarly emphasizes that digital education requires not only devices and connectivity but also **teacher capability, student skills, curriculum-aligned resources, assessment, and administrative infrastructure**. ([World Bank][31])

This is why simply comparing “digital school” vs. “traditional school” is increasingly considered a poor research design.

---

# 22. AI literacy is becoming part of education itself

The role of digital education is changing from:

> teach students **with** technology

to:

> teach students **about and through** technology.

UNESCO's 2024 Student AI Competency Framework defines 12 competencies across:

* human-centered mindset,
* ethics of AI,
* AI techniques and applications,
* AI system design,

with progression from understanding to applying to creating. ([UNESCO][36])

Its Teacher AI Competency Framework includes 15 competencies across five domains and three levels of progression. ([UNESCO][34])

This represents an important curricular transition: **AI literacy itself is becoming a learning objective.**

---

# 23. Where academic research is heading next

The research frontier is shifting away from:

> “Does technology improve test scores?”

toward much more specific questions.

### AI

* Which tutoring architectures produce durable learning?
* When should AI give hints versus explanations?
* How can AI increase productive struggle?
* How can AI detect misconceptions without over-intervening?
* What happens when AI is removed?
* Does AI improve transfer to unfamiliar problems?

### Personalized learning

* How accurately should systems adapt?
* Does personalization improve long-term retention?
* Can algorithms avoid reinforcing inequities?

### Teachers

* Which teacher-AI workflows actually save time?
* Does saved teacher time become better instruction?
* How much AI literacy does a teacher actually need?

### Assessment

* How should learning be assessed when students have AI access?
* Should assessment increasingly measure reasoning, oral explanation, process and application rather than only final answers?

### Equity

* Who benefits most?
* Who is excluded?
* Does AI narrow or widen achievement gaps?

### Governance

* Who owns learning data?
* How long should it be retained?
* Can models be audited?
* How should student data be protected?
* How should algorithmic bias be evaluated?

---

# 24. My overall assessment of the evidence

The current evidence can be summarized as follows:

**Strongest evidence**

* structured blended learning
* well-designed formative feedback
* adaptive practice under appropriate conditions
* OER/access interventions
* teacher-supported computer-assisted learning
* educationally designed AI tutoring

**Promising but still developing**

* generative AI tutoring
* AI feedback
* multimodal AI
* AI learning analytics
* immersive VR
* automated instructional assistants

**Highly context-dependent**

* gamification
* mobile learning
* dashboards
* MOOCs
* unrestricted chatbot use
* large-scale device deployments

**Major unresolved risks**

* cognitive offloading
* academic integrity
* student privacy
* algorithmic bias
* teacher workload
* digital distraction
* unequal access to high-quality implementation
* excessive dependence on technology vendors

The broad direction of the field is therefore **not “technology replaces education.”**

It is moving toward a more sophisticated model:

> **Human teacher + digital content + learner data + adaptive systems + AI assistance + carefully designed assessment**

with the teacher and learner remaining central.

---

# 25. Selected recent academic literature

For a research project or literature review, these are particularly useful starting points:

| Year | Paper/report                                                                                                                        | Why it matters                                                                               |
| ---- | ----------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| 2023 | Schmid et al., *A meta-analysis of online learning, blended learning, the flipped classroom and classroom instruction for teachers* | Evidence for online/blended instructional models ([DOI][3])                                  |
| 2023 | Liu & Khalil, *Understanding privacy and data protection issues in learning analytics*                                              | Major privacy/data-governance review ([DOI][23])                                             |
| 2024 | du Plooy et al., *Personalized adaptive learning in higher education*                                                               | Adaptive learning evidence and implementation challenges ([ScienceDirect][4])                |
| 2024 | Palanci et al., *Learning analytics in distance education*                                                                          | 400-study systematic review ([Springer][6])                                                  |
| 2024 | Conrad et al., *Learning effectiveness of immersive virtual reality*                                                                | Systematic VR evidence ([DOI][17])                                                           |
| 2024 | Cho & Permzadian, *The impact of open educational resources on student achievement*                                                 | OER outcomes and scalability ([ScienceDirect][24])                                           |
| 2024 | Zeng et al., *Exploring the impact of gamification on students' academic performance*                                               | Large recent gamification meta-analysis ([British Educational Research Association][15])     |
| 2025 | Han et al., *The impact of GenAI on learning outcomes*                                                                              | 68 experimental/quasi-experimental GenAI studies ([ScienceDirect][7])                        |
| 2025 | Chen & Cheung, *Effect of generative artificial intelligence on university students learning outcomes*                              | 57-study higher-education GenAI meta-analysis ([ScienceDirect][8])                           |
| 2025 | Kestin et al., *AI tutoring outperforms in-class active learning*                                                                   | RCT of AI tutoring in undergraduate physics ([DOI][9])                                       |
| 2025 | Garzón et al., *Mobile learning significantly enhances student learning gains*                                                      | 253-study meta-analysis ([ScienceDirect][14])                                                |
| 2026 | Liu et al., *Effects of AI-assisted feedback on students' perceptions...*                                                           | 11,875-student meta-analysis of AI feedback ([ScienceDirect][20])                            |
| 2026 | Oreopoulos, Keyes-Krysakowski & Agarwal, *How In-School Supervised Ed-Tech Support Produces Massive Learning Gains*                 | Large real-world RCT on implementation capacity ([National Bureau of Economic Research][12]) |
| 2026 | Oreopoulos & Low, *One Click Away: AI Tutoring with Khanmigo in a Two-Year School Experiment*                                       | Large field experiment of AI tutoring ([National Bureau of Economic Research][10])           |

For the policy/implementation side, the two most important recent reference points are the **OECD Digital Education Outlook 2026** and **UNESCO's technology-in-education work**, because they synthesize research alongside national policy and implementation considerations. ([OECD][2])

## Bottom line

The research base is now strong enough to reject two simplistic positions:

**“Digital education doesn't work.”** — false.

**“More technology automatically improves education.”** — also false.

The strongest evidence supports a third model:

**Digital technology is most effective when it is deliberately engineered around how humans learn.**

The major opportunity from 2026 onward is therefore not merely digitizing classrooms. It is building **evidence-based digital learning systems** in which AI, adaptive learning, analytics, digital content and human teaching reinforce one another—and where effectiveness is measured by **durable learning, transfer, equity and student development**, not by device usage or AI adoption alone. ([OECD][2])

[1]: https://gem-report-2023.unesco.org/?utm_source=chatgpt.com "Home - 2023 GEM Report"
[2]: https://www.oecd.org/en/publications/2026/01/oecd-digital-education-outlook-2026_940e0dd8.html?utm_source=chatgpt.com "OECD Digital Education Outlook 2026 | OECD"
[3]: https://doi.org/10.1016/J.CAEO.2023.100142?utm_source=chatgpt.com "A meta-analysis of online learning, blended learning, the flipped classroom and classroom instruction for pre-service and in-service teachers - ScienceDirect"
[4]: https://www.sciencedirect.com/science/article/pii/S2405844024156617?utm_source=chatgpt.com "Personalized adaptive learning in higher education: A scoping review of key characteristics and impact on academic performance and engagement - ScienceDirect"
[5]: https://www.sciencedirect.com/science/article/abs/pii/S1747938X23000805?utm_source=chatgpt.com "Exploring the impact of personalized and adaptive learning technologies on reading literacy: A global meta-analysis - ScienceDirect"
[6]: https://link.springer.com/article/10.1007/s10639-024-12737-5?utm_source=chatgpt.com "Learning analytics in distance education: A systematic review study | Education and Information Technologies | Springer Nature Link"
[7]: https://www.sciencedirect.com/science/article/pii/S1747938X2500051X?utm_source=chatgpt.com "The impact of GenAI on learning outcomes: A systematic review and meta-analysis of experimental studies - ScienceDirect"
[8]: https://www.sciencedirect.com/science/article/pii/S1747938X25000740?utm_source=chatgpt.com "Effect of generative artificial intelligence on university students learning outcomes: A systematic review and meta-analysis - ScienceDirect"
[9]: https://doi.org/10.1038/s41598-025-97652-6?utm_source=chatgpt.com "AI tutoring outperforms in-class active learning: an RCT introducing a novel research-based design in an authentic educational setting | Scientific Reports"
[10]: https://www.nber.org/papers/w35620?utm_source=chatgpt.com "One Click Away: AI Tutoring with Khanmigo in a Two-Year School Experiment | NBER"
[11]: https://www.nber.org/papers/w35621?utm_source=chatgpt.com "Making AI Tutoring Productive: Evidence from a Mastery-Based Math Practice Experiment | NBER"
[12]: https://www.nber.org/papers/w34683?utm_source=chatgpt.com "How In-School Supervised Ed-Tech Support Produces Massive Learning Gains: A Khan Academy Field Experiment in India | NBER"
[13]: https://teach.its.uiowa.edu/news/2025/08/pilot-recap-khanmigo-teacher-tools?utm_source=chatgpt.com "Pilot Recap: Khanmigo Teacher Tools | Office of Teaching, Learning, and Technology - The University of Iowa"
[14]: https://www.sciencedirect.com/science/article/pii/S0360131525001836?utm_source=chatgpt.com "Mobile learning significantly enhances student learning gains: A meta-analysis and research synthesis - ScienceDirect"
[15]: https://bera-journals.onlinelibrary.wiley.com/doi/10.1111/bjet.13471?utm_source=chatgpt.com "Exploring the impact of gamification on students’ academic performance: A comprehensive meta‐analysis of studies from the year 2008 to 2023 - Zeng - 2024 - British Journal of Educational Technology - Wiley Online Library"
[16]: https://link.springer.com/article/10.1007/s11423-023-10337-7?utm_source=chatgpt.com "Gamification enhances student intrinsic motivation, perceptions of autonomy and relatedness, but minimal impact on competency: a meta-analysis and systematic review | Educational technology research and development | Springer Nature Link"
[17]: https://doi.org/10.1016/j.cexr.2024.100053?utm_source=chatgpt.com "Learning effectiveness of immersive virtual reality in education and training: A systematic review of findings - ScienceDirect"
[18]: https://doi.org/10.1016/J.COMPEDU.2024.105214?utm_source=chatgpt.com "Virtual vs. traditional learning in higher education: A systematic review of comparative studies - ScienceDirect"
[19]: https://doi.org/10.1016/j.learninstruc.2024.101961?utm_source=chatgpt.com "How effective is feedback for L1, L2, and FL learners’ writing? A meta-analysis - ScienceDirect"
[20]: https://www.sciencedirect.com/science/article/pii/S0346251X26000497?utm_source=chatgpt.com "The effects of AI-assisted feedback on students’ perceptions, emotions, and learning outcomes in L2 writing: a three-level meta-analysis - ScienceDirect"
[21]: https://www.sciencedirect.com/science/article/pii/S107529352600022X?utm_source=chatgpt.com "Can algorithm-based feedback help students to write better? A meta-analysis exploring surface- and deep-level outcomes - ScienceDirect"
[22]: https://link.springer.com/article/10.1007/s44217-025-00964-y?utm_source=chatgpt.com "AI-powered learning analytics dashboards: a systematic review of applications, techniques, and research gaps | Discover Education | Springer Nature Link"
[23]: https://doi.org/10.1111/bjet.13388 "Understanding privacy and data protection issues in learning analytics using a systematic review - Liu - 2023 - British Journal of Educational Technology - Wiley Online Library"
[24]: https://www.sciencedirect.com/science/article/pii/S0883035524000521?utm_source=chatgpt.com "The impact of open educational resources on student achievement: A meta-analysis - ScienceDirect"
[25]: https://www.oecd.org/en/publications/managing-screen-time_7c225af4-en.html?utm_source=chatgpt.com "Managing screen time | OECD"
[26]: https://www.oecd.org/en/publications/students-digital-devices-and-success_9e4c0624-en.html?utm_source=chatgpt.com "Students, digital devices and success | OECD"
[27]: https://www.mext.go.jp/a_menu/shotou/zyouhou/detail/mext_03203.html?utm_source=chatgpt.com "令和7年度　次世代の学校・教育現場を見据えた先端技術・教育データの利活用推進(最先端技術及び教育データ利活用に関する実証事業）：文部科学省"
[28]: https://www.mext.go.jp/a_menu/shotou/zyouhou/detail/mext_00095.html "令和7年度学校における教育の情報化の実態等に関する調査結果：文部科学省"
[29]: https://journals.ncert.gov.in/IJET/article/view/850?utm_source=chatgpt.com "Access and Use of DIKSHA for School Teachers and Students Amid COVID-19: An Assessment of Rural Rajasthan | Indian Journal of Educational Technology"
[30]: https://www.sciencedirect.com/science/article/pii/S0272775719302729?utm_source=chatgpt.com "Technology and educational choices: Evidence from a one-laptop-per-child program - ScienceDirect"
[31]: https://www.worldbank.org/ext/en/topic/education/digital-technologies-in-education?utm_source=chatgpt.com "Digital Technologies in Education | World Bank Group"
[32]: https://blogs.worldbank.org/en/education/a-pilot-program-in-ethiopia-is-building-skills-for-refugees-and-?utm_source=chatgpt.com "How a pilot program in Ethiopia is building skills and pathways to jobs for refugees and host communities"
[33]: https://gem-report-2023.unesco.org/recommendations/?utm_source=chatgpt.com "Recommendations - 2023 GEM Report"
[34]: https://www.unesco.org/en/articles/ai-competency-framework-teachers?hub=253682&utm_source=chatgpt.com "AI competency framework for teachers | UNESCO"
[35]: https://www.unesco.org/en/articles/global-education-monitoring-report-2023-technology-education-tool-whose-terms?utm_source=chatgpt.com "2023 Global Education Monitoring Report, Technology in education: a"
[36]: https://www.unesco.org/en/articles/ai-competency-framework-students?hub=66682&utm_source=chatgpt.com "AI competency framework for students | UNESCO"
