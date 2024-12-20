---
layout: archive
permalink: /reflections/
author_profile: true
---

<div style="display: flex; align-items: center; font-size: 14px; font-family: 'Times New Roman', Times, serif; color:rgb(0, 0, 0); margin-top: 15px;">
    Sharing my Reflections on the courses I took as a Data Science major (MS) student at UCSD
</div>

<div style="justify-content: center; align-items: center; font-family: 'Times New Roman', Times, serif;">
  <div style="flex: 1; font-size: 14px; color: #212f3c;">
    <h3 style="color: #1e3a8a; font-size: 24px; font-family: 'Times New Roman', Times, serif;">ECE 225A: Probability & Statistics for Data Science</h3>
    <p><strong style="color: black; font-size: 16px;">Instructor: Prof. Alon Orlitsky </strong></p>
    <div style="text-align: center;">
      <figure style="display: inline-block; text-align: center; position: relative;">
        <img src="/assets/images/ece225a.jpg" alt="ECE 225A Course Logo" style="width: 500px; height: auto;">
        <figcaption style="font-size: 12px; color: #555;">Slides from Prof Orlitsky's class</figcaption>
      </figure>
    </div>
    <p style="font-size: 14px; color: #212f3c; text-align: justify;">
      The course covered a wide range of concepts in Probability and Statistics. It not only introduced me to new ideas but also highlighted the power of probabilistic reasoning and theoretical understanding. There are many concepts that I wasn’t aware of before. To highlight a few:
      <ul>
        <li>The concept of <strong>Memorylessness</strong> in Geometric and Exponential distributions and its applications.</li>
        <li>The Right CDF approach to calculate expectations of a distribution.</li>
        <li>Normal distribution approximates the Binomial Distribution.</li>
        <li>WLLN (Weak Law of Large Numbers) is a great generalisation of the CLT.</li>
        <li>How weak bounds like <strong>Markov</strong> can be used to derive strong bounds like the <strong>Chernoff</strong> bounds.</li>
      </ul>
      <p style="font-size: 14px; color: #212f3c; text-align: justify;">
        What I liked the most about the course was that the concepts were coupled with real-world applications. For example, we discussed the question "why we should vote?" using probability, along with analogies that helped understand the concepts better, such as understanding the reciprocity of proximity using Newton's first law. What made the class even more special was Prof. Orlitsky using memes and cartoons to explain varied concepts in an engaging and interactive manner. Prof. Orlitsky really puts in a great effort in his slides and presentation.<br><br>
        Overall, it was a great course to pursue as a Data Science major. The concepts and mathematics really help when reading research papers in ML/DS.
      </p>
    </p>
    <p style="font-size: 14px; color: #ec407a;">Fall 2024</p>
  </div>
</div>

<div style="justify-content: center; align-items: center; font-family: 'Times New Roman', Times, serif;">
  <div style="flex: 1; font-size: 14px; color: #212f3c;">
    <h3 style="color: #1e3a8a; font-size: 24px; font-family: 'Times New Roman', Times, serif;">CSE291h: Advanced Data-driven Text Mining</h3>
    <p><strong style="color: black; font-size: 16px;">Instructor: Prof. Jingbo Shang </strong></p>
    <div style="text-align: center;">
      <figure style="display: inline-block; text-align: center; position: relative;">
        <img src="/assets/images/cse291h.jpg" alt="CSE 291h Course Logo" style="width: 500px; height: auto;">
        <figcaption style="font-size: 12px; color: #555;">Slides from Prof Shang's class</figcaption>
      </figure>
    </div>
    <p style="font-size: 14px; color: #212f3c; text-align: justify;">
      This course covered a wide range of NLP topics, starting with foundational concepts such as frequency-based word embeddings, and progressing to prediction-based embeddings (Word2Vec, GloVe), language models (including neural language models), and their respective advantages and limitations. The course also delved into Sentiment Analysis, Information Retrieval, and LLMs in fair detail, providing a solid foundation for understanding these advanced topics.<br><br>
      One of the highlights was learning about the professor’s own work in <strong>Phrase Mining</strong>, which enhances feature representation and improves textual understanding. This included an exploration of three methods for phrase mining: supervised, unsupervised, and weakly/distantly supervised learning, a new concept for me. As part of the assignments, I applied techniques such as SegPhrase (<strong>weakly supervised</strong>, using manually annotated labels) and AutoPhrase (<strong>distantly supervised</strong>, leveraging existing knowledge bases like Wikipedia) for mining phrases.<br><br>
      Additionally, the professor organized a graded Kaggle competition focused on multi-class text classification. This was a challenging and intensive experience, where I experimented with various embedding and modeling techniques to achieve a strong score. Overall, I found this course highly beneficial as a Data Science major. While it doesn’t focus directly on the latest hot topics like LLMs, it provides a robust understanding that is essential for working with these models in the future.
    </p>
    <p style="font-size: 14px; color: #ec407a;">Fall 2024</p>
  </div>
</div>

<div style="justify-content: center; align-items: center; font-family: 'Times New Roman', Times, serif;">
  <div style="flex: 1; font-size: 14px; color: #212f3c;">
    <h3 style="color: #1e3a8a; font-size: 24px; font-family: 'Times New Roman', Times, serif;">DSC260: Data Science Ethics & Society</h3>
    <p><strong style="color: black; font-size: 16px;">Instructor: Prof. David Danks </strong></p>
    <div style="text-align: center;">
      <figure style="display: inline-block; text-align: center; position: relative;">
        <img src="/assets/images/dsc260.jpg" alt="DSC260 Course Logo" style="width: 500px; height: auto;">
        <figcaption style="font-size: 12px; color: #555;">Danks prefers a board approach. Ethics is fundamentally about asking a normative set of questions :)</figcaption>
        </figure>
    </div>
    <p style="font-size: 14px; color: #212f3c; text-align: justify;">
      Prof. Danks' classes are incredibly interactive, and his charisma makes even the most complex concepts easy to understand. He simplifies difficult topics by using relatable analogies, which helped me grasp the material better.<br><br>
      The course covered a wide range of topics, including values, stakeholders, consent, algorithmic-justice, bias, privacy, and explainability. We also explored societal practices such as delegation, organizational incentives, and accountability, as well as governance mechanisms, including law, regulation, and norms.<br><br>
      These ethical concerns often go unchecked in data science projects. It is common for practitioners to simply source datasets from the web and use them directly in their work without fully understanding the potential ethical implications. This course has made me realize the importance of being aware of these issues when conducting data science and asking critical questions like:
      <ul>
        <li>In what ways should companies be allowed to use the data they collect?</li>
        <li>How do these ethical concerns manifest at different stages of a data science effort, such as data collection, modeling/analysis, deployment, and usage?</li>
        <li>What societal-level issues arise when AI systems are used on a large scale?</li>
        <li>Who should be responsible when an algorithmic subject is at the mercy of decisions made by AI systems?</li>
      </ul>
      While the concepts were not difficult, there were too many things to remember, however, the assignments and project work ensured thinking and applying the ideas discussed in class.
    </p>
    <p style="font-size: 14px; color: #ec407a;">Fall 2024</p>
  </div>
</div>

<div style="justify-content: center; align-items: center; font-family: 'Times New Roman', Times, serif;">
  <div style="flex: 1; font-size: 14px; color: #212f3c;">
    <h3 style="color: #1e3a8a; font-size: 24px; font-family: 'Times New Roman', Times, serif;">DSC291a: Interpretable & Explainable ML</h3>
    <p><strong style="color: black; font-size: 16px;">Instructor: Prof. Berk Ustun </strong></p>
    <div style="text-align: center;">
      <figure style="display: inline-block; text-align: center; position: relative;">
        <img src="/assets/images/dsc291a.jpeg" alt="DSC291a Course Logo" style="width: 500px; height: auto;">
        <figcaption style="font-size: 12px; color: #555;">Berk's class involved thorough reading and discussion on leading papers in IML and XML</figcaption>
      </figure>
    </div>
    <p style="font-size: 14px; color: #212f3c; text-align: justify;">
        
    </p>
    <p style="font-size: 14px; color: #ec407a;">Fall 2024</p>
  </div>
</div>
