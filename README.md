# VARIATION-OF-GPT-MODEL

# Assignment: Text Generation with GPT Model – Temperature Comparison

**GENERATED OUTPUTS:**

**Temperature 1.0**

Wine review: US: California: Zinfandel: soft and buttery, this tastes young and fruity in blackberry and cherry sauce, with thin, sweet flavors of pear and raisins. A nice mix of acidity.
(Temperature: 1.0)

**Temperature 0.5**

Wine review: Italy: Veneto: Glera: this opens with aromas of acacia, acacia, toasted nut, ripe yellow apple, and a whiff of honey. The creamy palate offers dried apricot, candied nectarine zest, lemon zest, and a hint of bitter almond alongside brisk acidity.

**Temperature 0.2**

Wine review: Italy: Tuscany: Sangiovese: this opens with aromas of red berry, underbrush, grilled herb, and a whiff of menthol. The straightforward palate offers dried black cherry, licorice, and a hint of clove alongside bracing tannins. Drink through 2017.


# Interpretation of Differences Between Outputs at Different Temperatures:

The temperature setting in a language model affects the randomness and diversity of the generated text. A higher temperature (closer to 1) results in more varied and creative output, while a lower temperature produces more conservative and deterministic text.

**Temperature 1.0:**

At this temperature, the model produces more creative and varied text. The Zinfandel review uses descriptions that are somewhat unexpected, like "buttery" and "thin, sweet flavors of pear and raisins," suggesting more unpredictable associations between words. The variety of descriptors here reflects the model's tendency to explore different possibilities for word choices, resulting in a broader, more expressive range.

**Temperature 0.5:**

When the temperature is set to 0.5, the output becomes more focused and consistent. In this case, the Glera review follows a logical structure, using familiar descriptors like "toasted nut" and "candied nectarine zest." The creativity is somewhat reduced, but the language is still interesting and flavorful. The balance of vivid language with clear coherence makes this output a reliable choice for controlled yet still dynamic text generation.

**Temperature 0.2:**

At the lowest temperature, the model produces the most predictable and consistent text. The Sangiovese review is straightforward and precise, with descriptors that are familiar and expected in the context of wine reviews, such as "red berry" and "dried black cherry." The output is more focused on producing reliable, conservative choices, minimizing creativity in favor of accuracy and consistency.

In conclusion, lowering the temperature reduces the randomness of the text, making the output more deterministic and predictable. The higher temperature outputs show more creativity but can sometimes be less coherent. Depending on the application, different temperatures can be chosen to balance creativity and control in text generation.

**REFERENCES**

Foster, D. (2022). Generative Deep Learning: Teaching Machines to Paint, Write, Compose, and Play (2nd ed.).
Retrieved from https://github.com/davidADSP/Generative_Deep_Learning_2nd_Edition/blob/main/notebooks/09_transformer/gpt/gpt.ipynb

Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., Kaiser, Ł., & Polosukhin, I. (2017). Attention is all you need. In Advances in Neural Information Processing Systems (Vol. 30). https://papers.nips.cc/paper/7181-attention-is-all-you-need

Brown, T. B., Mann, B., Ryder, N., Subbiah, M., Kaplan, J., Dhariwal, P., Neelakantan, A., Shyam, P., Sastry, G., Askell, A., Agarwal, S., Herbert-Voss, A., Krueger, G., Henighan, T., Child, R., Ramesh, A., Ziegler, D. M., Wu, J., ... & Amodei, D. (2020). Language models are few-shot learners. arXiv preprint arXiv:2005.14165. https://arxiv.org/abs/2005.14165







