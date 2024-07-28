---
title: Machine Learning Paper Reading
excerpt: Machine Learning လေ့လာသူတွေအတွက် မဖြစ်မနေ သိထားသင့်တဲ့ research paper တွေကို အတတ်နိုင်ဆုံး ကြိုးစားရှင်ပြပေးထားတာကို စုထားပေးပါတယ်။
publisher:
  - Alex Snow School
creator:
  - Alex Snow
date: 2023-12-13
modified: 2024-06-28
difficulty: Intermediate
state: "ready"
license: PD
audience:
  - Computer Science Students
  - ML and AI Enthusiasts
  - IT Professionals
interactivity: Expository
resource_type: Publication
based_url: 
topic:
  - "Machine-Learning-and-AI"
tags:
  - Machine Learning & AI
  - Python
header:
  teaser: /assets/images/intro-to-ml-square.png
  overlay_image: /assets/images/HeroImage.png
  overlay_filter: .2
  caption: 
anchor: true
annotate: true
---

Pre-perquisite: ဒီ course ကို Computer Science အခြေခံရှိပြီးမှ တက်သင့်ပါတယ်။
{: .notice--info}

{% include toc title="Contents" %}

## Machine Learning Paper Reading

### 🥬 Metric Learning

#### FaceNet: A Unified Embedding for Face Recognition and Clustering

Face Recognition ကို စိတ်ဝင်စားသူတိုင်လေ့လာ သင့်တဲ့ paper လေဖြစ်လို့ အားလုံးအတွက် အကျိုးရှိအောင် ရှယ်ပေးလိုက်ပါတယ်။ 

{% include video id="w05oosmFsxM" provider="youtube" %}
- [Original Paper](https://arxiv.org/abs/1503.03832){:target='_blank'}
- [Explaination PDF](https://drive.google.com/file/d/1TwXJgNqA-nfcGyrZ_OlpBIshMgiJu82z/view?usp=sharing){:target='_blank'}
- [Implementation](https://github.com/alexsnow348/facetag){:target='_blank'}


### 🌼 Self-Supervised Learning

#### 1. SimCLR: A Simple Framework for Contrastive Learning of Visual Representations

SimCLR က Self-Supervised Learning ကို လေ့လာတဲ့အခါ မသိမဖြစ်သိထားသင့်တဲ့ paper လေဖြစ်ပါတယ်။ 

{% include video id="l8E_r9MkrCA" provider="youtube" %}

- [The Illustrated SimCLR Framework](https://amitness.com/posts/simclr){:target='_blank'}
- [NT-Xent Loss](https://towardsdatascience.com/nt-xent-normalized-temperature-scaled-cross-entropy-loss-explained-and-implemented-in-pytorch-cc081f69848){:target='_blank'}
- [Google Slides](https://docs.google.com/presentation/d/1ccddJFD_j3p3h0TCqSV9ajSi2y1yOfh0-lJoK29ircs/edit#slide=id.g8c1b8d6efd_0_1){:target='_blank'}


#### 2. BYOL: Bootstrap Your Own Latent

BYOL က SimCLR က မှာ collapse (trivial constant solution) ပြဿနာကို ဖြေရှင်ဖို့ လိုအပ်တဲ့ negative pairs  ကို avoids လုပ်ဖို့ အဓိက ထားပြီး design လုပ်ထားတာဖြစ်ပါတယ်။

{% include video id="1BJmQxHuRgs" provider="youtube" %}

- [Original Paper](https://arxiv.org/pdf/2006.07733){:target='_blank'}
- [Towards Data Science Explanation](https://towardsdatascience.com/byol-the-alternative-to-contrastive-self-supervised-learning-5d0a26983d7c
){:target='_blank'}


#### 3. SimSiam: Exploring Simple Siamese Representation Learning

SimSiam Method က SimCLR, BYOL တိုမှာ ပါတဲ့ complicated methods တွေကို အလွယ်ကူဆုံး  simple siamese network ဖြင့် အစားထို ဖြေရှင်ထားတဲ့ နည်းလမ်းတစ်ခုပဲဖြစ်ပါတယ်။

{% include video id="mBrzoPHl-BI" provider="youtube" %}

- [Explanation Slide](https://drive.google.com/file/d/1GMkDr77fA0H4EvUnRAGjucJMEFxWVQ7o/view?usp=sharing){:target='_blank'}
- [Original Paper](https://arxiv.org/abs/2011.10566){:target='_blank'}
- [Towards Data Science Explanation](https://sh-tsang.medium.com/review-simsiam-exploring-simple-siamese-representation-learning-3c84ceb61702){:target='_blank'}


### 👩🏻‍🎓 Knowledge Distillation

#### 1. Knowledge Distillation: A Survey

Knowledge Distillation ဆိုင်ရာ သိသင့် သိထိုက်သော အခြေခံ concept တွေကို နာလည်းဖို့ အတွက် ဖတ်သင့်တဲ့ paper လေ တစ်ခုပဲ ဖြစ်ပါတယ်။

{% include video id="0LtoRcXcudc" provider="youtube" %}

- [Explanation Slide](https://drive.google.com/file/d/1qoMhFWrcDK3jjOuWnv2863XeJwIs1bJ5/view?usp=drive_link){:target='_blank'}
- [Original Paper](https://arxiv.org/abs/2006.05525){:target='_blank'}
