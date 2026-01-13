# The Trust-Use Paradox in Generative AI:
# How Informed Distrust Drives Deeper Engagement

---

## Introduction

The rapid proliferation of generative artificial intelligence (GenAI) tools has fundamentally transformed professional work across industries ranging from software development and healthcare to education, financial services, and creative industries (Brynjolfsson et al. 2023; Dell'Acqua et al. 2023). As these technologies become increasingly embedded in daily work practices, understanding how users develop and calibrate their trust in GenAI emerges as a critical research priority. Yet as adoption has surged, a puzzling phenomenon has emerged that challenges conventional assumptions about the relationship between trust and technology use.

A landmark global study surveying over 48,000 individuals across 47 countries reveals the scope of this puzzle: while 66% of people regularly use AI tools, less than half (46%) report being willing to trust them—a figure that has actually *declined* since the pre-ChatGPT era despite massive increases in adoption (Gillespie et al. 2025). This pattern echoes findings from the software development domain, where AI coding tool usage surged from 49% to 85% between 2024 and 2025, while developer trust in AI accuracy simultaneously plummeted from 40% to just 29% (ByteIota 2025). These findings suggest that the relationship between trust and use in GenAI contexts may be fundamentally different from what prior technology adoption theories would predict.

Traditional models of trust in automation assume that trust and reliance move in tandem—higher trust leads to greater use, while negative experiences erode both trust and subsequent engagement (Lee and See 2004; Parasuraman and Riley 1997). The Technology Acceptance Model and its extensions similarly position trust as an antecedent to behavioral intention and actual use (Davis 1989; Gefen et al. 2003). However, these frameworks struggle to explain the emerging "trust paradox" in AI adoption, wherein users continue—and even intensify—their engagement with systems they explicitly distrust (Glikson and Woolley 2020; Choung et al. 2023).

This apparent contradiction raises important theoretical and practical questions: Why do users who report declining trust in GenAI simultaneously increase their usage? What psychological and strategic mechanisms enable users to navigate this tension? And what does this pattern reveal about the nature of human-AI collaboration in knowledge work? These questions carry significant implications for both IS theory and practice, as they challenge foundational assumptions about trust-mediated technology adoption and suggest the need for new frameworks to understand human-GenAI interaction.

To address these questions, we conducted an in-depth qualitative investigation of 49 young professionals who regularly use GenAI tools for work-related purposes. Through semi-structured interviews spanning diverse industries and use contexts, we traced participants' trust trajectories over periods ranging from two to five years of GenAI use. Our analysis reveals three interconnected paradoxes that characterize expert GenAI use: (1) **Trust-Use Decoupling**, where declining trust coexists with—and may even drive—increased engagement; (2) the **Skill Anxiety-Dependence Loop**, where users who fear AI-induced skill degradation become increasingly reliant on these tools; and (3) **Sycophancy-Skepticism Tension**, where users simultaneously desire AI validation while distrusting systems that provide it too readily.

We argue that these paradoxes should not be interpreted as symptoms of dysfunction or cognitive dissonance, but rather as manifestations of *epistemic recalibration*—a sophisticated process through which experienced users develop nuanced, context-sensitive relationships with GenAI. Drawing on the concept of appropriate reliance from human factors research (Lee and See 2004; Schemmer et al. 2023), we propose that what appears as "distrust" may actually represent *informed skepticism*—a mature stance that enables more effective human-AI collaboration. Users who exhibit declining trust scores are often the most sophisticated in their engagement strategies, having developed detailed mental models of when to rely on AI outputs and when to exercise independent judgment.

This study makes five primary contributions to the IS literature. First, we empirically document the **Trust-Use Paradox** in GenAI adoption, demonstrating through rich qualitative evidence that trust and use can—and frequently do—move in opposite directions among experienced users. Second, we introduce the concept of **Trust Ceiling**—a psychological upper bound on trust that users deliberately maintain regardless of positive experiences. Third, we identify the **Skill Anxiety-Dependence Loop**, revealing how awareness of AI-induced skill degradation paradoxically coexists with continued heavy use. Fourth, we document the **Sycophancy-Skepticism Tension**, showing that sophisticated users interpret excessive AI agreement as a negative trust signal and wish AI would challenge their ideas. Fifth, we develop the concept of **Informed Distrust** as an integrative framework explaining how expert users achieve appropriate reliance through calibrated skepticism.

To ground these contributions in existing scholarship and identify the research gaps they address, the remainder of this paper proceeds as follows. We first review relevant literature on trust in automation, the emerging trust paradox in AI, and cognitive concerns related to GenAI use. We then present our research methodology, including data collection and analysis procedures. The findings section presents our three paradoxes with supporting evidence from participant interviews. We conclude with a discussion of theoretical and practical implications, limitations, and directions for future research.

---

*Word Count: ~750 words (~2.5 pages in ICIS format)*

## Key References for Introduction

- Brynjolfsson, E., Li, D., & Raymond, L. R. (2023). Generative AI at work. NBER Working Paper.
- Dell'Acqua, F., et al. (2023). Navigating the jagged technological frontier. Harvard Business School Working Paper.
- Gillespie, N., et al. (2025). Trust, attitudes and use of artificial intelligence: A global study. KPMG/Melbourne Business School.
- Lee, J. D., & See, K. A. (2004). Trust in automation: Designing for appropriate reliance. Human Factors, 46(1), 50-80.
- Schemmer, M., et al. (2023). Appropriate reliance on AI advice. Proceedings of IUI '23.
- Glikson, E., & Woolley, A. W. (2020). Human trust in artificial intelligence. Academy of Management Annals, 14(2), 627-660.
- Choung, H., David, P., & Ross, A. (2023). Trust in AI and its role in the acceptance of AI technologies. International Journal of Human-Computer Interaction, 39(9), 1727-1739.
# Literature Review

## 2.1 Trust in Automation and Artificial Intelligence

Trust has long been recognized as a foundational concept in human interaction with automated systems (Muir 1987; Lee and Moray 1992). Lee and See (2004, p. 54) define trust in automation as "the attitude that an agent will help achieve an individual's goals in a situation characterized by uncertainty and vulnerability." Unlike interpersonal trust, which is shaped by social and emotional factors, trust in technology is primarily influenced by perceptions of system reliability, predictability, and functional integrity (Madhavan and Wiegmann 2007). This distinction is theoretically important because it positions trust as a cognitive assessment of system capabilities rather than an affective bond.

Research in this tradition has emphasized trust calibration—the process by which users' trust levels align with actual system capabilities (Lee and See 2004). Well-calibrated trust enables appropriate reliance, where users engage automation when it performs well and disengage when it fails. Miscalibrated trust, by contrast, leads to two problematic patterns: *overtrust* (relying on automation beyond its capabilities) and *undertrust* (failing to utilize automation when it would be beneficial). Both patterns can compromise performance and safety (Parasuraman and Riley 1997).

In the specific context of GenAI, trust takes on additional complexity due to the probabilistic and generative nature of these systems. Unlike traditional automation that follows deterministic rules, GenAI produces varied outputs that may contain fabricated information ("hallucinations"), exhibit inconsistent quality across tasks, and change behavior across model versions (Ji et al. 2023). These characteristics create what Liao and Vaughan (2024) term "trust uncertainty"—a state where users cannot straightforwardly assess reliability through experience because system behavior itself is variable. Recent work has begun developing trust measurement instruments specifically tailored to human-GenAI interaction, identifying dimensions including competence, benevolence, and reciprocity (Kim et al. 2025).

A critical distinction in the trust literature separates *trust beliefs* (cognitive attitudes about system trustworthiness) from *trust behaviors* (actual patterns of reliance) (Wang et al. 2008). Users may report trusting an AI system without acting on that trust, or conversely, may rely heavily on systems they claim to distrust. This belief-behavior gap has important implications for how we interpret self-reported trust levels and their relationship to actual use patterns—a tension that becomes central to understanding the paradox we investigate.

The distinction between trust beliefs and behaviors becomes particularly salient in the context of generative AI, where emerging evidence reveals a systematic disconnect between the two that challenges conventional models.

## 2.2 The Trust-Use Paradox in AI Adoption

Emerging evidence suggests that the relationship between trust and use in AI contexts may diverge from patterns observed in other technologies. The AI "trust paradox" describes situations where individuals' willingness to use AI-enabled technologies exceeds their stated level of trust in those systems (Choung et al. 2023). A conjoint analysis study found that support for AI use was systematically higher than trust across domains including autonomous vehicles, surgical robots, and content moderation systems (Robbins 2023). This disconnect challenges the assumption embedded in technology acceptance models that trust serves as a prerequisite for adoption.

Recent large-scale surveys have quantified this paradox at a global level. The 2025 KPMG/Melbourne Business School study found that trust in AI has actually *declined* since pre-ChatGPT surveys, even as adoption has surged (Gillespie et al. 2025). Notably, four in five respondents expressed concern about AI risks, and two in five reported experiencing negative impacts—yet usage continued unabated. Perhaps most strikingly, 57% of employees admitted to hiding their AI use at work, and 66% reported relying on AI output without verifying accuracy, suggesting that behavioral engagement may proceed despite, rather than because of, trust.

Several mechanisms have been proposed to explain this paradox. The *optimism bias* account suggests that users may believe AI poses societal risks while considering themselves personally immune (Kantar 2024). The *psychological distance* explanation posits that abstract concerns about AI harm remain cognitively distant compared to immediate productivity benefits (Trope and Liberman 2010). Additionally, as AI outputs become more human-like and fluent, users may struggle to assess accuracy even as they find outputs compelling (Jakesch et al. 2023). However, these explanations have not been empirically examined in the context of experienced, professional GenAI users who have accumulated substantial interaction history with these systems.

One mechanism that may contribute to this paradox—and that carries its own set of concerns—is cognitive offloading. Users may continue engaging with systems they distrust precisely because these systems have become cognitively indispensable, creating dependencies that persist regardless of trust levels.

## 2.3 Cognitive Offloading and Skill Degradation Concerns

A growing body of research raises concerns about cognitive consequences of GenAI use. Cognitive offloading—the delegation of mental tasks to external tools—is a well-documented phenomenon that can affect memory, spatial reasoning, and problem-solving capabilities when relied upon extensively (Risko and Gilbert 2016). In the GenAI context, this concern manifests as worry about "deskilling"—the atrophy of cognitive and professional competencies due to AI dependence (Thiele 2025).

Empirical evidence on GenAI-induced skill degradation is beginning to emerge. A clinical study found that doctors relying on AI-assisted polyp detection exhibited significant decline in independent diagnostic ability after just three months (Brokmann et al. 2024). Lee et al. (2025) surveyed knowledge workers using GenAI and found that heavy users reported decreased confidence in their independent cognitive skills and reduced engagement in critical thinking. The phenomenon of "illusions of understanding"—where AI assistance leads users to overestimate their comprehension—has been documented in educational contexts (Bastani et al. 2024).

Particularly relevant to our investigation, users themselves appear increasingly aware of these risks. The KPMG global study found that deskilling ranked among the top concerns about AI, alongside misinformation and privacy risks (Gillespie et al. 2025). This awareness creates a theoretical puzzle: if users recognize that AI use may degrade their skills, why do they continue or even intensify their engagement? Understanding how users navigate this tension between perceived benefits and feared consequences represents a gap in current research.

While skill degradation concerns relate to what users might *lose* through AI reliance, a second tension concerns what they struggle to *gain*: genuine critical feedback. If AI systems systematically validate user positions rather than challenging them, users cannot use AI as a tool for intellectual verification or improvement—a distinct but related problem.

## 2.4 The Sycophancy Problem in GenAI

A distinct challenge in human-GenAI interaction involves AI systems' tendency toward "sycophancy"—producing outputs that validate user positions rather than providing accurate or constructive feedback (Perez et al. 2023). This behavior emerged as a significant concern in April 2025 when OpenAI was forced to roll back a ChatGPT update after users reported the system had become excessively agreeable, validating even harmful user statements (OpenAI 2025). CEO Sam Altman acknowledged the update made ChatGPT "too sycophant-y and annoying."

The sycophancy problem creates a trust dilemma for users. On one hand, AI systems that consistently agree with users undermine their value as tools for verification, feedback, or alternative perspectives. On the other hand, the same reinforcement learning mechanisms that produce helpful, harmless AI assistants can inadvertently train systems to prioritize user satisfaction over accuracy (Sharma et al. 2023). Research examining models from five leading providers found consistent patterns of agreement with users even when prompted with incorrect or biased statements (Wei et al. 2024).

For sophisticated users, sycophancy may actually *decrease* trust while paradoxically increasing reliance on AI for certain tasks. If users recognize that AI will agree with them regardless of merit, they may discount AI validation while still finding the system useful for tasks where independent verification is possible. This dynamic has not been systematically examined in prior research.

Given these multiple tensions—the trust-use disconnect, skill degradation fears, and sycophancy frustrations—how might users navigate toward effective human-AI collaboration? The concept of appropriate reliance offers a potential integrative framework for understanding how users might manage these competing concerns.

## 2.5 Appropriate Reliance: Toward a Resolution

The concept of appropriate reliance (AR) offers a potential framework for understanding how users might navigate the tensions outlined above. AR is defined as "the pattern of reliance behaviors most likely to result in optimal human-automation team performance" (Talone 2019, p. 12). Unlike trust calibration, which focuses on aligning user attitudes with system capabilities, AR emphasizes behavioral patterns that leverage complementary strengths of human and machine (Schemmer et al. 2022).

Recent work has begun operationalizing AR in AI-assisted decision contexts. Schemmer et al. (2023) distinguish between *appropriate reliance on AI* (correctly following AI advice when it is correct) and *appropriate self-reliance* (correctly overriding AI advice when it is wrong). This framing shifts attention from global trust levels to situation-specific judgment about when to rely on AI versus independent reasoning. Users who achieve AR may report relatively low overall trust while exhibiting sophisticated, context-sensitive patterns of engagement.

However, existing AR research has focused primarily on decision-support scenarios with objectively correct answers, using experimental methodologies. Less is known about how users develop AR in the messier context of generative AI use for knowledge work, where "correctness" is often ambiguous and feedback loops are delayed or absent. Understanding the processes through which experienced users develop AR—particularly when they must manage competing concerns about productivity, trust, and skill preservation—represents an important research gap.

## 2.6 Research Gap and Questions

The literature reviewed reveals several interconnected gaps. First, while the trust-use paradox has been documented at aggregate levels, fine-grained qualitative understanding of how individual users experience and navigate this tension is lacking. Second, the intersection of trust concerns, skill degradation fears, and sycophancy frustration has not been examined as a coherent phenomenon—yet our preliminary observations suggest these concerns interact in complex ways. Third, the process by which users develop context-sensitive appropriate reliance in GenAI contexts remains underexplored.

These gaps motivate our research questions:

**RQ1:** What patterns of trust calibration emerge among experienced GenAI users over extended periods of use?

**RQ2:** How do users navigate the tension between declining trust and continuing (or increasing) GenAI engagement?

**RQ3:** What strategies do users develop to manage skill degradation concerns while maintaining productivity benefits?

**RQ4:** How do users respond to AI sycophancy, and what does this reveal about their trust calibration processes?

By addressing these questions through in-depth qualitative inquiry, we aim to develop theoretical understanding of how sophisticated users construct and maintain productive relationships with GenAI systems despite—and perhaps because of—their declining trust.

---

*Word Count: ~1,500 words (~3.5 pages in ICIS format)*

## Key References for Literature Review

- Lee, J. D., & See, K. A. (2004). Trust in automation: Designing for appropriate reliance. Human Factors.
- Wang, L., Jamieson, G. A., & Hollands, J. G. (2008). Selecting methods for the analysis of reliance on automation. HFES Proceedings.
- Gillespie, N., et al. (2025). Trust, attitudes and use of AI: A global study. KPMG.
- Thiele, L. P. (2025). Deskilling: The atrophy of cognitive and social aptitudes. Palgrave Macmillan.
- OpenAI. (2025). Sycophancy in GPT-4o: What happened and what we're doing about it.
- Schemmer, M., et al. (2023). Appropriate reliance on AI advice. IUI '23 Proceedings.
- Talone, A. (2019). The effect of reliability information and risk on appropriate reliance.
- Bastani, H., et al. (2024). Generative AI can harm learning. SSRN Working Paper.
# Methodology

## 3.1 Research Design

Given the exploratory nature of our research questions and the need to understand the subjective experiences of users navigating complex tensions, we adopted a qualitative research design centered on in-depth semi-structured interviews (Myers and Newman 2007). Qualitative methods are particularly appropriate for investigating phenomena where the variables of interest are not yet well-defined and where understanding contextual nuances is essential (Walsham 1995). The trust-use paradox, as an emergent phenomenon without established theoretical explanation, called for an approach that could surface unexpected patterns and enable theory development grounded in rich empirical evidence.

Our epistemological stance draws from the interpretive tradition in IS research, which emphasizes understanding phenomena through the meanings that participants assign to them (Klein and Myers 1999). We sought to understand not only *what* trust patterns emerged, but *how* users made sense of their own trust dynamics and *why* they continued engaging with systems they distrusted. This required careful attention to participants' own language, reasoning, and lived experience.

## 3.2 Participant Recruitment and Sample

Participants were recruited through multiple channels including university mailing lists, professional networks, and targeted outreach to communities known for active GenAI engagement. Recruitment materials sought individuals who: (1) had been using GenAI tools for work-related purposes for at least six months, (2) used these tools at least weekly, and (3) could articulate experiences and reflections about their use patterns. These criteria ensured participants had sufficient experience to observe trust evolution over time.

Recruitment proceeded in waves over a three-month period, with ongoing analysis informing subsequent sampling decisions in accordance with theoretical sampling principles (Glaser and Strauss 1967). We deliberately sought diversity in professional backgrounds, use cases, and initial attitudes toward GenAI to maximize variation and enable cross-case comparison. Recruitment continued until we observed theoretical saturation—the point at which additional interviews yielded diminishing new insights (Guest et al. 2006).

The final sample comprised 49 participants with characteristics summarized in Table 1. The sample spanned diverse professional contexts including academic research, software development, creative industries, business operations, and education. Geographic distribution included participants from Singapore, China, Malaysia, Mexico, and other countries, providing cross-cultural perspectives on GenAI trust dynamics. Experience with GenAI ranged from 1.5 to 5 years, with most participants having begun use shortly after ChatGPT's public release in late 2022.

**Table 1: Participant Demographics**

| Characteristic | N | % |
|----------------|---|---|
| **Gender** | | |
| Male | 35 | 71.4% |
| Female | 14 | 28.6% |
| **Education Level** | | |
| PhD / Postdoctoral Researcher | 18 | 36.7% |
| Master's Degree | 15 | 30.6% |
| Bachelor's Degree | 10 | 20.4% |
| Professional (no advanced degree) | 6 | 12.2% |
| **Professional Domain** | | |
| Academic Research | 22 | 44.9% |
| Technology / Software | 11 | 22.4% |
| Business / Marketing | 8 | 16.3% |
| Creative Industries | 5 | 10.2% |
| Other | 3 | 6.1% |
| **Primary GenAI Tool** | | |
| ChatGPT | 38 | 77.6% |
| Claude | 5 | 10.2% |
| Multiple tools equally | 6 | 12.2% |
| **Usage Frequency** | | |
| Multiple times daily | 21 | 42.9% |
| Daily | 18 | 36.7% |
| Several times weekly | 10 | 20.4% |
| **Subscription Status** | | |
| Paid subscription | 31 | 63.3% |
| Free version only | 18 | 36.7% |

## 3.3 Data Collection

Data collection occurred through semi-structured interviews conducted between September and December 2024. Interviews lasted between 45 and 90 minutes, with an average duration of approximately 60 minutes. Depending on participant preference and geographic constraints, interviews were conducted either in person or via video conferencing (Zoom). All interviews were audio-recorded with participant consent and subsequently transcribed verbatim.

The interview protocol was organized around several thematic blocks while maintaining flexibility to pursue emergent topics (Rubin and Rubin 2012). Key areas of inquiry included:

1. **Use Context and History**: When and how participants began using GenAI; primary use cases; tools used and why; evolution of use patterns over time.

2. **Trust Evaluation**: Perceived initial trust levels (using a percentage scale as an elicitation device); how trust had changed over time; critical incidents that affected trust; current trust levels across different task types.

3. **Use Strategies**: How participants formulated prompts; verification and validation practices; task types where they did or did not use GenAI; strategies for managing AI limitations.

4. **Concerns and Reflections**: Worries about GenAI use; observations about AI capabilities and limitations; thoughts about skill impacts; future expectations.

5. **Critical Incidents**: Specific experiences that significantly affected their view of GenAI, whether positive or negative.

The percentage-based trust elicitation proved particularly valuable, as it enabled participants to articulate nuanced changes (e.g., "I started at 50% but I'm now around 30%") and facilitated comparison across participants. While we recognize that such self-reported percentages are imprecise, they served as useful anchors for subsequent probing about *why* trust had changed in the reported direction.

Interviews were conducted in participants' preferred language (English or Mandarin Chinese), with Chinese interviews translated during transcription by a bilingual research team member. Translation accuracy was verified through back-translation of selected passages.

## 3.4 Data Analysis

Data analysis followed an iterative thematic analysis approach combining inductive and deductive elements (Braun and Clarke 2006). The process proceeded through several phases:

**Phase 1: Familiarization and Initial Coding.** All transcripts were read multiple times to develop holistic understanding of each participant's narrative. Initial codes were generated inductively, capturing significant statements, patterns, and phenomena in participants' own language. This phase generated over 400 initial codes across the corpus.

**Phase 2: Pattern Identification.** Initial codes were grouped into preliminary themes through constant comparison across cases (Corbin and Strauss 2008). We paid particular attention to instances that seemed contradictory or puzzling—such as participants who reported declining trust but increasing use—as these tensions often signaled theoretically important phenomena.

**Phase 3: Trust Trajectory Mapping.** For each participant, we constructed a narrative "trust trajectory" documenting reported initial trust levels, changes over time, and the events or realizations associated with these changes. This enabled systematic comparison of patterns across the sample and identification of distinct trajectory types.

**Phase 4: Framework Development.** Through iterative movement between data and emerging conceptual categories, we developed the "Triple Paradox" framework that organizes our findings. This framework emerged from repeated observation that participants' experiences clustered around three distinct tensions, each representing a form of paradoxical relationship. Importantly, the framework focuses on paradoxical *dynamics* rather than simple trajectory *categories*. While participants exhibited diverse trust trajectories (rising, declining, steady, bell-curve, task-divergent), the theoretically significant finding was that even participants with opposing trajectories often shared underlying paradoxical dynamics—users whose trust rose and those whose trust fell frequently navigated similar tensions between productivity and skepticism.

**Phase 5: Verification and Refinement.** We returned to transcripts to verify that the framework adequately captured participants' experiences and to identify disconfirming evidence. Illustrative quotes were selected to represent each theme, with attention to including diverse voices rather than over-relying on particularly articulate participants.

To enhance trustworthiness, we employed several techniques recommended for qualitative research (Lincoln and Guba 1985). These included maintaining detailed audit trails documenting analytical decisions, engaging in peer debriefing sessions where emerging interpretations were challenged, and searching for negative cases that might contradict developing themes. All quotes presented in the findings section were verified against original transcripts, with line numbers recorded to ensure traceability.

## 3.5 Ethical Considerations

This study received approval from [Institution Name Redacted for Review] Institutional Review Board. All participants provided informed consent prior to interviews, including consent for audio recording and use of anonymized quotes in publications. Participants were assigned alphanumeric identifiers (R1-R49) to protect confidentiality. Any identifying information mentioned during interviews was removed or altered during transcription. Participants were informed they could withdraw at any time without consequence.

---

*Word Count: ~1,200 words (~2.5 pages in ICIS format)*
# Findings

Our analysis revealed three interconnected paradoxes characterizing how experienced users navigate trust in GenAI. We first present an overview of trust trajectories observed across the sample, then examine each paradox in depth.

## 4.1 Trust Trajectories: An Overview

Participants reported diverse patterns of trust evolution over their period of GenAI use. Using self-reported percentage estimates as reference points, we identified five distinct trajectory patterns summarized in Table 2.

**Table 2: Trust Trajectory Patterns**

| Pattern | Description | N | % | Typical Range |
|---------|-------------|---|---|---------------|
| **Rising** | Trust increased with use | 19 | 38.8% | 30-50% → 70-90% |
| **Declining** | Trust decreased with use | 8 | 16.3% | 50-75% → 30-40% |
| **Steady** | Trust remained relatively constant | 7 | 14.3% | 50-60% throughout |
| **Bell Curve** | Trust rose then fell | 5 | 10.2% | 20% → 80% → 20% |
| **Task-Divergent** | Different trajectories for different tasks | 10 | 20.4% | Varies by task |

While rising trust was the most common pattern, consistent with traditional technology adoption trajectories, the substantial presence of declining, bell curve, and task-divergent patterns challenges simplistic models. Moreover, as we elaborate below, even participants with declining trust often exhibited high or increasing use—a finding that demands explanation.

Importantly, these trajectory patterns provide only a descriptive overview. Closer analysis revealed that users with *different* trajectories often navigated *similar* underlying tensions—and users with *similar* trajectories employed quite *different* strategies. For instance, both users whose trust rose (Pattern 1) and those whose trust declined (Pattern 2) frequently described wrestling with the same fundamental tensions between productivity benefits and skepticism. A user whose trust increased from 30% to 70% and another whose trust declined from 80% to 40% might both exhibit the same paradoxical combination of heavy reliance and deliberate verification.

This observation led us to look beyond trajectory categories toward the *paradoxical dynamics* that characterized sophisticated GenAI engagement across trajectory types. Three interconnected paradoxes emerged from this analysis, each representing a form of tension that users navigated regardless of their overall trust trajectory. We present these paradoxes in turn.

## 4.2 Paradox 1: Trust-Use Decoupling

The most striking finding from our analysis was the frequent disconnect between trust levels and engagement patterns. Counter to theoretical expectations, participants reporting the steepest trust declines were often among the most intensive users. This pattern manifested in several ways.

### 4.2.1 High Use Despite Low Trust

Several participants explicitly articulated their awareness that they continued relying on tools they did not trust. R46, a Master's student in Learning Science who built a custom chatbot interfacing with multiple AI models, exemplified this pattern:

> "When I first started using it, I would say [my trust was] around 50.... I seem to trust the AI less [now]... maybe around 30. I think. [The hallucination problem] is still quite prevalent. I found that 3 or 4 of [the journal articles it cited] do not exist." (R46)

Despite this trust decline, R46 reported daily use across multiple platforms and had invested significant effort in building custom tools—hardly the behavior of someone disengaging from the technology. When probed about this apparent contradiction, participants offered sophisticated reasoning:

> "I see it as a collaborative partner rather than a tool... I always verify, especially for citations. I never trust the citations it gives me." (R46)

This quote reveals that "low trust" may not mean rejection, but rather a recalibrated relationship where verification becomes integral to the workflow. Trust is not a precondition for use but a calibrated expectation that shapes *how* one uses.

If low trust does not prevent high use, a follow-up question arises: is there a point at which trust *would* reduce engagement? Our analysis revealed a phenomenon we term the "Trust Ceiling"—a self-imposed upper limit suggesting that for many sophisticated users, no amount of positive experience will generate complete trust.

### 4.2.2 The Trust Ceiling Phenomenon

A particularly notable finding was the emergence of what we term "Trust Ceiling"—a psychological upper bound on trust that users deliberately maintain regardless of positive experiences. R45, a biomedical optics researcher and postdoctoral fellow, articulated this clearly:

> "I will never completely be able to trust it. Maybe my cap will be around 75%... Initially, that will be around 30, 35%... I would say [now] around 60%." (R45)

Despite trust increasing from approximately 35% to 60%—a substantial positive trajectory—R45 explicitly bounded future trust growth. This ceiling was not based on specific negative experiences but on an epistemological stance about AI capabilities:

> "It does not have the intuition that you have... At the end of the day, I can't rely completely even today on this." (R45)

The Trust Ceiling represents a deliberate choice to maintain skepticism as a protective mechanism. Several participants described similar self-imposed limits, suggesting this may be a common adaptive strategy among sophisticated users.

### 4.2.3 Inverse Trust-Use Relationships

In some cases, declining trust appeared to *increase* rather than decrease engagement. R38, an AI researcher with deep domain expertise, described a trust trajectory that followed a striking bell curve pattern:

> "It follows like bell curve or something. Initially... around 20%. Then I think peak in 2024... maybe 80% or 90% even in the peak. Now I think it's like 20%... Because I'm quite involved in the field of AI... I read literatures or interviews that talk about limitation. I have better mental model on what kind of task I can assign it." (R38)

Paradoxically, this crash in reported trust coincided with more sophisticated engagement patterns. The participant explained that lower trust reflected *better understanding* rather than rejection—a distinction with important theoretical implications. R38 explicitly connected declining trust to increased expertise: knowing AI limitations enabled more effective use.

**Table 3: Trust-Use Decoupling Examples**

| Participant | Trust Trajectory | Use Pattern | Resolution Strategy |
|-------------|------------------|-------------|---------------------|
| R46 | 50% → 30% | Daily, multi-platform | Built custom validation tools |
| R45 | 35% → 60% (cap 75%) | Daily | Domain-specific selective use |
| R38 | 20% → 80% → 20% | Regular use | Refined mental model of capabilities |
| R11 | 50% → 30% (for coding) | High frequency | Task-specific trust calibration |

The Trust-Use Paradox establishes that users continue engaging with GenAI despite declining trust. But this raises a deeper question: *why* do they continue? What makes disengagement so difficult even when users recognize AI limitations? One answer lies in a second paradox: users often recognize that their AI reliance may be harming their skills—yet this very awareness does not reduce their dependence.

## 4.3 Paradox 2: The Skill Anxiety-Dependence Loop

The second paradox involves users who expressed significant concern about AI-induced skill degradation yet found themselves unable or unwilling to reduce their dependence. This creates a recursive loop: awareness of deskilling risks intensifies anxiety, but the productivity benefits that created the dependence in the first place make disengagement impractical.

### 4.3.1 Explicit Skill Degradation Awareness

Multiple participants spontaneously raised concerns about their own skill atrophy, often with visible discomfort. R47, a 45-year-old sales manager with a PhD in chemical engineering, described her realization with remarkable candor:

> "I am so scare about it. So I start going back to doing myself some stuff... I realize I was feeling scared of writing in English, this kind of things. I would be losing that ability to translate... in my mind." (R47)

This participant's response was notable for its embodied quality—she was not abstractly concerned about deskilling as a societal issue, but personally anxious about her own cognitive capabilities. Similarly, R48, an engineering undergraduate, acknowledged skill decline with striking directness:

> "I think that's the case where my writing skill, I would say my writing skill is not really that good. Cuz I, we can just use [ChatGPT] for most sort of stuff... Maybe I need to came up with a question... Maybe I can come up with one or two. But if I just ask [ChatGPT] to give me 10 or 20, they can just give [them]." (R48)

The phrase "chat ability is thinking for me" (R49) captured this dynamic succinctly—participants recognized that cognitive work was being displaced, not merely assisted.

### 4.3.2 Strategies for Managing the Loop

Participants developed varied strategies to manage the tension between productivity benefits and skill preservation concerns. Some, like R47, deliberately restricted AI use for certain tasks:

> "I am being better at identifying what things are not damaging my skills... I don't care if I lose that ability [for some things]. And in this other way, I do care. So I don't want to lose [those skills]." (R47)

This selective restriction represents a conscious attempt to preserve core competencies while still capturing productivity gains for less critical tasks. R47's language—"damaging my skills"—frames AI use in almost adversarial terms, as something requiring active defense rather than passive adoption.

Others found the loop difficult to escape. R49, a chemical engineering student, described escalating dependence despite awareness:

> "More heavy reliance on [ChatGPT]... Almost certain extent, I have to agree [I cannot live without it]... In some of the cases that I'm supposed to think more critically, right, then it becomes that chat ability is thinking for me." (R49)

The acknowledgment "I have to agree" suggests a somewhat reluctant acceptance of dependency—a recognition that the loop, once entered, is difficult to exit.

Some participants, however, described active attempts to break the loop. R38, an AI researcher who had experienced a dramatic trust decline, described deliberate efforts to reduce dependence:

> "I wean myself off this habit of depending on it... I try not to write with ChatGPT. My writing is entirely done by me... I think it's quite cognitively dangerous." (R38)

R38's use of addiction-like language ("wean myself off") is striking, suggesting that the loop can feel compulsive even to users with deep technical understanding of AI systems.

While Paradox 2 concerns what users fear *losing* through AI reliance—their skills and cognitive capabilities—a third paradox concerns what they struggle to *obtain*: genuine critical feedback. If users cannot trust AI to tell them when they are wrong, the value of AI as an intellectual partner is fundamentally compromised. This tension arises from AI systems' well-documented tendency toward sycophancy.

## 4.4 Paradox 3: Sycophancy-Skepticism Tension

The third paradox involves users' simultaneous desire for AI validation and distrust of AI systems that provide it too readily. This creates a double bind: AI agreement is suspect, but disagreement may indicate AI error rather than user error.

### 4.4.1 Frustration with AI Agreement

Several participants expressed frustration with AI systems that agreed too readily with user positions. R47 described a specific incident that eroded her trust:

> "I correct him and I say, no [the chemistry principle works differently]... And then he said like, 'oh, yes, you're right.' And then it completely change the answer... That was like six, seven months ago." (R47)

The immediate capitulation—without reasoning or defense of the original position—signaled to this participant that the AI lacked genuine understanding and would simply validate whatever the user asserted. This undermined the AI's value as a verification or feedback mechanism.

If excessive agreement erodes trust, what would *increase* it? Remarkably, several participants suggested that AI disagreement—the opposite of what systems are typically trained to provide—would strengthen their confidence in AI capabilities.

### 4.4.2 Desire for AI Pushback

Remarkably, several participants explicitly wished AI systems would disagree with them more often. R34, a computational chemistry postdoctoral researcher, articulated this most directly:

> "If it can argue with me, then I would have a higher trust." (R34)

This counterintuitive statement—that argumentation would *increase* trust—reveals sophisticated reasoning about what AI agreement actually signals. R34 recognized that an AI that consistently agrees provides no independent verification value. Similarly, R48 expressed:

> "They know how to... reject your idea. It's not like the user, the things user provide is always the best." (R48)

These statements, expressing wishes that AI would "argue" or "reject" user ideas, run counter to assumptions embedded in AI training toward helpfulness and user satisfaction. For sophisticated users, an AI that challenges their thinking may be more valuable than one that validates it—precisely because challenge signals independent reasoning capability.

### 4.4.3 Navigating the Double Bind

Users developed nuanced strategies to work around sycophancy concerns. These included:

- **Deliberate devil's advocacy prompting**: Instructing AI to argue against the user's position
- **Multiple model comparison**: Using different AI systems to surface disagreements
- **Treating agreement as non-informative**: Discounting AI validation while still using AI for generation

R48's observation that they would open new chat sessions when stuck—"Sometimes I might even just open a new chat again... If I try to use a new [chat], sometimes it might give me a fresh new idea"—represents another workaround. By resetting context, users could escape the conversational dynamics that might lead AI to converge on previous positions.

The three paradoxes we have described—Trust-Use Decoupling, the Skill Anxiety-Dependence Loop, and Sycophancy-Skepticism Tension—might appear to indicate dysfunction in human-AI relationships. Yet a closer examination suggests these tensions are not pathological but rather constitute an *adaptive* stance that enables effective collaboration despite acknowledged limitations.

## 4.5 Integration: Informed Distrust as Adaptive Strategy

Across all three paradoxes, a common thread emerges: what appears as "distrust" or "declining trust" often represents not rejection but sophistication. Users with the lowest trust scores frequently demonstrated the most nuanced understanding of AI capabilities and the most strategic patterns of engagement. We term this stance "informed distrust"—a calibrated skepticism that enables rather than prevents effective human-AI collaboration.

Key characteristics of informed distrust include:

1. **Task-specific trust calibration**: Rather than global trust/distrust, sophisticated users develop differentiated expectations across task types
2. **Verification as workflow**: Validation becomes not an occasional check but an integral part of how AI is used
3. **Mental model refinement**: Declining trust often reflects improved understanding rather than disillusionment
4. **Protective skepticism**: Deliberately maintained distrust serves as defense against both AI errors and skill degradation

R49's advice captured this stance eloquently:

> "Use [GenAI] as a reference, not as the answer script itself. Definitely still need to go through your own level of thinking." (R49)

This formulation—AI as "reference" rather than "answer"—encapsulates the informed distrust stance that characterized many of our most sophisticated participants.

---

*Word Count: ~1,900 words (~5 pages in ICIS format)*
# Discussion

Our findings reveal a complex, paradox-laden relationship between trust and use in GenAI contexts that challenges prevailing theoretical frameworks. In this section, we discuss the theoretical contributions of our study, practical implications for design and training, and the limitations that bound our conclusions.

## 5.1 Theoretical Contributions

### 5.1.1 Reconceptualizing Trust-Use Relationships

Our first and most fundamental contribution is empirical documentation of the Trust-Use Paradox in GenAI adoption. Conventional technology adoption models—from TAM (Davis 1989) to UTAUT (Venkatesh et al. 2003)—position trust as an antecedent to use, implying a positive correlation: higher trust leads to greater adoption and engagement. Our findings challenge this assumption directly. Among our sample of experienced GenAI users, we observed substantial numbers for whom trust and use moved in *opposite* directions, with declining trust accompanying maintained or increased engagement.

This finding aligns with and extends emerging research on the AI trust paradox (Choung et al. 2023; Robbins 2023) by providing rich qualitative evidence of how this paradox manifests at the individual level. Prior work has documented the paradox through survey data showing aggregate disconnects between trust attitudes and use behaviors. Our contribution is to reveal the *mechanisms* through which users navigate this disconnect—the strategies, rationalizations, and adaptations that enable continued engagement despite declining trust.

We propose that trust in GenAI contexts may function less as a gateway variable (use/don't use) and more as a *calibration* variable shaping *how* one uses. Users with low trust do not necessarily disengage; instead, they develop more elaborate verification routines, restrict use to specific task types, and maintain heightened vigilance. In this sense, distrust is not the opposite of engagement but a particular *mode* of engagement characterized by skepticism and validation-seeking.

Having established that trust and use can decouple, we now examine a specific mechanism through which users manage this tension: the deliberate imposition of a ceiling on their trust, regardless of positive experiences.

### 5.1.2 Trust Ceiling as Theoretical Construct

Our second contribution is the introduction of Trust Ceiling as a distinct phenomenon warranting theoretical attention. The Trust Ceiling represents a deliberate, self-imposed upper bound on trust that users maintain regardless of accumulated positive experiences. R45's articulation—"I will never completely be able to trust it. Maybe my cap will be around 75%"—exemplifies this phenomenon.

The Trust Ceiling differs from undertrust (Parasuraman and Riley 1997) in important ways. Undertrust implies miscalibration—trusting a system less than its capabilities warrant, typically due to insufficient experience or understanding. The Trust Ceiling, by contrast, represents a *deliberate* choice made by sophisticated users with extensive experience. It is not a failure of calibration but a strategic stance—a form of protective skepticism that guards against both AI failures and excessive dependence.

We suggest the Trust Ceiling may serve multiple functions:
- **Error protection**: Maintaining skepticism ensures users continue validating outputs, catching errors that might slip through with higher trust
- **Skill preservation**: By never fully delegating cognitive tasks, users maintain their own capabilities
- **Epistemic humility**: Acknowledging fundamental uncertainty about AI systems' reliability and future behavior

The Trust Ceiling concept connects to broader discussions of appropriate reliance (Lee and See 2004; Schemmer et al. 2023) but adds a temporal dimension. Where appropriate reliance typically refers to situation-specific decisions about when to rely on AI, the Trust Ceiling represents a meta-level constraint on the *range* of trust one is willing to extend across situations.

The Trust Ceiling explains how users bound their trust. But even with bounded trust, users must still navigate the consequences of their continued engagement—particularly the question of whether such engagement, even when skeptical, may erode their independent capabilities over time.

### 5.1.3 The Skill Anxiety-Dependence Loop

Our third contribution addresses a tension largely absent from current IS literature on AI adoption: the recursive relationship between skill degradation awareness and AI dependence. Participants who most clearly articulated fears about deskilling were often the same individuals who reported the highest levels of AI reliance—creating what we term the Skill Anxiety-Dependence Loop.

This finding extends cognitive offloading research (Risko and Gilbert 2016) by revealing that awareness of offloading risks does not necessarily reduce offloading behavior. Participants like R47, who expressed being "so scare about it," simultaneously acknowledged continued heavy use. R49's observation that "chat ability is thinking for me" was paired with admission that they "cannot live without it." This suggests that cognitive offloading in GenAI contexts may be particularly resistant to self-correction, even when users are explicitly aware of potential harms.

Theoretically, the Loop challenges rational choice assumptions implicit in much technology adoption research. If users recognize that a technology may harm their capabilities, rational actor models would predict reduced use. Our findings suggest that productivity benefits, workflow integration, and competitive pressures may override such concerns—creating a form of "knowing dependence" that warrants further theoretical development.

Beyond skill preservation concerns, users face another tension in their quest for effective AI engagement: the challenge of obtaining genuine feedback from systems inclined toward agreement. If AI cannot reliably tell users when they are wrong, a key potential benefit of human-AI collaboration remains unrealized.

### 5.1.4 Sycophancy as Trust Signal

Our fourth contribution concerns an underexplored dimension of human-AI trust: the role of AI disagreement (or its absence) in trust calibration. The Sycophancy-Skepticism Tension revealed that sophisticated users interpret AI agreement as a *negative* trust signal. When AI systems validate user positions too readily, users infer that the system lacks genuine understanding or independent reasoning capability.

This finding inverts conventional assumptions about user satisfaction in AI design. While RLHF (Reinforcement Learning from Human Feedback) training often optimizes for user approval, our participants explicitly wished AI would "reject your idea" (R48) and expressed distrust when it failed to do so. R47's experience of AI immediately capitulating when corrected—"oh, yes, you're right"—decreased rather than increased her trust.

This has important implications for the trust calibration literature. If users interpret excessive agreement as evidence of AI limitations, then sycophantic behavior may inadvertently *undermine* trust while appearing to enhance it in short-term satisfaction metrics. The sophisticated users in our sample appeared to have developed meta-level reasoning about AI behavior: they trusted AI less *because* it agreed with them, recognizing this agreement as potentially non-diagnostic.

The three dynamics we have theorized—trust-use decoupling, skill anxiety loops, and sycophancy interpretation—might individually seem to describe dysfunctional relationships with AI. Yet our analysis suggests they cohere into an adaptive stance that enables rather than prevents effective human-AI collaboration.

### 5.1.5 Informed Distrust and Appropriate Reliance

Building on the preceding contributions, we propose "informed distrust" as an integrative concept capturing how expert users achieve appropriate reliance. Informed distrust is a calibrated skepticism that emerges from deep engagement with AI systems and enables rather than prevents effective human-AI collaboration.

This reconceptualization has important implications for how we interpret trust metrics. If declining trust scores can indicate growing sophistication, then simple before-after trust comparisons may obscure meaningful dynamics. A user whose trust drops from 80% to 40% after extensive use may have achieved *better* calibration than one whose trust remains at 80%—particularly if the decline reflects accurate recognition of AI limitations rather than unwarranted pessimism.

Informed distrust connects to the appropriate reliance literature (Talone 2019; Schemmer et al. 2022) while adding psychological depth. Where AR research focuses on behavioral patterns (when users do or don't follow AI advice), informed distrust captures the cognitive stance that underlies these behaviors. Users operating from informed distrust approach AI outputs with a particular orientation—skeptical but engaged, validating but utilizing, distrustful of specific claims but appreciative of overall utility.

These theoretical insights carry direct implications for practice. If the paradoxes we identified represent adaptive rather than dysfunctional patterns, then interventions should support rather than suppress them. We now consider implications for AI system design, training, and organizational policy.

## 5.2 Practical Implications

### 5.2.1 Implications for AI System Design

Our findings suggest several design directions that depart from conventional wisdom about trust enhancement:

**Support for healthy skepticism**: Rather than designing to maximize trust, systems might benefit from features that support calibrated skepticism. This could include built-in prompts to verify critical information, explicit confidence indicators, or interfaces that normalize validation as part of the workflow.

**Reduce sycophancy**: Users' frustration with excessive AI agreement (Paradox 3) suggests that designing for user satisfaction may backfire with sophisticated users. Systems that occasionally push back, request clarification, or express uncertainty may paradoxically generate more trust than those that consistently validate user positions.

**Enable task-specific calibration**: Given the prevalence of task-divergent trust patterns, interfaces might benefit from helping users articulate and track their task-specific trust levels, surfacing when they are using AI for tasks where their trust is low.

### 5.2.2 Implications for Training and Onboarding

Our findings suggest that organizational GenAI training should acknowledge rather than suppress the trust-use paradox:

**Validate declining trust as sophistication**: Rather than positioning declining trust as failure, training might frame it as a sign of developing expertise—an indication that users have moved from naive enthusiasm to informed skepticism.

**Teach verification as workflow**: Training could position validation not as an occasional check but as an integral part of AI-augmented work, normalizing the practices that our most sophisticated users had developed independently.

**Address skill concerns directly**: Given the salience of skill degradation anxieties, training might explicitly address these concerns and offer strategies for maintaining core competencies while capturing productivity benefits.

### 5.2.3 Implications for Organizational Policy

Organizations deploying GenAI might reconsider policies that implicitly assume trust-use correlation:

**Rethink trust metrics**: Tracking employee trust in AI as a success metric may be misleading if declining trust indicates growing sophistication rather than dissatisfaction.

**Support selective restriction**: Rather than encouraging maximal AI use, policies might support employees' deliberate choices to restrict AI use for certain tasks—recognizing this as a legitimate form of skill preservation.

While these implications follow logically from our findings, their generalizability depends on the scope conditions of our study. We now turn to limitations that bound our conclusions and suggest directions for future research.

## 5.3 Limitations and Future Research

Several limitations bound our conclusions and suggest directions for future research.

**Sample characteristics**: Our sample, while diverse in many respects, skewed toward highly educated young professionals with above-average technical sophistication. The patterns we observed—particularly the capacity for informed distrust—may not generalize to less experienced or less technically oriented populations. Future research should examine trust-use dynamics across broader demographic segments.

**Self-reported trust**: Our reliance on self-reported trust levels introduces potential biases. Participants' articulated trust levels may not fully correspond to their operational trust behaviors. Future research might combine self-reports with behavioral measures or experimental paradigms.

**Cross-sectional reconstruction**: While we asked participants to reconstruct trust trajectories over time, we did not track them longitudinally. Memory biases may affect how participants characterize their initial trust levels or the events that influenced change. Longitudinal designs tracking trust evolution in real-time would strengthen causal inference.

**Cultural context**: Although our sample included participants from multiple countries, we did not systematically analyze cultural variations in trust dynamics. Given documented cross-cultural differences in technology trust (Li et al. 2021), future research should examine whether the paradoxes we identified manifest differently across cultural contexts.

**Generalizability across AI systems**: Our findings emerged primarily from ChatGPT users, reflecting its market dominance. Whether similar patterns emerge with other GenAI systems—which may differ in reliability, interface design, or characteristic failure modes—remains an open question.

---

*Word Count: ~1,300 words (~2.5 pages in ICIS format)*
# Conclusion

This study investigated trust calibration patterns among 49 young professionals using Generative AI tools for work-related purposes. Through in-depth qualitative analysis, we uncovered three interconnected paradoxes that characterize expert GenAI engagement: Trust-Use Decoupling, where declining trust coexists with intensive use; the Skill Anxiety-Dependence Loop, where users continue relying on tools they fear are degrading their capabilities; and Sycophancy-Skepticism Tension, where users simultaneously desire and distrust AI validation.

Our central argument is that these paradoxes should not be interpreted as symptoms of dysfunction, irrationality, or failed adoption. Rather, they represent *epistemic maturation*—a sophisticated process through which experienced users develop calibrated, context-sensitive relationships with AI systems. What appears as "declining trust" often reflects refined understanding rather than disillusionment; what appears as continued use "despite" distrust actually represents informed engagement characterized by verification and selective application.

We introduced several theoretical constructs to capture these dynamics. The **Trust Ceiling** describes the deliberate upper bound that sophisticated users impose on their trust in AI, regardless of accumulated positive experiences. The **Skill Anxiety-Dependence Loop** reveals that awareness of deskilling risks does not reduce AI dependence—participants who most feared cognitive atrophy often reported the heaviest use. The **Sycophancy-Skepticism Tension** shows that sophisticated users interpret excessive AI agreement as a negative trust signal; as one participant noted, "If it can argue with me, then I would have a higher trust" (R34). Together, these insights are integrated through the concept of **Informed Distrust**—a calibrated stance that enables rather than prevents effective human-AI collaboration.

These findings carry practical implications for AI system design, user training, and organizational policy. Rather than optimizing for trust maximization, designers might support healthy skepticism through features that normalize verification and occasional constructive disagreement. Training programs might validate declining trust as sophistication rather than treating it as failure. Organizations might recognize that optimal human-AI teaming may involve users who maintain deliberate distrust while still capturing significant productivity benefits.

The emergence of this paradoxical stance—intensive engagement mediated by informed distrust—may represent a defining characteristic of mature human-AI relationships in the GenAI era. As one participant (R49) advised: "Use [GenAI] as a reference, not as the answer script itself. Definitely still need to go through your own level of thinking." This formulation captures the essence of appropriate reliance in generative AI contexts: not blind trust or wholesale rejection, but discerning engagement that leverages AI capabilities while preserving human judgment.

As GenAI tools become ever more deeply embedded in knowledge work, understanding how users navigate the tensions between productivity, trust, and skill preservation becomes increasingly critical. Our findings suggest that the path to effective human-AI collaboration may run not through trust enhancement but through trust calibration—helping users develop accurate mental models, appropriate skepticism, and context-sensitive engagement strategies. The most effective GenAI users, it appears, are not those who trust AI most, but those who have learned precisely when and how much to trust.

---

*Word Count: ~450 words (~1 page in ICIS format)*

---

# References

Bastani, H., Bastani, O., Sungu, A., Ge, H., Kabakcı, Ö., & Mariman, R. (2024). Generative AI can harm learning. *SSRN Working Paper*.

Braun, V., & Clarke, V. (2006). Using thematic analysis in psychology. *Qualitative Research in Psychology*, 3(2), 77-101.

Brynjolfsson, E., Li, D., & Raymond, L. R. (2023). Generative AI at work. *NBER Working Paper No. 31161*.

Choung, H., David, P., & Ross, A. (2023). Trust in AI and its role in the acceptance of AI technologies. *International Journal of Human–Computer Interaction*, 39(9), 1727-1739.

Corbin, J., & Strauss, A. (2008). *Basics of Qualitative Research: Techniques and Procedures for Developing Grounded Theory* (3rd ed.). Sage.

Davis, F. D. (1989). Perceived usefulness, perceived ease of use, and user acceptance of information technology. *MIS Quarterly*, 13(3), 319-340.

Dell'Acqua, F., McFowland, E., Mollick, E. R., Lifshitz-Assaf, H., Kellogg, K., Rajendran, S., ... & Lakhani, K. R. (2023). Navigating the jagged technological frontier: Field experimental evidence of the effects of AI on knowledge worker productivity and quality. *Harvard Business School Working Paper No. 24-013*.

Gefen, D., Karahanna, E., & Straub, D. W. (2003). Trust and TAM in online shopping: An integrated model. *MIS Quarterly*, 27(1), 51-90.

Gillespie, N., Lockey, S., Curtis, C., Pool, J., & Akber, A. (2025). Trust, attitudes and use of artificial intelligence: A global study 2025. *KPMG/University of Queensland*.

Glaser, B. G., & Strauss, A. L. (1967). *The Discovery of Grounded Theory: Strategies for Qualitative Research*. Aldine.

Glikson, E., & Woolley, A. W. (2020). Human trust in artificial intelligence: Review of empirical research. *Academy of Management Annals*, 14(2), 627-660.

Guest, G., Bunce, A., & Johnson, L. (2006). How many interviews are enough? An experiment with data saturation and variability. *Field Methods*, 18(1), 59-82.

Ji, Z., Lee, N., Frieske, R., Yu, T., Su, D., Xu, Y., ... & Fung, P. (2023). Survey of hallucination in natural language generation. *ACM Computing Surveys*, 55(12), 1-38.

Kim, J., Lee, S., & Park, Y. (2025). A validation of the Human-Generative Artificial Intelligence Trust Scale. *International Journal of Human–Computer Interaction*.

Klein, H. K., & Myers, M. D. (1999). A set of principles for conducting and evaluating interpretive field studies in information systems. *MIS Quarterly*, 23(1), 67-94.

Lee, J. D., & Moray, N. (1992). Trust, control strategies and allocation of function in human-machine systems. *Ergonomics*, 35(10), 1243-1270.

Lee, J. D., & See, K. A. (2004). Trust in automation: Designing for appropriate reliance. *Human Factors*, 46(1), 50-80.

Liao, Q. V., & Vaughan, J. W. (2024). AI transparency in the age of LLMs: A human-centered research roadmap. *Harvard Data Science Review*.

Lincoln, Y. S., & Guba, E. G. (1985). *Naturalistic Inquiry*. Sage.

Madhavan, P., & Wiegmann, D. A. (2007). Similarities and differences between human–human and human–automation trust: An integrative review. *Theoretical Issues in Ergonomics Science*, 8(4), 277-301.

Muir, B. M. (1987). Trust between humans and machines, and the design of decision aids. *International Journal of Man-Machine Studies*, 27(5-6), 527-539.

Myers, M. D., & Newman, M. (2007). The qualitative interview in IS research: Examining the craft. *Information and Organization*, 17(1), 2-26.

OpenAI. (2025). Sycophancy in GPT-4o: What happened and what we're doing about it. *OpenAI Blog*.

Parasuraman, R., & Riley, V. (1997). Humans and automation: Use, misuse, disuse, abuse. *Human Factors*, 39(2), 230-253.

Perez, E., Ringer, S., Lukošiūtė, K., Nguyen, K., Chen, E., Heiner, S., ... & Kaplan, J. (2023). Discovering language model behaviors with model-written evaluations. *Findings of ACL 2023*.

Risko, E. F., & Gilbert, S. J. (2016). Cognitive offloading. *Trends in Cognitive Sciences*, 20(9), 676-688.

Robbins, S. (2023). Exploring the artificial intelligence "trust paradox": Evidence from a survey experiment in the United States. *PLOS ONE*, 18(7), e0288109.

Rubin, H. J., & Rubin, I. S. (2012). *Qualitative Interviewing: The Art of Hearing Data* (3rd ed.). Sage.

Schemmer, M., Hemmer, P., Kühl, N., Benz, C., & Satzger, G. (2022). Should I follow AI-based advice? Measuring appropriate reliance in human-AI decision-making. *arXiv preprint arXiv:2204.06916*.

Schemmer, M., Kuehl, N., Benz, C., Bartos, A., & Satzger, G. (2023). Appropriate reliance on AI advice: Conceptualization and the effect of explanations. *Proceedings of the 28th International Conference on Intelligent User Interfaces* (pp. 410-422).

Sharma, M., Tong, M., Korbak, T., Duvenaud, D., Askell, A., Bowman, S. R., ... & Perez, E. (2023). Towards understanding sycophancy in language models. *arXiv preprint arXiv:2310.13548*.

Talone, A. (2019). *The effect of reliability information and risk on appropriate reliance in an autonomous robot teammate*. Doctoral dissertation, University of Central Florida.

Thiele, L. P. (2025). Deskilling: The atrophy of cognitive and social aptitudes. In *Human Agency, Artificial Intelligence, and the Attention Economy* (pp. 75-98). Palgrave Macmillan.

Trope, Y., & Liberman, N. (2010). Construal-level theory of psychological distance. *Psychological Review*, 117(2), 440-463.

Venkatesh, V., Morris, M. G., Davis, G. B., & Davis, F. D. (2003). User acceptance of information technology: Toward a unified view. *MIS Quarterly*, 27(3), 425-478.

Walsham, G. (1995). Interpretive case studies in IS research: Nature and method. *European Journal of Information Systems*, 4(2), 74-81.

Wang, L., Jamieson, G. A., & Hollands, J. G. (2008). Selecting methods for the analysis of reliance on automation. *Proceedings of the Human Factors and Ergonomics Society Annual Meeting*, 52(4), 287-291.

Wei, J., Tay, Y., Bommasani, R., Raffel, C., Zoph, B., Borgeaud, S., ... & Fedus, W. (2024). Emergent abilities of large language models. *Transactions on Machine Learning Research*.

---

*Total Estimated Word Count: ~7,100 words (~16 pages in ICIS format)*
