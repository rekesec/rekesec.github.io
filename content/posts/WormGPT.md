---
title: 'Exploring the Dark Side of Artificial Intelligence: WormGPT'
date: 2024-01-07T18:00:00+00:00
draft: False
tags: ['WormGPT', 'IA', 'ChatGPT', 'LastMalware', 'Last', 'sim-4932765', 'SecurityResearching', 'DarkWeb', 'DeepWeb', 'UndergroundForum']
---

# Executive Summary

In the vast realm of technology, Artificial Intelligence (AI) stands as a powerful force, revolutionizing industries and reshaping the way we interact with the digital world. With its ability to learn, adapt, and perform tasks autonomously, AI has become an integral part of our daily lives, from virtual personal assistants to recommendation algorithms that guide our online experiences. Yet, as we embrace the marvels of this cutting-edge technology, a darker underbelly emerges, where AI is not just a tool for progress but a weapon for malicious intent.

In the realm of AI chatbots, familiar faces like Siri, Google Assistant and Alexa have become household names, offering assistance and companionship. However, amidst the bright facade of helpful virtual assistants, there exists a shadowy counterpart – a breed of AI designed not to serve, but to exploit. 

During this blog post, we will delve into the unnerving world of dark AI, exploring the ominous applications that threaten to misuse the very technology designed to make our lives easier.


# WormGPT

WormGPT is a chatbot developed by LastMalware. It is based on the GPT-J language model from 2021, which is an open-source large language model capable of generating text similar to humans, similar to ChatGPT. Being open-source, unlike OpenAI, the laboratory behind ChatGPT, means that anyone can inspect, share, and even modify the source code. This, combined with the absence of anti-abuse restrictions that prevent ChatGPT from using profanity, writing hate speech, or viruses, means that WormGPT can fulfill any kind of malicious requests.

In its initial iteration, version 1 of the tool entered the market at a rate of 60€. However, with the unveiling of the enhanced version (v2), a strategic adjustment in pricing occurred, introducing two distinct plans: a monthly subscription at 100€ and an annual subscription priced at 550€.

  {{< figure link="/posts/images/WormGPT/WormGPTPrices.png" caption="WormGPT Initial Prices" >}}

This meticulous pricing strategy was formulated to seamlessly align with the user's objectives, granting them access to an array of features. These encompass unlimited character support, chat memory retention, and code formatting capabilities. The tool's remarkable proficiency in code composition and formatting stands out, providing users with the adeptness to engineer sophisticated malware attacks.

<br>

As evident from the imagery acquired by security researchers at slashnext, the tool exhibits the capability to generate emails without ethical or security constraints. This functionality aids attackers in executing BEC attacks with enhanced ease and speed.

{{< figure link="/posts/images/WormGPT/WormGPT-Created-BEC-Attack.png" caption="slashnext.com image." >}}

### Key Points

 - Owner: @LastMalware
 - Developers/helpers: @LastMalware, @Yellow, @Modz, @dash
 - Tool announcement date: 6th of March 2023.
 - Release date: 28th of June 2023.
 - Total officially released versions: 2
 - Project end date: 8th of August 2023

### LastMalware

LastMalware is a Portuguese individual who, as of October 22, 2022, was pursuing a degree in computer engineering. His personal GitHub account showcases his high-level programming skills, with proficiency in languages such as C++, Python, and JavaScript.

<br>

{{< figure link="/posts/images/WormGPT/LastMalwareGitHub.png" caption="Picture taken from waybackmachine. IMG date: 5 Oct 2022." >}}

<br>

**LastMalware**, also known as **sim-4932765** and **last**, became a member of an underground forum on January 23, 2021, with a primary focus on enhancing his knowledge of malware development through interactions with other forum members. Despite being labeled as a malware developer/seller, he attempted to obscure his nationality by claiming to be from Poland.

In his quest for involvement, **LastMalware** sought membership in various hacking groups like **Coined**, **Mafia Crew**, and **PinkLSZ Developers**. 

<br>

{{< gallery caption-effect="fade" >}}
  {{< figure thumb="-thumb" link="/posts/images/WormGPT/mafia.png" caption="Mafia group postulation">}}
  {{< figure thumb="-thumb" link="/posts/images/WormGPT/PinkLSZ.png" caption="PinkLSZ postulation" >}}
  {{< figure thumb="-thumb" link="/posts/images/WormGPT/Coined.png" caption="Coined postulation" >}}
{{< /gallery >}}

<br>

Notably, up until January 22, 2022, he maintained a low profile without contributing any content. However, on this date, he unveiled his maiden malware variant, DCRat.

<br>

{{< figure link="/posts/images/WormGPT/LastMalware-drat.png" caption="DCRat announcment post" >}}

<br>

Fast forward to March 6, 2023, LastMalware published a post introducing his latest project, named WormGPT. After nearly 3 months from the announcement date, he officially released the first version, marking a significant milestone in the evolution of his technical endeavors. 

<br>

  {{< figure link="/posts/images/WormGPT/WormGPTRelease.png" caption="WormGPT release post" >}}

<br>

The second version was released on September 15, 2023, as indicated by [@DailyDarkWeb](https://twitter.com/DailyDarkWeb/status/1702728987708104902?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1702728987708104902%7Ctwgr%5Eb2ed277770628a2c729eb497720ef512acc323f7%7Ctwcon%5Es1_&ref_url=https%3A%2F%2Fcybersecuritynews.com%2Fai-tool-wormgpt-v2%2F) in their X (old twitter) account.

{{< figure link="/posts/images/WormGPT/WormGPTV2.png" caption="WormGPT version 2 release." >}}

## The Conclusion of WormGPT: Fact or Fiction?

On August 8th, **LastMalware** announced their departure from the project they initiated a couple of months ago, citing concerns over the project's reputation.

{{< figure link="/posts/images/WormGPT/EndOfWormGPTProject.png" caption="WormGPT departure announcment." >}}

On their private official channel, on September 18th, 2023, WormGPT saw an update, followed by another release on December 27th, 2023. However, a puzzling question arises: who facilitated these updates when LastMalware had previously announced on an underground forum that they were leaving the project?

{{< gallery caption-effect="fade" >}}
  {{< figure link="/posts/images/WormGPT/WormGPTV3Release.png" caption="WormGPT Version 3 release post.">}}
  {{< figure link="/posts/images/WormGPT/WormGPTV4Release.png" caption="WormGPT Version 4 release post.">}}
{{< /gallery >}}


On July 15, 2023, **LastMalware** announced that one of his team members expressed interest in acquiring the project. 


{{< figure link="/posts/images/WormGPT/WormGPTTransferPlan.png" caption="WormGPT selling plan." camption-effect="fade">}}


### The question now arises: did he transfer the project to that teammate, or did he declare the end of the project and continue with it in the shadows?

---

### Metadata

| | |
|:-: | :-:| 
| Name | Fernando AKA LastMalware |
| Location | Portugal |
| Motivation | - Cybercrime <br> - Malware development <br> - Artificial Intelligence|