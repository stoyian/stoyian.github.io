---
layout: homepage
---

## About Me

I am completing my M.Sc in Computer Science at Athens University of Economics and
Business under the supervision of [Prof. Ion Androutsopoulos](https://www2.aueb.gr/users/ion/) and at the time being, I am a Machine Learning Research Engineer at [helvia.ai](https://helvia.ai/), specializing in NLP and Large Language Models. I am also an active member of the <a href="http://nlp.cs.aueb.gr/" target="_blank"> Natural Language Processing Group </a> at AUEB where we conduct research on NLP and Machine Learning.

You're welcome to reach out to me using the emails provided.
Currently, the time for me is: <span id="current-time"></span>

<script>
  setInterval(() => {
    const now = new Date();
    const options = { hour: '2-digit', minute: '2-digit' ,timeZone: 'Europe/Athens'};
    document.getElementById('current-time').textContent = now.toLocaleTimeString([], options);
  }, 1000);
</script>



## Research Interests


- **Natural Language Processing:** Cost-efficient usage and optimization of LLMs, open-book generative QA, text summarization.
- **Machine Learning:** Active learning, knowledge distillation, adversarial learning.
- **Reinforcement Learning:** Decision-making in complex systems, improved NLG, wireless network routing optimization, vehicular networks and self-driving cars.

## News

- **[Nov. 2023]** Our paper has been selected for poster presentation at EMNLP 2023. See you in Singapore!
- **[Oct. 2023]** My thesis in under the final review and will be available soon in the NLP Group's [website](http://nlp.cs.aueb.gr/theses.html).
- **[Oct. 2023]** Our paper about LLM caching is accepted to the Findings of EMNLP 2023.

{% include_relative _includes/publications.md %}

<!-- {% include_relative _includes/services.md %} -->
