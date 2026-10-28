<style>
  /* ---------- Top navigation ---------- */
  .topnav { position: sticky; top: 0; z-index: 10; background: #fff;
            display: flex; flex-wrap: wrap; gap: 1.75rem; padding: 1rem 0; margin-bottom: 1.5rem; }
  .topnav a { text-transform: uppercase; letter-spacing: 0.12em; font-size: 0.85rem;
              color: #8a8799; text-decoration: none; border: none; }
  .topnav a:hover, .topnav a.active { color: #1f1b2e; font-weight: 600; }

  /* ---------- Intro: headshot left, text right ---------- */
  .intro { display: flex; gap: 2.5rem; align-items: flex-start; margin-bottom: 2rem; scroll-margin-top: 4rem; }
  .intro img { width: 350px; flex-shrink: 0; border-radius: 4px;
               box-shadow: 0 6px 20px rgba(0,0,0,0.12); margin-top: .5rem; }
  .intro-text { flex: 1; }
  .intro-text h1 { margin-top: 0; }

  /* Keep headings from hiding under the sticky bar when jumped to */
  h1[id], h2[id] { scroll-margin-top: 4rem; }

  /* ---------- Mobile ---------- */
  @media (max-width: 700px) {
    .topnav { gap: 1rem; }
    .intro { flex-direction: column; align-items: center; }
    .intro img { margin-top: 0; }
  }
</style>

<nav class="topnav">
  <a href="#home" class="active">Home</a>
  <a href="#research">Research</a>
  <a href="#workshops">Service</a>
  <a href="#teaching">Teaching</a>
  <a href="#about-me">About</a>
  <a href="#contact">Links</a>
  <a href="#media">Media</a>
  <!-- href="/cv.pdf">CV-->
</nav>

<div class="intro" id="home">
  <img src="/headshot_2026.jpg" alt="Hope Schroeder headshot">
  <div class="intro-text">
    <p>I'm <strong>Hope Schroeder</strong>, a PhD candidate at the
      <a href="https://www.ccc.mit.edu/">MIT Center for Constructive Communication</a>.</p>
    <p>I study <strong>how AI changes the way people produce, interpret, and communicate knowledge.</strong>
  My research sits at the intersection of <strong>Human–Computer Interaction, Natural Language Processing,
  and Computational Social Science</strong>, where I design and study AI systems that support sensemaking,
  data analysis, and scientific inquiry. I am co-advised by
  <strong><a href="https://www.ccc.mit.edu/person/deb-roy/">Deb Roy</a></strong> and
  <strong><a href="https://miba.dev/">Michiel Bakker</a></strong>.</p>
    <p>My current project investigates pro-AI bias in language models, and how it can affect measurement
      in AI safety evaluations and social science.</p>
    <p><strong>I am on the academic faculty job market and industry research job market in 2026–2027.</strong>
      If you'd like to chat, I'd love to hear from you.</p>
  </div>
</div>

---

<h1 id="research">Research</h1>

My research asks how AI is transforming the production, interpretation, and communication of knowledge.
A central theme of my work is understanding **LLMs as interpretation machines**: systems that increasingly participate in how people analyze information, construct meaning, and produce knowledge.

My work focuses on three connected questions:

---

## 1. Understanding AI-Mediated Interpretation and Judgment

When AI systems participate in interpretation, how do they influence human reasoning?

I study when AI assistance improves judgment, when people over-rely on AI outputs, and how AI changes subjective decision-making processes.

Projects include:

- **[Just Put a Human in the Loop?](https://aclanthology.org/anthology-files/pdf/findings/2025.findings-acl.1323.pdf)** (ACL Findings 2025): a large experimental study of LLM-assisted subjective annotation, examining how people use and evaluate AI-generated suggestions in interpretive tasks. Humans heavily anchor on LLM suggestions when annotating subjective data, even when they're given the chance to change the labels. The interface in which the suggestion is presented affects the strength of the effect. If humans "review" LLM outputs when constructing ground truth data sets, they will likely overestimate the model's performance.
- Research on **AI-assisted qualitative coding and annotation**, investigating how LLMs influence human labeling, judgment, and decision-making.

---

## 2. Designing AI Systems for Knowledge Work

How can we design AI systems that support human sensemaking from multiple perspectives, given that humans anchor on AI outputs?

I build and evaluate AI tools that augment qualitative analysis, conversation exploration, and research workflows. These systems serve as both practical tools and research instruments for understanding how people use AI to make sense of complex information.

Projects include:

- **[Forage](http://forage.ccc-mit.org:8501/)** (CHI 2026): a RAG-based conversation sensemaking system studied with NPR journalists and public-sector workers from the City of Durham, North Carolina. This project showed main use cases for RAG-search in qualitative data analysis, and built and evaluated features that surfaced multiple AI "perspectives" on the same data in order to counteract researcher bias.
  - Paper: [CHI 2026 paper](https://dl.acm.org/doi/10.1145/3772318.3791640)

- **[LLMs in Qualitative Research](https://dl.acm.org/doi/full/10.1145/3706598.3713120)** (CHI 2025): examined current opportunities and challenges when using LLMs in mixed methods and qualitative research workflows, producing a series of decision checkpoints to support researcher intentionality.

- **[Fora: A Corpus and Framework for the Study of Facilitated Dialogue](https://github.com/schropes/fora-corpus)** (ACL 2024): a dataset and framework for studying facilitated dialogue and collaborative meaning-making.
  - Paper: [ACL 2024 paper](https://aclanthology.org/2024.acl-long.754/)

---

## 3. AI and the Transformation of Knowledge Production

As AI becomes part of research and communication, how are norms and methods changing, and what new risks and opportunities are introduced?

I investigate how AI reshapes scientific practice, accountability, and the social processes through which knowledge is produced.

Projects include:

- **[Disclosure without Engagement](https://dl.acm.org/doi/pdf/10.1145/3715275.3732079)** (FAccT 2025): a study of positionality statements in FAccT, a major AI research community, and how researchers engage with questions of accountability and reflexivity.

- **[Understanding the LLM-ification of CHI](https://arxiv.org/pdf/2501.12557)** (CHI 2025): examined how generative AI is reshaping HCI research practice and provided suggestions to responsibly report on AI usage in HCI publications.

- **[Interpretive Cultures: Resonance, Randomness, and Negotiated Meaning for AI-Assisted Tarot Divination](https://dl.acm.org/doi/10.1145/3772318.3791571)** (CHI 2026): studying how people use AI systems to interpret and make sense of personal experiences.

---

<h2 id="workshops">Service</h2>

I also actively contribute to the development of emerging standards within HCI communities related to AI in mixed methods work with scientific and civic impacts. My past workshops include:

- **[Standards for LLMs in Human Subjects Research](https://sites.google.com/andrew.cmu.edu/chi-llm-simulacra/home)** (CHI 2026 Workshop): developing methodological guidance for researchers using LLMs in human-subjects studies.
- **[LLMs as Research Tools](https://dl.acm.org/doi/10.1145/3613905.3636301)** (CHI 2024 Workshop): convening researchers around the use of LLMs in research within HCI and related fields.
- **[NLP for Democracy](https://sites.google.com/andrew.cmu.edu/nlp4democracy/home)** (COLM 2025 Workshop): convening researchers in NLP, HCI, and related fields using LLMs in democracy-related work.

In addition to service to my academic communities, I am also actively involved as a Graduate Resident Advisor at MIT, where I have lived with and mentored undergraduates across fields at the Institute for four years.

---

<h2 id="teaching">Teaching</h2>

In Spring of 2023, I co-instructed a course at the MIT Media Lab called **["Generative AI for Constructive Communication: Evaluation and New Research Methods"](https://ai4comm.media.mit.edu/)** the first course covering the "modern" era of generative AI post-ChatGPT. Course materials are available on **[YouTube](https://www.youtube.com/@GenerativeAIatMIT-bz6zz)**, including my **[introduction](https://www.youtube.com/watch?v=okzJGwYzNas)** to the course.

Papers taught in the course were foundational and have set the course of the next several years of research. 
~20 students from across departments were enrolled and completed mentored research projects.
In addition to this teaching experience, I regularly mentor undergraduate researchers (UROPs) and early stage master's and PhD students.

---

<h2 id="media">Media</h2>

### Press

**Science** piece:

- [If art is how we express our humanity, where does AI fit in?](https://news.mit.edu/2023/generative-ai-art-expression-0615), *MIT News*, June 2023 — Q&A on our *Science* paper, "Art and the science of generative AI."
- [Generative AI is a minefield for copyright law](https://theconversation.com/generative-ai-is-a-minefield-for-copyright-law-207473), *The Conversation*, June 2023 — essay by co-authors Robert Mahari, Jessica Fjeld, and Ziv Epstein drawing on our *Science* paper.



**Dear Visitor**:

Before my PhD, I directed location-based augmented reality projects that use AR to document and reinterpret contested public spaces. A case study of this work received the **[Best Case Study Award at CHI 2023](https://www.media.mit.edu/posts/hope-schroeder-chi-2023/)**. Directed with co-technical directors Kyle Qian and Khoi Le; funded by a Brown Institute Magic Grant. Stanford later approved a plaque with Miller's quote, and our work was covered by global news:

- [Chanel Miller: Stanford University scheme projects her words on to assault site](https://www.bbc.co.uk/news/world-us-canada-49858238), *BBC News*, September 2019
- [Stanford students launch tribute to sexual assault survivor Chanel Miller](https://www.theguardian.com/us-news/2019/sep/27/stanford-students-launch-tribute-to-sexual-assault-survivor-chanel-miller), *The Guardian*, September 2019
- [The top AR apps, projects, and activations of 2019](https://www.forbes.com/sites/jessedamiani/2020/02/27/the-top-ar-apps-projects-and-activations-of-2019/), *Forbes*, February 2020 — Top AR Social Justice Activation of 2019
- [A new garden, a sexual assault and the fight at Stanford over Chanel Miller's voice](https://www.latimes.com/california/story/2019-10-04/the-space-where-brock-turner-sexually-assaulted-chanel-miller-is-at-the-center-of-an-ongoing-battle-at-stanford), *Los Angeles Times*, October 2019
- [Column: Chanel Miller's memoir should be required reading for every cop, judge and prosecutor in America](https://www.latimes.com/opinion/story/2019-09-24/abcarian-chanel-miller-sexual-assault-brock-turner), *Los Angeles Times*, September 2019
- [Augmented reality brings to life words of Stanford sex assault survivor](https://www.sfchronicle.com/bayarea/article/Augmented-reality-project-brings-to-life-words-of-14473441.php), *San Francisco Chronicle*, September 2019
- [A Virtual Memorial Brings a Sexual Assault Survivor's Voice to the Stanford Campus](https://www.motherjones.com/politics/2019/10/stanford-sexual-assault-garden/), *Mother Jones*, October 2019
- [Stanford Students Create Virtual Reality Project to Honor Assault Survivor Chanel Miller](https://www.teenvogue.com/story/stanford-students-create-virtual-reality-memorial-to-assault-survivor-chanel-miller/), *Teen Vogue*, 2019
- [Show of solidarity at Stanford for Chanel Miller's memoir](https://abc7news.com/show-of-solidarity-at-stanford-for-chanel-millers-memoir/5565869/), *ABC7 News*, September 2019
- [Stanford students use AR to keep spotlight on campus sexual assault](https://venturebeat.com/2019/09/19/stanford-students-use-ar-to-keep-spotlight-on-campus-sexual-assault/), *VentureBeat*, September 2019
- [These students are using augmented reality to honor Chanel Miller's words on the Stanford campus](https://www.paloaltoonline.com/news/2019/09/28/these-students-are-using-augmented-reality-to-honor-chanel-millers-words-on-the-stanford-campus), *Palo Alto Weekly*, September 2019
- [AR app lets users see, hear Chanel Miller quotes Stanford rejected at site of her assault](https://www.stanforddaily.com/2019/09/28/ar-app-lets-users-see-hear-chanel-miller-quotes-stanford-rejected-at-site-of-her-assault/), *The Stanford Daily*, September 2019

### Talks

Here is a selection of publicly posted talks I have given recently:
- [Disclosure without Engagement](https://www.youtube.com/watch?v=xouYrAvBTWA) — FAccT 2025 conference talk
- [Young Innovators in AI](https://www.youtube.com/watch?v=LhuEBdkI4Hg) — Invited panel, Imagination in Action: Architects of the Global Future, Davos, January 2025
- [AI-Mediated Annotation](https://www.youtube.com/watch?v=I2zn--vIkgc) - Computation + Journalism 2024 conference talk
- [AR for Social Justice](https://www.youtube.com/watch?v=fwZbk8PQAl8) - CHI 2023 talk, for project which won **Best Case Study Award**
- [Responsible AI Practices](https://www.youtube.com/watch?v=xl_mLILZkiA&t=272s) panel moderator at 2023 MIT GenAI Summit


### Commentary and Writing

In addition to my academic publications, I have also published commentary on AI in research and art, shown below.
- [AI Séance: Recounts from designing artificial intelligence for transcendence, interpretive lenses and chance](https://journals.sagepub.com/doi/10.1177/13675494251351223), *European Journal of Cultural Studies*, 2025. With Amy Smith and Ziv Epstein. See also: [AI Séance at the MIT Chapel](https://www.media.mit.edu/projects/encountering-the-other-ai-seance/overview) (October 2025).
- [The State of Large Language Models in HCI Research: Workshop Report](https://dl.acm.org/doi/fullHtml/10.1145/3705617), *ACM Interactions* 32(1), 2025. With Marianne Aubin Le Quéré, Casey Randazzo, and Jie Gao.

---

<h1 id="about-me">About</h1>

I hold an MSc (Distinction) in Social Data Science from the Oxford Internet Institute as a Clarendon Scholar at Christ Church, Oxford, and a BS with Honors in Symbolic Systems from Stanford University.

During my PhD, I have interned at Microsoft Research NYC twice, once in 2023 with David Rothschild on the Computational Social Science team, and once in 2024 with Solon Barocas on the FATE team.

Earlier in my career, I worked on projects using VR and AR to document and reinterpret contested public spaces. Our **Dear Visitor** project received international press coverage, and a case study on this work received the **Best Case Study Award at CHI 2023**.

Before college, I was a competitive figure skater and won US [national titles in solo ice dance](https://www.paloaltoonline.com/sports/2012/09/27/wheres-there-hope-theres-gold-medal-opportunities/).


<h1 id="contact">Contact</h1>

📧 **hi@hopeschroeder.com**

- [Google Scholar](https://scholar.google.com/citations?user=-UKCJTAAAAAJ&hl=en)
- [Bluesky](https://bsky.app/profile/hopeschroeder.bsky.social)
- [LinkedIn](https://www.linkedin.com/in/hopeschroeder/)
- [Twitter/X](https://twitter.com/Schropes)

<script>
  // Bolds the nav link for whichever section is on screen
  const links = document.querySelectorAll('.topnav a[href^="#"]');
  const spy = new IntersectionObserver(entries => {
    entries.forEach(e => {
      if (e.isIntersecting) links.forEach(a =>
        a.classList.toggle('active', a.getAttribute('href') === '#' + e.target.id));
    });
  }, { rootMargin: '-40% 0px -55% 0px' });
  links.forEach(a => { const t = document.querySelector(a.getAttribute('href')); if (t) spy.observe(t); });
</script>
