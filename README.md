# Build agents and extend copilot experiences with Copilot Studio

This repo contains the train the trainer material for the Build agents and extend copilot experiences with Copilot Studio breakout session for AI Tour.

![Workshop Title](/src/brktitle.png)

## Session Desciption

This is a 45-minute session focused on building and extending custom copilots and agents with Copilot Studio. This session gives an overview of Copilot Studio and where it fits into the copilot ecosystem and guides you through the basics of building a custom copilot to chat over your data, use Copilot Studio to extend Microsoft Copilot and change the way you interact with copilots with agents.

## Learning Outcomes
- Understanding of Copilot Studio and when to use it
- Know how to build a copilot connected to knowledge
- Extend a copilot with topics and actions
- Publish and monitor a copilot
- Extend Microsoft 365 Copilot with Copilot Studio
- Understanding of agents and how they work

## Technology Used
- Copilot Studio

## Additional Resources
You can find additional resources, including the slides for the presentation and train the trainer material [here](/train-the-trainer/README.md).

## Content Owners

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
<tr>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://github.com/aprildunnam.png" width="100px;" alt="April Dunnam
"/><br />
        <sub><b>April Dunnam
</b></sub></a><br />
            <a href="https://github.com/aprildunnam" title="talk">📢</a> 
    </td>
</tr>
<tr>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://github.com/laskewitz.png" width="100px;" alt="Daniel-Laskewitz
"/><br />
        <sub><b>Daniel Laskewitz
</b></sub></a><br />
            <a href="https://github.com/laskewitz" title="talk">📢</a> 
    </td>
</tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Responsible AI 

Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at [https://aka.ms/RAI](https://aka.ms/RAI).
Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. We also have an interactive Content Safety Studio that allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [generation quality and risk and safety metrics](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in).

You can evaluate your AI application in your development environment using the [prompt flow SDK](https://microsoft.github.io/promptflow/index.html). Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the prompt flow sdk to evaluate your system, you can follow the [quickstart guide](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk). Once you execute an evaluation run, you can [visualize the results in Azure AI Studio](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results).
