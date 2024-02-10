---
layout: single
title: "About our Courses"
# excerpt: "ကျောင်းမှာ လက်ရှိ ပိုချနေတဲ့ သင်ခန်စားများနဲ့ ပတ်သက်ပြီး အောင်ပါဖော်ပြချက်ကို လေ့လာနိုင်ပါတယ်။"
permalink: /courses/about/
header:
  teaser: /assets/images/HeroImage.png
  overlay_image: /assets/images/HeroImage.png
  overlay_filter: .3
  caption:
---

Alex Snow School တွင် ရှိသော် course အားလုံးသည် အောက် ဖော်ပြပါ information များ ပါဝင်ပါတယ်။
## Courses information

Course တိုင်းမှာ ဖန်းတီးထားသူတွေရဲ့ details တွေကို ထည့်တွင်းထားပါတယ်။

- Publisher(s)
- Creator(s)
- License
- Publication date (earliest)
- Modification date (most recent)
- Course state
- Course repository (if available)
- Based on URL (if available)

### Courses state

Course တိုင် ရဲ့ လက်ရှိ development အခြေအနေတွေကိုလဲ အောက်က ဖော်ပြထားတဲ့ status တစ်ခု မဟုတ် တစ်ခု နှင့်  ဖော်ပြထားရှိပါတယ်။

- ![state: brainstorming](https://img.shields.io/badge/status-brainstorming-lightgrey.svg)
- ![state: needs work](https://img.shields.io/badge/status-needs%20work-red.svg)
- ![state: building/designing](https://img.shields.io/badge/status-building%2fdesigning-orange.svg)
- ![state: experimental](https://img.shields.io/badge/status-experimental-yellow.svg)
- ![state: ready](https://img.shields.io/badge/status-ready-brightgreen.svg)  

## Educational information

ကျောင်းတွင် မိမိတို့ စိတ်ဝင်စားရာ နည်ပယ်များကို အလွယ်တကူ လေ့လာနိုင်ရန် သက်ဆိုင် ဘာသာရပ်အလိုက် စုစည်ပေးထားပါတယ်။

- Topics
- Difficulty
- Audience
- Educational Use

### Difficulty

Course တိုင်တွင် ဘာသာရပ်ဆိုင်ရာ ခက်ခဲ့နိုင်မှုကို ခန့်မှန်ချက်များ ပေးထားပါတယ်။

- Beginner
- Intermediate
- Advanced

### Topics

ကျောင်းတွင် အောက်ဖော်ပြပါ ခေါင်စဉ်များမှ မိမိတို့ စိတ်ဝင်စားရာ နည်ပယ်ကို ရွေးချယ်လေ့လာနိုင်ပါတယ်။  

{% for topic in site.data.topics %}
- **{{ topic.name }}:** {{ topic.description }}
{% endfor %}

### Audience

ကျောင်းသည် အောက်ဖော်ပြပါ လေ့လောသူများကို ဦတည်ထားပါတယ်။

{% for audience in site.data.audiences %}
- **{{ audience.name }}:** {{ audience.description }}
{% endfor %}


### Educational Use

ကျောင်းမှာ ရှိတဲ့ course contents မှာ အားလုံးသည် အောက်ဖော်ပြပါ အခြေအနေဖြင့် ကိုက်ညီမှုရှိသော နေရာမျိုးတိုတွင် ပြန်လည် အသုံးချမှုကို ခွင့်ပြုပေးထားပါတယ်။

- Self-guided learning
- Board and volunteer trainings
- Government and nonprofit staff trainings
- Community workshops
- High school and undergraduate college courses
