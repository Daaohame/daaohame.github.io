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


- Minimizing Packet Retransmission for Real-time Video Analytics<br />
  **Haodong Wang**, Kuntai Du, Junchen Jiang<br />
  *ACM Symposium on Cloud Computing (SoCC), 2022* [[paper]](https://alex-q-z.github.io/files/accmpeg_mlsys22.pdf)

- AccMPEG: Optimizing Video Encoding for Video Analytics<br />
  Kuntai Du, Qizheng Zhang, Anton Arapin, **Haodong Wang**, Zhengxu Xia, Junchen Jiang<br />
  *Conference on Machine Learning and Systems (MLSys), 2022* [[paper]](https://alex-q-z.github.io/files/accmpeg_mlsys22.pdf) [[code]](https://github.com/KuntaiDu/AccMPEG)
