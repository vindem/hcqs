---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
# About

Welcome to the home page of the first workshop on Hybrid Classical Quantum Systems! The workshop is co-located with [EuroPar 2024](https://2024.euro-par.org/).

The advent of the Post-Moore era is driving the HPC research community towards alternative forms of computing, also known as Post-Moore computing. Quantum computing is particularly appealing for HPC, due to its proven theoretical speedup for suitable problems. Since not all the computational tasks will benefit from execution on quantum hardware, quantum systems have to be integrated with HPC infrastructures to exploit the full potential of quantum hardware. However, integration of quantum hardware into HPC infrastructure is a cumbersome task, due to the different programming models used in quantum with respect to HPC applications, the high heterogeneity of quantum hardware (i.e., superconducting qubits, ion-traps, photonics, neutral atoms), the necessity of pre-processing classical data (i.e., encoding into a quantum state) and post-processing quantum computation results (i.e., error mitigation). All these open research challenges contributed to the development of a new research area that lies at the intersection of HPC and quantum information and computation, called Hybrid Classical Quantum Systems (HCQS).

## Scope

The goal of HCQS is to bring quantum computing to the HPC research community, helping scientists working in this field to find common ground in this interdisciplinary field. In this workshop, we want to attract submissions from computer scientists, mathematicians and physicists, working on the integration of quantum into HPC infrastructures. Works on benchmarking hybrid classical quantum systems, hybrid classical quantum applications, and integration of classical HPC and quantum hardware are especially welcome.


<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.date }} - {{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
