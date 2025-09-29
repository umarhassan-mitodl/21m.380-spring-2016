---
content_type: page
description: 'In this section, Dr. Florian Hollerweger shares his insights about using
  the programming language Pure Data (Pd) as a teaching tool in 21M.380 Music and
  Technology: Sound Design. He also describes how he balances using technological
  tools with engaging students in key conceptual ideas, and using their ears, voices
  and minds.'
layout: instructor_insights
learning_resource_types: []
ocw_type: CourseSection
parent_title: Instructor Insights
parent_type: ThisCourseAtMITSection
parent_uid: b081e93a-ad70-36b9-ba45-f2818ea93148
title: Teaching with Technology (and Without)
uid: 7d747e12-0f5b-8bc5-aceb-7df72a18708a
---
_In this section, Dr. Florian Hollerweger shares his insights about using the programming language Pure Data (Pd) as a teaching tool in_ 21M.380 Music and Technology: Sound Design. _He also describes how he balances using technological tools with engaging students in key conceptual ideas, and using their ears, voices and minds_.

## Using Pure Data (Pd) to Synthesize Sounds

{{< quote "Your main tool for sound design is really your ears." "— Florian Hollerweger" >}}

In _21M.380 Music and Technology: Sound Design_, we use Miller Puckette's programming language, [Pure Data (Pd)](https://puredata.info/), to synthesize sounds. Pure Data is a wonderful teaching tool because it runs on many different computer platforms, is freely available, and is open source (and will continue to be so). This last point is critical. When I’m designing teaching materials, I always consider whether or not the tools I teach students will be available in the foreseeable future.

In class we focus on just the basic core of Pure Data, known as "Pd vanilla" (as opposed to “Pd-extended”, a version that includes additional libraries and extensions, and "Pd-L2Ork" which has recently superceded Pd-extended). This ensures that students understand the nuts and bolts of the sound design problems they are trying to solve, instead of relying on pre-fabricated solutions.

After the course, students can apply what they’ve learned to other computer music programming environments, such as SuperCollider or Pure Data's commercial relative Max/MSP.

## Sound Design Begins with the Ears

Teaching sound design involves more than teaching students how to use specific technological tools, such as Pure Data— it’s also about engaging students in thinking about conceptual ideas guiding the sound design process. To accomplish the latter objective, I deliberately include sound design problems that do not involve the use of software. For example, the {{% resource_link cf15ea27-ab5d-b27b-a2b2-eefe4e862776 "soundwalk assignment" "#SW" %}} asks students to describe, in as minute detail as possible, their aural experience from a listening excursion that we conduct across the MIT campus together. This assignment teaches them to verbalize their sonic impressions and communicate them to others. It trains students' ears to attend not only to individual sound sources, but also to flutter echoes, comb filters, and other subtle acoustics effects that are due to the abutting architecture.

This assignment encapsulates a message I constantly emphasize in the course: your main tool for sound design is really your ears. As Andy Farnell (2010) suggests in _Designing Sound_, using a tool like Pure Data comes only at the end of the sound design process, after you’ve analyzed the sound and built a model of it based on your understanding of the sound's key characteristics. This process inevitably starts with your ears.

This is why, in the {{% resource_link cf15ea27-ab5d-b27b-a2b2-eefe4e862776 "final project" "#FP" %}}, which is divided into four parts, only the last two parts require using Pure Data. The first two parts involve analyzing the sound, researching the sound creation mechanism, and coming up with a model that works independently of specific software environments.

Often the challenge students face during the design process is to understand what ultimately characterizes their sounds. Part of the analysis process may involve exploring sounds by visual means, such as spectrograms. Students often come to me and say, “I made a spectrogram of this sound, but I don’t see a thing.” It's an opportunity to help students reconnect with their ears as their primary tool. We start by identifying what they hear. For example, I had a student try to recreate the sound of a meowing cat. Using our ears, we attacked the problem, mostly through an analysis of the sequence of vowels that one typically uses when mimicking a cat's sound with one's voice. After looking up the characteristic formant frequencies of these vowels online, we applied them to a series of harmonically tuned bandpass filters. Soon afterwards, the cat was practically jumping right out of the loudspeaker. We got fantastic results without ever relying on visual aids such as  a spectrogram. It was a wonderful example of how using their ears as the primary tool can help students engage in the sound design process.

## The Voice as a Tool in Sound Design

When students get stuck in the analysis of a sound, I first encourage them to re-listen to their sound together with me, which usually leads to conversations about the essential characteristics of the sound. In this process, students are often hindered by language's natural inability to adequately describe aural experience. Rather than trying to describe the sound in words, we regularly resort to mimicking the actual sound itself with our own voices. Besides leading to hilarious office hour situations, I find that embodied sensations help students to better understand their sounds on an intuitive level. It’s a message I emphasize often: if you can produce a sound with your voice, chances are you have probably understood a great deal about it.

## Reference

![Buy at MIT Press](/images/mp_logo.gif) Farnell, Andy. _Designing Sound_. MIT Press, 2010. ISBN: 9780262014410. (Book and accompanying Pd example files.)