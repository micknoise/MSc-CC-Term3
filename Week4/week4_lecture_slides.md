# MSc Creative Computing
## Practice as Research — Lecture 4
### Choosing and designing methods

Mick Grierson — Creative Computing Institute, UAL

*Black text on white. ~20 slides. Speaker notes under each.*

---

## Slide 1 — Title

**Choosing and Designing Methods**
Lecture 4 of 8 — Practice as Research

Mick Grierson, [Creative Computing Institute](https://www.arts.ac.uk/colleges/creative-computing-institute), UAL

> **Speaker note:** We're halfway through the series. By now students should have a working research question and a draft gap statement. This week we ask: once you know *what* you're investigating, *how* do you investigate it? The word "method" can feel intimidating — it shouldn't. A method is just a principled way of finding things out.

---

## Slide 2 — Recap: where we are

Week 1: Research = edge + hypothesis + test.
Week 2: Practice produces knowledge — procedural, experiential, tacit, propositional, critical.
Week 3: Finding the gap — situating your work in a field.

Today: **How do you investigate your gap?**

A gap tells you what's missing. A method tells you how you're going to fill it — and why that approach is appropriate.

> **Speaker note:** Emphasise the connection: the gap shapes the method, and the method shapes what kind of knowledge you can produce. If your gap is "we don't know how audiences respond to X," you need a method that involves audiences. If your gap is "no system exists that does Y," you need a method that involves building a system. This sounds obvious but students often choose methods that don't match their question.

---

## Slide 3 — What is a method?

A method is a **systematic way of doing something that can be described, justified, and repeated** (at least in principle).

It is not the same as a tool. Python is not a method. TensorFlow is not a method. A method is the *logic* behind what you do with those tools.

"I trained a neural network" is not a method.
"I trained a neural network on X data, varied Y parameter, measured Z outcome, and compared against baseline W" — that's closer.

> **Speaker note:** The tool/method distinction trips up technical students especially. They describe what software they used, not what investigative logic they followed. The method is the *why* and the *how*, not the *with what*. Push on this: "you used PyTorch — great. But what was your experimental design? What were you comparing? How did you know when you'd learned something?"

---

## Slide 4 — Methods are not one-size-fits-all

Different research questions need different methods. The method has to match:

**The type of gap** — a knowledge gap needs investigation; a method gap needs construction and evaluation; a critical gap needs analysis and argumentation.

**The type of knowledge you want to produce** — propositional knowledge needs controlled comparison; experiential knowledge needs encounter and documentation; tacit knowledge needs reflective practice.

**The practical constraints** — time, access, equipment, ethics, your own skills.

There is no single correct method for any project. There are better and worse fits.

> **Speaker note:** This is the key message of the lecture: methods are chosen, not given. You choose a method because it's the right tool for your question, not because it's the one you happen to know. That said, practical constraints are real — if you only have 12 weeks and no budget for participants, a large-scale user study isn't realistic. Part of good research design is knowing what's feasible.

---

## Slide 5 — Haseman's three paradigms

Haseman (2006) argues that practice-led research doesn't fit neatly into the two established paradigms:

**Quantitative** — hypothesis testing, controlled variables, statistical analysis. Produces numerical data. Answers "how much" and "how often."

**Qualitative** — interviews, ethnography, thematic analysis. Produces textual/descriptive data. Answers "what is it like" and "what does it mean."

**Performative** — Haseman's proposed third paradigm. The research output is not a number or a text — it is a **practice**, an artefact, a performance. The research is expressed *through* the doing.

Most creative computing projects involve elements of **all three**. The question is which is primary and how the others support it.

> **Speaker note:** Haseman's argument is that neither quantitative nor qualitative methods fully capture what practice-based researchers do. He's not dismissing those paradigms — he's saying there's a third one that the academy hasn't fully recognised. In creative computing, you might build a system (performative), measure its performance (quantitative), and interview people who used it (qualitative). The combination is fine — encouraged, even. But you should know which paradigm your core contribution sits in.

---

## Slide 6 — A toolkit of methods for practice-based research

Here are methods you are likely to use. You don't need all of them. You need the ones that fit your question.

**Construction / system building** — you make something. The making *is* the investigation. This is the core of most practice-based work in creative computing.

**Technical evaluation** — you measure your system's performance against a baseline or benchmark. Latency, accuracy, perceptual quality, computational cost.

**User study / participant evaluation** — you put your system in front of people and gather data on how they experience, use, or respond to it.

**Reflective practice** — you document your own process of making, noting decisions, surprises, dead ends, and discoveries. This is where tacit knowledge becomes (partially) explicit.

**Comparative analysis** — you compare your approach to existing approaches, technically or critically.

**Critical/theoretical analysis** — you use theory to interpret what your artefact does or reveals.

> **Speaker note:** Walk through each briefly with an example. Construction: "I built a real-time generative audio system." Technical evaluation: "I measured its latency at 12ms vs 45ms for the baseline." User study: "I had 10 performers use it and interviewed them afterwards." Reflective practice: "I kept a studio log of every design decision and why I made it." Comparative: "I compared the timbral range of my system's output against three existing synthesisers." Critical: "I used Borgdorff's framework to argue that the system produces non-propositional knowledge." Most projects use 2–3 of these.

---

## Slide 7 — Construction as method

In creative computing, **building something is itself a research method** — not a preliminary to research.

This is what Borgdorff means by research *in and through* the arts, and what Smith & Dean's iterative cyclic web describes: the building process generates knowledge that couldn't have been produced any other way.

But construction alone is not sufficient. You also need to:

1. **Document** what you built and why — the design decisions, the architecture, the constraints.
2. **Contextualise** it — how does it relate to what already exists?
3. **Evaluate** it — does it do what you hoped? What did it reveal? What surprised you?

Construction + documentation + contextualisation + evaluation = a research contribution.

> **Speaker note:** This is the most important slide for this cohort. Most of them will build things. The temptation is to treat the building as the whole project and the writing as an afterthought. Resist that. The building generates the knowledge; the writing makes the knowledge communicable. Without the writing, you have a demo. With it, you have a contribution.

---

## Slide 8 — Technical evaluation: what to measure and how

If your project involves building a system, you will probably need some form of technical evaluation. Common approaches:

**Benchmarking** — compare your system's output to established baselines using standard metrics (e.g. FID for image generation, PESQ/POLQA for audio quality, latency measurements for real-time systems).

**Ablation studies** — remove or change components of your system to show what each part contributes.

**Stress testing** — push the system to its limits. Where does it break? What are the failure modes?

**Reproducibility** — can someone else run your code and get comparable results? Releasing code and data is part of the method.

Not all of these will apply to your project. Choose the ones that address your research question.

> **Speaker note:** Technical evaluation is where creative computing overlaps with CS/engineering. Students from art backgrounds may need support here; students from CS backgrounds may over-rely on it. The point is not to produce a benchmark paper — it's to demonstrate that your system does what you claim it does, and to show *how well* it does it relative to alternatives.

---

## Slide 9 — User studies and participant evaluation

If your project involves people experiencing, using, or responding to your work, you need a user study. Common approaches in creative computing:

**Structured interviews** — you ask participants predefined questions about their experience. Good for depth.

**Questionnaires / surveys** — standardised instruments (e.g. [SUS](https://www.usability.gov/how-to-and-tools/methods/system-usability-scale.html) for usability, [NASA-TLX](https://humansystems.arc.nasa.gov/groups/TLX/) for cognitive load, [AttrakDiff](http://www.attrakdiff.de/) for user experience). Good for breadth and comparability.

**Think-aloud protocols** — participants narrate their experience while using your system. Good for understanding process.

**Observation** — you watch people interact with your work and note what happens. Good for behaviour you can't self-report.

**Workshops / co-design sessions** — participants contribute to the design process itself. Good for participatory and speculative projects.

Key resources:
- Lazar, Feng & Hochheiser (2017). [*Research Methods in Human-Computer Interaction*](https://www.sciencedirect.com/book/monograph/9780128053904/research-methods-in-human-computer-interaction), 2nd ed. Morgan Kaufmann. — The standard HCI methods textbook.
- Cairns & Cox (eds.) (2008). [*Research Methods for Human-Computer Interaction*](https://www.cambridge.org/core/books/research-methods-for-humancomputer-interaction/43E95E979117C42DF822673D098474D2). Cambridge University Press.

> **Speaker note:** If students are doing any kind of user-facing work, point them to Lazar et al. It's comprehensive and practical. Also flag that any study involving participants will need ethical approval — we'll cover that in the next two slides. For sample sizes: in HCI and creative computing, qualitative studies with 5–12 participants are common and legitimate, provided you justify the number and analyse rigorously.

---

## Slide 10 — Reflective practice as method

Reflective practice means **systematically documenting your own process of making** — not as a diary, but as evidence.

This draws on Donald Schön's (1983) concept of the **reflective practitioner**: someone who thinks about what they're doing *while they're doing it*, and uses that reflection to steer the next action.

Practical forms:

**Studio/lab log** — regular dated entries recording what you did, what happened, what you decided, and why. Digital or physical.

**Annotated portfolio** — a curated set of artefacts (prototypes, sketches, outputs, screenshots) with written commentary explaining what each reveals.

**Process documentation** — video, screen recordings, version histories, commit logs with meaningful messages.

The key: reflective practice is not "I did X." It is "I did X, expecting Y, but Z happened, which led me to revise my understanding of W."

> **Speaker note:** Schön is the foundational reference here. Reflective practice is sometimes dismissed as "just keeping a journal" — it isn't. The journal is the raw material; the reflection is the analytical work you do on it. The annotated portfolio approach (Gaver & Bowers, 2012, in CHI) is especially useful for creative computing — it treats the artefacts themselves as evidence and the annotations as interpretation. If students are building iteratively, their Git history is already a partial process document. Encourage them to use meaningful commit messages.

---

## Slide 11 — Methods you can use without reinventing the wheel

You don't need to invent a new method. Established frameworks exist and are there to be used:

**For building + evaluating interactive systems:**
- [Research through Design (RtD)](https://ixdf.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/research-through-design) — Zimmerman, Stolterman, and others. Design process as research inquiry. Well established in HCI.
- [Design Science Research](https://link.springer.com/article/10.1007/s10796-006-9048-8) — Hevner et al. (2004). Build an artefact, evaluate it, articulate the contribution. Common in information systems.

**For understanding user experience:**
- [Thematic Analysis](https://www.tandfonline.com/doi/abs/10.1191/1478088706qp063oa) — Braun & Clarke (2006). The standard method for analysing qualitative data (interviews, open-ended responses). Widely used, well documented, citable.
- [System Usability Scale (SUS)](https://www.usability.gov/how-to-and-tools/methods/system-usability-scale.html) — Brooke (1996). A 10-item questionnaire for quick usability assessment. Free, validated, takes 2 minutes to administer.

**For documenting creative process:**
- [Annotated Portfolios](https://dl.acm.org/doi/10.1145/2317956.2318036) — Gaver & Bowers (2012). A method for presenting design artefacts as research contributions.
- Nelson, R. (2013). [*Practice as Research in the Arts*](https://link.springer.com/book/10.1057/9781137282910). Palgrave Macmillan. — Chapter 3 on "multi-mode epistemological model" for PaR.

**For technical comparison:**
- Standard ML evaluation protocols — train/test splits, cross-validation, ablation. Any good ML textbook covers these.

> **Speaker note:** The point of this slide is to save students time. These are well-cited, well-documented methods with clear procedures. Using them doesn't make your work less original — it makes it more rigorous and easier to assess. If a student says "I did thematic analysis following Braun & Clarke (2006)," an examiner immediately knows what that means and can evaluate whether it was done well. If a student says "I sort of grouped the responses by theme," the examiner has no way to assess the rigour. Name your methods. Cite them.

---

## Slide 12 — Combining methods

Most practice-based projects in creative computing use a **mixed-methods** approach:

A typical structure might be:

1. **Construction** — build the system.
2. **Technical evaluation** — measure its performance.
3. **User study** — have people use it and gather their responses.
4. **Reflective practice** — document the design process and what you learned from it.
5. **Critical framing** — use theory to interpret the results.

You don't need all five. But you almost certainly need more than one.

The methods should be **integrated, not bolted on**. Each method should address a different aspect of the research question, and together they should produce a richer answer than any one method alone.

> **Speaker note:** "Bolted on" is the danger. A user study that doesn't connect to the research question is busywork. A technical evaluation that doesn't relate to the gap is irrelevant. Every method should earn its place by contributing something the others can't. If students are unsure, ask them: "what does this method tell you that the others don't?"

---

## Slide 13 — Writing a methods section

Your written submission will need a methods section. It should cover:

1. **What methods you used** — named and cited.
2. **Why you chose them** — how they match your research question and gap.
3. **How you applied them** — enough detail that someone could follow your process.
4. **What data they produced** — what kind of evidence you gathered.
5. **How you analysed that data** — the analytical framework.

A good methods section is specific and honest. It includes limitations: "I had 8 participants rather than 20 because of time constraints. This limits the generalisability of the findings but is sufficient for a qualitative exploration."

> **Speaker note:** Students often write methods sections that are either too vague ("I tested it with some people") or too detailed about the wrong things ("I used a MacBook Pro M2 with 16GB RAM" — irrelevant unless hardware is part of the contribution). The test is: could someone read this section and understand your investigative logic? Could they, in principle, do something similar?

---

## Slide 14 — Ethics: why this matters

Any research that involves other people, their data, or potential risks requires **ethical approval before you begin**.

This is not bureaucracy for its own sake. It exists to protect:

- **Participants** — from harm, deception, or exploitation.
- **You** — from doing something that causes harm you didn't anticipate.
- **The institution** — from liability.
- **The field** — from losing public trust.

If your project involves human participants, secondary human data, external collaborators, or any of the categories we're about to discuss — you need to go through the ethics process. And you need to do it **before you collect any data**, not after.

> **Speaker note:** Be direct: students sometimes see ethics approval as an obstacle. It isn't. It's a design constraint that makes your research better. The process of filling in an ethics application forces you to think through your method carefully — who are your participants, what are you asking of them, how will you protect their data, what happens if something goes wrong? These are questions you should be asking anyway. The form just makes you write the answers down.

---

## Slide 15 — CCI ethics procedures: what you need to do

All MSc students at CCI must complete the **ethics pre-screen checklist** before any data gathering begins.

The checklist is here: [CCI Ethics Pre-Screen Checklist](https://forms.office.com/e/tDXR4bLikJ?origin=lprLink)

Full details: [CCI Taught Course Ethics Procedures](https://wiki.cci.arts.ac.uk/books/research-knowledge-exchange-ethics/page/taught-course-ethics-procedures-aka-educational-ethics)

**Your project is likely to have an ethical dimension if it involves:**

- Other people — as participants, users, testers, or subjects of observation (including in a professional capacity)
- Human data — whether you collect it yourself (primary) or use existing datasets (secondary, e.g. social media posts, medical records)
- External collaborators — companies, organisations, community groups
- Animals, human tissue, or environmental impact
- Health and safety risks beyond everyday life

The most common scenario for this cohort: **you're building something and asking people to use it**, or **you're using a dataset that contains human-generated content**. Both require ethical consideration.

> **Speaker note:** Be concrete about the common cases. "I scraped tweets for my training data" — that's secondary human data, needs ethics review. "I had my flatmates test my app" — that's a user study, needs ethics review. "I only used publicly available data" — still needs review, because public availability doesn't mean consent for research use. The pre-screen checklist is not the full application — it's a triage step that determines whether you need the full application. Everyone does the pre-screen. Not everyone needs the full application.

---

## Slide 16 — If the pre-screen says you need full approval

If the pre-screen identifies that your project has ethical dimensions requiring approval, you will need to:

1. Complete the [ethics application form](https://artslondon.sharepoint.com/:w:/t/CCICRESC583/EaNQpsseI85MqPPhu-l3-3AB1c_0aLg3jEmMvdKKSvNPmg?e=lvfHQa) with your supervisor.
2. Prepare a [Participant Information & Consent Form](https://artslondon.sharepoint.com/:w:/t/CCICRESC583/EUKGtar3dg9ApSGJO9oaDJoBei5fROENFLLsh5NApzRVRQ?e=nCziHs).
3. Submit both to **cci-cresc@arts.ac.uk** with the subject line: **MSc project ethics application**.

**Minimise risk.** Most student projects should be **minimal risk** — defined as risk no greater than what participants encounter in everyday life. If your project goes above minimal risk (vulnerable participants, sensitive topics, deception, confidential records), it will be reviewed by the UAL educational ethics sub-committee, which takes longer.

**If your project changes** after approval, submit a [Notice of Amendment](https://artslondon.sharepoint.com/:w:/t/CCICRESC583/EbWJA-9bvelIo5f-6Wlg02wBkvMc4ny1wKDCNp_Nf2ip6w?e=0yzZQf). Substantial changes may require a new application.

Questions? Contact **cci-cresc@arts.ac.uk** or **#research-ethics** on Slack.

> **Speaker note:** Don't rush through this. Students need to know these deadlines and links exist, and they need to know that ethics approval takes time — so if they're planning a user study for their final project, they should start the ethics process *now*, not two weeks before they want to run it. Also: the consent form is not just a signature page. It's a document that tells participants exactly what you're doing, why, what data you'll collect, how you'll store it, and how they can withdraw. Writing a good consent form is a research skill.

---

## Slide 17 — Method design as research design

Choosing methods is not a box-ticking exercise. It is **research design** — the architecture of your investigation.

Good research design means:

- Your methods **match your question**. (Don't run a user study if your question is about computational efficiency.)
- Your methods **produce the right kind of evidence**. (Don't use a questionnaire if you need rich descriptions of experience.)
- Your methods are **feasible**. (Don't plan for 50 participants if you have 6 weeks.)
- Your methods are **ethical**. (Don't collect data you don't need. Don't expose participants to unnecessary risk.)
- Your methods are **documented and justified** in your writing.

The test: can you explain, in two sentences, what your method is and why it's the right one for your question?

> **Speaker note:** The two-sentence test is worth doing out loud. "My method is X, because my question is about Y and X is the established way of investigating Y." If students can say that clearly, they're in good shape. If they can't, they need to refine either the method or the question.

---

## Slide 18 — An exercise: method matching

Here are three fictional project descriptions. For each, identify which methods from slide 6 would be appropriate, and why.

**Project A:** A real-time system that generates ambient soundscapes from weather data, intended for public installation.
**Project B:** A tool that helps non-programmers fine-tune image generation models, with the goal of making the process more accessible.
**Project C:** An artistic investigation of how language models represent gender, expressed as a series of generated text-and-image compositions.

Take 10 minutes. For each project, name 2–3 methods and write one sentence explaining why each is appropriate.

> **Speaker note:** This is the in-class exercise. Keep it to 10 minutes of writing, then 5 minutes of discussion. Likely answers — Project A: construction + technical evaluation (latency, audio quality) + reflective practice (design decisions for the installation context). Project B: construction + user study (usability testing with non-programmers) + comparative analysis (how does it compare to existing fine-tuning interfaces?). Project C: construction + critical/theoretical analysis (using gender theory to interpret the outputs) + reflective practice (documenting the artistic decision-making). Accept other reasonable answers — the point is that students can justify their choices.

---

## Slide 19 — For next week

Week 5: **Documentation — what to document and how.**

You've now got a question, a gap, and a method. Next week we ask: what counts as evidence in practice-based research, and how do you capture it?

No required reading — but if you want to get ahead:

- Gaver, W. & Bowers, J. (2012). [Annotated Portfolios](https://dl.acm.org/doi/10.1145/2317956.2318036). *Interactions*, 19(4), 40–49.
- Keep a process log this week. Just notes — what you're doing, why, what's happening. We'll use these in Week 5.

> **Speaker note:** Week 5 is where process documentation becomes concrete. If students start logging their process *this week*, they'll have material to work with next time. Even rough notes are useful. The habit matters more than the format.

---

## Slide 20 — References

Haseman, B. (2006). ["A Manifesto for Performative Research."](https://journals.sagepub.com/doi/10.1177/1329878X0611800113) *Media International Australia*, 118(1), 98–106.

Nelson, R. (2013). [*Practice as Research in the Arts.*](https://link.springer.com/book/10.1057/9781137282910) Palgrave Macmillan.

Schön, D. (1983). *The Reflective Practitioner.* Basic Books.

Braun, V. & Clarke, V. (2006). ["Using Thematic Analysis in Psychology."](https://www.tandfonline.com/doi/abs/10.1191/1478088706qp063oa) *Qualitative Research in Psychology*, 3(2), 77–101.

Gaver, W. & Bowers, J. (2012). ["Annotated Portfolios."](https://dl.acm.org/doi/10.1145/2317956.2318036) *Interactions*, 19(4), 40–49.

Zimmerman, J., Forlizzi, J. & Evenson, S. (2007). ["Research through Design as a Method for Interaction Design Research in HCI."](https://dl.acm.org/doi/10.1145/1240624.1240704) *CHI '07*, 493–502.

Hevner, A. et al. (2004). ["Design Science in Information Systems Research."](https://link.springer.com/article/10.1007/s10796-006-9048-8) *MIS Quarterly*, 28(1), 75–105.

Lazar, J., Feng, J. H. & Hochheiser, H. (2017). [*Research Methods in Human-Computer Interaction*](https://www.sciencedirect.com/book/monograph/9780128053904/research-methods-in-human-computer-interaction), 2nd ed. Morgan Kaufmann.

Brooke, J. (1996). "SUS: A 'Quick and Dirty' Usability Scale." In Jordan et al. (eds.), *Usability Evaluation in Industry*. Taylor & Francis, 189–194.

[CCI Taught Course Ethics Procedures](https://wiki.cci.arts.ac.uk/books/research-knowledge-exchange-ethics/page/taught-course-ethics-procedures-aka-educational-ethics)

[UAL Research Ethics Policy](https://artslondon.sharepoint.com/:b:/s/CCI/ERT-H4auVVxFmZPFI3OJCskBnXqpo63uRMWUbgF7qPNv0w?e=n0NocH)

---

## Slide 21 — Questions

What method are you leaning towards?
What's stopping you from starting?
Does your project involve participants — and have you started the ethics process?

---

# End of deck
