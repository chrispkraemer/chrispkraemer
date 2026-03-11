---
title: "FPVM: Towards a Floating Point Virtual Machine"
collection: publications
category: conferences
permalink: /publication/fpvm_paper
excerpt: 'Trap and emulate approach to abitrary precision floating point'
date: 2022-06-27
venue: 'HPDC'
#slidesurl: 'https://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://chrispkraemer.github.io/chrispkraemer/files/fpvm.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Peter Dinda, Nick Wanninger, Jiacheng Ma, Alex Bernat, Charles Bernat, Souradip Ghosh, Christopher Kraemer, Yehya Elmasry

Alternatives to IEEE floating point arithmetic have become all the
rage. Some extract more representational power out of the avail-
able bits. Others offer the potential for lower or higher precision
than is available in IEEE-compatible hardware. Even an “interface
to the real numbers” has recently been proposed. Using such al-
ternative arithmetic systems within an existing scientific or other
significant codebase is a major challenge, however. We explore
how to address this challenge through virtualizing the IEEE float-
ing point hardware, specifically on x64. The goal of the floating
point virtual machine (FPVM) is to allow an existing application
binary to be seamlessly extended to support the desired alternative
arithmetic system with overheads determined by that system and
not the virtualization mechanisms. We describe the prospects, is-
sues, and tradeoffs for four different approaches for building FPVM:
trap-and-emulate, trap-and-patch, binary transformation, and IR
transformation. We then describe the design and implementation
of our current design, which combines static binary analysis/trans-
lation and trap-and-emulate execution. We evaluate our FPVM
implementation on several benchmarks, virtualizing them to use
posits and MPFR. Finally, we comment on kernel- and hardware-
level innovations that could further reduce overheads for floating
point virtualization.
