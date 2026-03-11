---
title: "Battery-free MakeCode"
collection: publications
category: manuscripts
permalink: /publication/batteryfreemakecode
excerpt: 'Compiler extensions to enable battery-free computing for MakeCode.'
date: 2024-10-01
venue: 'IMWUT'
#slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://chrispkraemer.github.io/chrispkraemer/files/batteryfreemakecode.pdf'
#citation: 'Kraemer, Christopher. (2022). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

Christopher Kraemer, Amy Guo, Saad Ahmed, Josiah Hester

Hands-on computing has emerged as an exciting and accessible way to learn about computing and engineering in the physical
world for students and makers of all ages. Current end-to-end approaches like Microsoft MakeCode require tethered or
battery-powered devices like a micro:bit, limiting usefulness and applicability, as well as abdicating responsibility for teaching
sustainable practices. Unfortunately, energy harvesting computing devices are usually only programmable by experts and
require significant supporting toolchains and knowledge across multiple engineering and computing disciplines to work
effectively. This paper bridges the gap between sustainable computing efforts, the maker movement, and novice-focused
programming environments with MakeCode-Iceberg, a set of compiler extensions to Microsoft’s open-source MakeCode
project. The extensions automatically and invisibly transform user code in any language supported (Blocks, JavaScript,
Python)into a version that can safely and correctly execute across intermittent power failures caused by unreliable energy
harvesting. Determining where, when, and what to save in a checkpoint on limited energy, time, and hardware budget is
challenging. We leverage the unique intermediate representation of the MakeCode source-to-source compiler to design
and deploy various checkpointing techniques. Our approach allows us to provide, for the first time, a fully web-based and
toolchain-free environment to program intermittent computing devices, making battery-free operation accessible to all.
We demonstrate new use cases with multiple energy harvesters, peripherals, and application domains: including a Smart
Terrarium, Step Counter, and Combination Lock. MakeCode-Iceberg provides sustainable hands-on computing opportunities
to a broad audience of makers and learners, democratizing access to energy harvesting and battery-free embedded systems.
