---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**Fields:** Natural Language Processing, Deep Learning

**Topics**: Natural Language Understanding, Spelling Correction, Legal Text Processing, Medical Text Processing

**Listing of my papers**: [Google Scholar](https://scholar.google.com/citations?user=wspA9boAAAAJ&hl=vi)

**Publications**:

1. Manh Hung Nguyen, Vu Hoang, **Tu Anh Nguyen**, and Trung H. Bui. Automatic Radiology Report Editing Through Voice. InProc. Interspeech 2021, pages 4862–4863, 2021 [paper](https://www.isca-speech.org/archive/interspeech_2021/nguyen21f_interspeech.html)

2. Ta Duc Huy, **Nguyen Anh Tu**, Tran Hoang Vu, Nguyen Phuc Minh, Nguyen Phan, Trung H. Bui, and Steven Q. H. Truong. ViMQ: A Vietnamese Medical Question Dataset for Healthcare Dialogue System Development. In Proceedings of the 28th International Conference on Neural Information Processing (ICONIP), 2021. [paper](https://link.springer.com/chapter/10.1007/978-3-030-92310-5_76) 

3. **Nguyen Anh Tu**, Hoang Thi Thu Uyen, Tu Minh Phuong, Ngo Xuan Bach. Analyzing Vietnamese Legal Questions using Deep Neural Networks with Biaffine Classifiers. In Proceedings of the 28th International Conference on Neural Information Processing (ICONIP), 2021. [paper](https://link.springer.com/chapter/10.1007/978-3-030-92270-2_44)  
4. Oanh Thi Tran, Thang Van Nguyen, **Tu Anh Nguyen**, Ngo Xuan Bach. Learning Student Intents and Named Entities in the Education Domain. International Journal on Artificial Intelligence Tools.[paper](https://doi.org/10.1142/S0218213023500021). (SCIE, Q3, IF 1.208) 
5. Hoang Thi Thu Uyen, **Nguyen Anh Tu**, Ta Duc Huy. Vietnamese Capitalization and Punctuation Recovery Models. Interspeech 2022 [paper](https://arxiv.org/abs/2207.01312)
6. **Nguyen Anh Tu**, Duong Xuan Hieu, Tu Minh Phuong, Ngo Xuan Bach. A Bidirectional Joint Model for Spoken Language Understanding. Proceedings of the 48th IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP), Greece, June 2023
