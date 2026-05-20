---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* B.S. in Computer Science and Technology, School of Artificial Intelligence, Beijing Normal University, 2023-2027
  * GPA: 3.8 / 4.0
  * Class Rank: 1 / 54
* B.S. in Mathematics and Applied Mathematics, School of Mathematical Sciences, Beijing Normal University, 2024-2027

## Research Experience

* **CLASS: Collaborative Lesson Plan Generation Agents With Skill-Structure Co-Evolution**
  * Feb 2026 - Present
  * Responsibilities: Proposed CLASS, a multi-agent collaborative evolution framework for personalized lesson plan generation, employing a "Generate-Evaluate-Evolve" closed-loop. Designed a two-stage search strategy combining tree-based local exploration for task decomposition and skill acquisition with graph-based global optimization for flexible coordination and escaping local optima. Introduced a student modeling method based on a capability tree and constructed a unified objective function balancing instructional plan quality, alignment with learner profiles, and computational cost. Achieved an average 25.1% improvement over the Single Agent baseline across four benchmark datasets under an LLM-based simulated student evaluation framework, achieving favorable performance-cost trade-off.

* **LLM-based Suicide Risk Identification and Interpretability Research for College Students**
  * Beijing Natural Science Foundation Undergraduate "Qiyan" Program, Participant
  * Jul 2025 - Present
  * Responsibilities: Fine-tuned large language models for multi-platform text-based suicide risk classification. Designed a Chain-of-Thought-based interpretability generation framework guiding the model to output structured psychological reasoning processes (emotion recognition, cognitive analysis, suicidal ideation judgment, etc.). Integrated psychological theories to construct an interpretability annotation paradigm, improving model decision transparency.

* **Intelligent Campus Security and Behavior Recording System Based on Multi-person Motion Capture**
  * Beijing Undergraduate Research Training Program, Principal Investigator
  * Jun 2024 - May 2025
  * Responsibilities: Designed a real-time warning system based on video streams, implementing video-to-3D human model conversion through improved AiOS into SMPL-X parameters, extracting human key points, generating bone heatmaps, and using MMAction2 for bone-to-action classification. Achieved a 20% improvement in recognition accuracy on a self-built campus dataset compared to MMAction2's direct video-to-action classification.

## Publications

<ul>{% for post in site.publications reversed %}
  {% if post.category == 'underreview' %}
    {% continue %}
  {% endif %}
    {% include archive-single-cv.html %}
{% endfor %}</ul>

