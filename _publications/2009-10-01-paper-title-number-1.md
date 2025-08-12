---
title: "Universally Composable Subversion-Resilient Authenticated Key Exchange"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-08-10
venue: 'ASIACRYPT 2025'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Jiahao Liu, Yi Wang, Rongmao Chen, Xinyi Huang, Jinshu Su, Moti Yung. (2025). &quot;Universally Composable Subversion-Resilient Authenticated Key Exchange.&quot; <i>ASIACRYPT 2025</i>.'
---

Subversion-resilient cryptography has garnered increasing attention in recent years due to growing concerns about cryptographic subversions in real-world applications. Among the existing countermeasures, the notion of cryptographic reverse firewalls (RFs), initially proposed by Mironov and Stephens-Davidowitz (EUROCRYPT 2015) and later extended by Chakraborty et al. (EUROCRYPT 2022) to the universally composable (UC) model, has proven to be a powerful tool for building subversion-resilient cryptographic protocols.
In this work, we focus on designing subversion-resilient authenticated key exchange (AKE) protocols, which are critical components of secure Internet communication. We present the first generic framework for subversion-resilient UC-secure AKE protocols leveraging RFs. Inspired by the state-of-the-art advancements by Chakraborty et al. (ASIACRYPT 2024), we address subversions: where a party’s implementation is covertly altered to exfiltrate secrets or behave unpredictably when triggered by adversarial inputs.
A key contribution of our work is the introduction of a new AKE functionality which, for the first time, incorporates security against key control, an essential aspect of achieving subversion resilience. We also provide a concrete instantiation of our framework, demonstrating its feasibility in practice. Notably, the RFs in our proposed AKE protocol are **transparent**, an important property of RF as defined originally, which allows
deployment of RF without all parties explicitly knowing about it and allows robust security. Achieving transparency for RFs has been widely regarded as challenging, particularly when addressing broader subversion attacks (e.g., input-trigger attacks) in the UC model. Our approach, thus, not only advances the state of AKE protocol design, but also offers insights into building other subversion-resilient protocols in the UC model using transparent RFs.
