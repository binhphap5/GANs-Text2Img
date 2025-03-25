# DCGANs-Text2Img

This project examine the power of Conditional GANs along with a Sentence BERT model to generate diverse and realistic flower images from textual descriptions. My goal is to create visually compelling images based solely on input text.

## Project Overview

We are exploring two distinct training strategies:
- **Traditional Loss Functions:** Leveraging conventional GAN loss metrics.
- **Contrastive Loss Functions:** Integrating contrastive loss to better align semantic features between text and image.

| Traditional GAN Loss                                                               | Contrastive GAN Loss                                                                        |
|------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| <img src="GANs.png" alt="Traditional GAN Loss" width="300" style="border:1px solid #ccc; border-radius:8px;" /> | <img src="GANs_contrastive.png" alt="Contrastive GAN Loss" width="300" style="border:1px solid #ccc; border-radius:8px;" /> |
| *Traditional GAN Loss*                                                             | *Contrastive GAN Loss*                                                                      |

