---
title: "Towards Efficient Kyber on FPGAs: A Processor for Vector of Polynomials"
collection: publications
permalink: /publication/2020-01-15-cinference
excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2020-01-15
venue: 'ASP-DAC 2020'
paperurl: 'http://cccisi.github.io/files/paper2.pdf'
citation: 'Zhaohui Chen, Yuan Ma, Tianyu Chen, Jingqiang Lin, Jiwu Jing." Towards Efficient Kyber on FPGAs: A Processor for Vector of Polynomials," to appear in the 25th Asia and South Pacific Design Automation Conference (ASP DAC) 2020.'
---

[Download paper here](http://cccisi.github.io/files/Kyber.pdf)

Kyber is a promising candidate in post-quantum cryptography standardization process. In this paper, we propose a targeted optimization strategy and implement a processor for Kyber on FPGAs. By merging the operations, we cut off 29.4% clock cycles for Kyber512 and 33.3% for Kyber1024 compared with the textbook implementations. We utilize Gentlemen-Sande (GS) butterfly to optimize the Number-Theoretic Transform (NTT) implementation. The bottleneck of memory access is broken taking advantage of a dual-column sequential scheme. We further propose a pipeline architecture for better performance. The optimizations help the processor achieve 31684 NTT operations per second using only 477 LUTs, 237 FFs and 1 DSP. Our strategy is at least 3x more efficient than the state-of-the-art module for NTT with a similar security level.


Recommended citation:
---
Zhaohui Chen, Yuan Ma, Tianyu Chen, Jingqiang Lin, Jiwu Jing." Towards Efficient Kyber on FPGAs: A Processor for Vector of Polynomials," to appear in the 25th Asia and South Pacific Design Automation Conference (ASP DAC) 2020.
