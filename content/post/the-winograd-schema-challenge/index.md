---
title: The Winograd Schema Challenge
date: 2023-06-20T07:25:23.576Z
draft: false
featured: false
authors:
  - Yi-Chun Ko
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
My thesis focuses on referential ambiguity. While searching for related literature, I stumbled upon the work of [Levesque et al. (2012)](https://cdn.aaai.org/ocs/4492/4492-21843-1-PB.pdf) discussing the Winograd Schema Challenge. This finding excited me because "testing whether a machine is thinking" is quite a sci-fi and "cyberpunk" notion and since then I have always wanted to discuss and share it in a post. 

Many of us are familiar with the Turing test or similar concepts used to evaluate artificial intelligence, often due to science fiction or films like the Blade Runner series. The central idea is that if a human evaluator cannot determine whether they are conversing with another person or a machine during an unrestricted conversation, we can consider the machine to have passed the test, exhibiting behavior equivalent to human thinking. This notion reminds me of a quote from the TV series "Westworld". When a main character first entered the immersive futuristic theme park populated with highly sophisticated androids known as “host” and encounter one of them at the first time, he asks, “Are you real?”. And the host responds, “If you can't tell, does it matter?”

(If you're into sci-fi like me, totally recommend checking out this TV series!) 

The Turing Test serves as a benchmark for evaluating artificial intelligence. However, Levesque et al. (2012) highlights some problematic and perhaps unnecessary aspects of the test. Specifically, a tricky aspect of the test lies in the fact that a machine can pass the test “if the human evaluator cannot reliably distinguish it from a human”. However, upon closer examination, one might realize that there are various ways for a machine to confuse participants about its identity without truly possessing the ability to "think." In other words, the requirements of the Turing Test lack precision, allowing systems to pass it without genuinely exhibiting intelligent behavior. 

To address this issue, the authors introduce the Winograd Schema Challenge, which has several favorable features. A Winograd schema comprises a pair of sentences that differ by only a word or two, containing an ambiguity that is resolved differently based on the specific words used in each sentence. This structure, while controlling for difficulty, aims to make pronoun resolution apparent to human readers, while also posing a challenge that cannot be easily solved using selectional restrictions or statistical approaches with large corpora. 

Several aspects of the study stood out to me as particularly intriguing. Firstly, the paper demonstrates how referential processing plays a crucial role in human language processing. The sentences are simple, and the reference resolution is so obvious that readers may not even notice the existence of ambiguity. We can reason and answer them immediately. Secondly, at first glance, I thought that it is the implicit causality possessed by verbs that alternates the answer. However, upon closer examination, it becomes clear that the sentences are more cleverly designed than I expected and resolving the references requires a deep understanding of the world knowledge. 

Furthermore, understanding how these "truly unambiguous" sentences were created provides valuable insights for me (and likely for those focused on referential ambiguity). It helps us reconsider our approach to constructing materials, as we were actually aiming for ambiguity. Knowing what reduces ambiguity proves helpful in identifying when ambiguity occurs and whether our materials truly exhibit ambiguity. 

Regarding Winograd Schema questions, there is much potential to explore these well-designed questions. For example, the position of the disambiguation is precisely controlled because the word position of the special (alternate) word is exactly where the temporally ambiguous pronoun is disambiguated. This characteristic can be utilized to study disambiguation mechanisms in referential processing. In my thesis, one of the findings indicated that the ERP ambiguity effect, known as the Nref effect, was observed even a few words after the ambiguity occurred if the underlying ambiguity status remained. This suggests that referential processing is flexible. It would be truly interesting to investigate whether strictly controlled disambiguating information, like the special word in Winograd Schema questions, could alter underlying referential processing and lead to observing a Nref effect in different positions. 

Lastly, an intriguing (though perhaps unrelated to academia) side note is that the original Turing Test suggested that conversations should be conducted in written form to avoid clues provided by "tones of voice" that could give away the machine. This limitation stemmed from the belief that machines may not convincingly imitate human voices at that time. However, we currently live in an era where we can no longer discern whether a photo or a video is real, thanks to generative AI technologies like Midjourney or Deepfake. It is only a matter of time, if not already happened, before a "thinking" machine can convincingly imitate natural speech and deceive evaluators, making it no longer a fantasy.