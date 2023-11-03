---
title: Introduction to Git
excerpt: Developer တိုင်း မဖြစ်မနေ သိသင့်တဲ့ Git ဆိုတာနဲ့ ပတ်သက်ပြီး အတွေ့အကြုံများဖြင့် အခြေခံထားတဲ့ လက်တွေ့ hand-on session ကို သေချာ အတူတူ လုပ်ကြရမည့် သင်ခန်းစာများ ဖြစ်ပါတယ်။
publisher:
  - Alex Snow School 
creator:
  - Lin Ye Htut Aung
date: 2020-06-29
modified: 2022-10-10
difficulty: Beginner
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
  - "DevOps-MLOps-and-Backend"
tags:
  - Python
  - Git
header:
  teaser: /assets/images/introduction-to-git.webp
  overlay_image: /assets/images/HeroImage.png
  overlay_filter: .2
  caption: 
anchor: true
annotate: true
---

Pre-perquisite: ဒီ course ကို Computer Science အခြေခံရှိပြီးမှ တက်သင့်ပါတယ်။
{: .notice--info}

{% include toc title="Contents" %}

An online webinar to understand git and its ability to scale Software Development based projects.

{% include video id="GoHPDcgNWBo" provider="youtube" %}

## Why do we need git?

### Working in teams

- It simplifies the process of working with other people and makes it easy to collaborate on projects.
- Team members can work on several files and easily merge their changes in with the master branch of the project. This allows multiple people to work on the same files at the same time.

### Centralized Storage of your code

- Your code is always available to you. (Different OS)
- You don’t have to worry about hard Drive failure and it is backed up.

### Version Control

- Every time you commit your code, Git remembers what has changed since the last time you saved your code. Even if you’ve changed a file a 1000 times, it will still remember each and every change. 

## Git OneFlow

- Maintaining a single long-lived branch simplifies the versioning scheme and day-to-day operations that developers have to perform considerably.
- It also makes the project history cleaner and more readable, and thus more useful.

|![Overview of Git OneFlow](/assets/images/overview-of-git-oneflow.png "Overview of Git OneFlow")|
|:--:|
| <b>Overview of Git OneFlow</b>|

### Advantages of fast-forward method

- Rebasing before integrating with master allows you to clean up the branch history before making it public, resulting in better final history landing on master.
- Linear history makes things simpler and easier to find, especially when looking at the per-file history.

### Disadvantages of fast-forward method

- Reverting the entire feature requires reverting multiple commits.

## Lab exercises and demo will be included

- Lab-1 Pre-requirisity and preparation
- Lab-2 Start a new development instance
- Lab-3 Check the status of the git directory
- Lab-4 Developing a new feature/bug fixes
- Lab-5 Get the latest code
- Lab-6 Update the new feature/bug to be compatible with the latest code base
- Lab-7 Deploy a new feature or bug fixes
- Lab-8 Stage for a release 
- Lab-9 Hotfix on a specific version
- Lab-10 Cherry Pick (If we have time)



## Assignments and Reading List

- [GitHub: Introduction to Git](https://github.com/alexsnowschool/demo-test-linked-data-dbpedia-SPARQL){:target='_blank'}
- [Git Conceptual Walkthrough](https://docs.google.com/document/d/1ETIhOH-YQi9_YWef9UAKPNOWK2hEMKDRoMRRRI1ZAj4/edit?usp=sharing){:target='_blank'}
