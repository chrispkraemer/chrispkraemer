---
title: "User-directed Assembly Code Transformations Enabling Efficient Batteryless Arduino Applications"
collection: publications
category: manuscripts
permalink: /publication/batteryfreearduino
excerpt: 'Binary rewriting tool for to enable Battery-free Arduino devices'
date: 2024-10-01
venue: 'IMWUT'
slidesurl: 'https://chrispkraemer.github.io/files/batteryfreearduinoSlides.pdf'
paperurl: 'https://chrispkraemer.github.io/files/batteryfreearduino.pdf'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

Christopher Kraemer, Josiah Hester

The time for battery-free computing is now. Lithium mining depletes and pollutes local water supplies and dead batteries in
landfills leak toxic metals into the ground. Battery-free devices represent a probable future for sustainable ubiquitous
computing and we will need many more new devices and programmers to bring that future into reality. Yet, energy harvesting
and battery-free devices that frequently fail are challenging to program. The maker movement has organically developed a
considerable variety of platforms to prototype and program ubiquitous sensing and computing devices, but only a few have
been modified to be usable with energy harvesting and to hide those pesky power failures that are the norm from variable
energy availability (platforms like Microsoft’s Makecode and AdaFruit’s CircuitPython). Many platforms, especially Arduino
(the first and most famous maker platform), do not support energy harvesting devices and intermittent computing. To bridge
this gap and lay a strong foundation for potential new platforms for maker programming, we build a tool called BOOTHAMMER:
a lightweight assembly re-writer for ARM Thumb. BOOTHAMMER analyzes and rewrites the low-level assembly to insert careful
checkpoint and restore operations to enable programs to persist through power failures. The approach is easily insertable in
existing toolchains and is general-purpose enough to be resilient to future platforms and devices/chipsets. We close the loop
with the user by designing a small set of program annotations that any maker coder can use to provide extra information to
this low-level tool that will significantly increase checkpoint efficiency and resolution. These optional extensions represent a
way to include the user in decision-making about energy harvesting while ensuring the tool supports existing platforms. We
conduct an extensive evaluation using various program benchmarks with Arduino as our chosen evaluation platform. We
also demonstrate the usability of this approach by evaluating BOOTHAMMER with a user study and show that makers feel very
confident in their ability to write intermittent computing programs using this tool. With this new tool, we enable maker
hardware and software for sustainable, energy-harvesting-based computing for all.
