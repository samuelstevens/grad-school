---
documentclass: article
geometry:
  - margin=1.5in
---

<!--
pandoc umass-amherst.md -o umass-amherst.pdf
-->

# Instructions

Your Personal Statement should be a brief but carefully written essay and should include: 1) the reasons you want to do graduate work in this particular field, 2) your specific interests and experiences in this field, 3) any special skills or experiences that may relate to an assistantship, and 4) your career plans.

# Essay

1. The reasons you want to do graduate work in this particular field
2. Your specific interests and experiences in this field
3. Any special skills or experiences that may relate to an assistantship
4. Your career plans.

I'm fascinated by artificial intelligence. More specifically, my area of interest is natural language understanding. Not only is it difficult to teach a system to understand natural language (like an essay on economics), it's difficult to prove that the system understands the material (how do you ask a machine to explain supply and demand?). To me, natural language understanding is a very fundamental area of artificial intelligence, because it needs a clear definition of understanding and intelligence to measure success. This intertwining of "teach a computer to read" with "what is the definition of intelligence" is what makes natural language understanding so interesting to me.

My undergraduate research thesis focuses on natural language understanding. I am creating a distantly-supervised dataset of sentences from academic writing using papers published on the arXiv[^arxiv]. With this dataset, I am fine-tuning transformer models to predict whether a given sentence needs editing or not. Finally, I'm benchmarking my model against top models from the Automatic Evaluation of Scientific Writing (AESW) task, which was also to predict whether a sentence in an academic context needs editing or not. The initial training set for the AESW provided 1.1M hand-edited sentences; the arXiv has around 150M sentences. Although these sentences are not hand-labeled, my thesis is about investigating whether that the size will make up for any potential noise in the data.

[^arxiv]: https://arxiv.org

Users of the arXiv typically upload PDFs and LaTeX source documents as `.tar.gz` files for each version of a paper. One specific challenge that I encountered was finding the best way to extract text from LaTeX source documents. The difficulty arises from LaTeX's Turing-completeness; there are arbitrarily complex expressions that eventually resolve to formatted text. To solve this, I manually inspected the output of three different "de-LaTeXing" (detexing) tools, line by line, keeping track every error. With these errors, I created an extensive test suite to ensure that my detexing tool was the best it could be. This software engineering skill and attention to fine detail led to a high-quality dataset that I am using to train my model.

In part, my thesis is a joy to work on because I think that natural language understanding is important and that I can meaningfully contribute to the field. But beyond that, I enjoy the rigor and difficulty of research. I'm forced to support my assumptions with analysis, and explain myself clearly and concisely. I've learned how to read academic papers and find the information relevant to my work. The independence and lack of safety net in research compared to my classes is scary, but thrilling. My work matters, and I'm responsible for making sure it's trustworthy and useful to others.

To me, a graduate degree is about improving both the breadth and the depth of my knowledge. For instance, I have known unknowns (I'm not entirely sure why transformer models are so effective) and unknown unknowns (I just learned that distributed algorithms exist). I feel confident that I can make my known unknowns into just knowns: I can find an online course, a textbook, or an open source project to learn from. But what unknown unknowns are out there that I've never heard about? In this sense, a graduate degree is about increasing my breadth of knowledge, so that when I have a new problem, I can find the best tool for the job.

_Start editing here_

In addition to increasing my breadth of knowledge, a graduate degree is an opportunity for me to become an expert in a topic and further develop my technical understanding of natural language research. I think that natural language is improperly utilized in business; often, chatbots are just a series of multiple-choice questions that follow a predetermined path. At that point, it would be better for the customer to just be able to click on the answers rather than type them out. I think that recent advances in pretrained models will give business an opportunity to develop genuinely useful dialogue systems that save both the customer and business time and money. I want to use my graduate degree to develop a competitive advantage in commercial natural language systems and capitalize on my expertise in a particular niche.
