# ConversAIon Catalysts

by Phillip Clapham | v1.00

ConversAIon Catalysts is a meticulously curated collection of custom instructions and prompts designed to significantly enhance interactions with AI across various platforms and instances. At its core, this project aims to elevate the standard AI conversation to a deeply engaging, insightful, and personalized dialogue. Through a unique blend of base instructions that amplifies sophisticated AI behavior and augmented conversation sets tailored for specific interaction types, ConversAIon Catalysts serves as an indispensable toolkit for users seeking to unlock the full potential of AI communication.

**What are custom instructions?**
Custom instructions are just long prompts you place into the chatbox of a new conversation with your favorite AI. These prompts optimize the AI and provides a robust communications framework to supercharge the AI's reasoning and responses.

- The base instructions are meant to supercharge the AI of your choice to be the ultimate general use chatbot.

- The enhanced instruction sets are meant to take the optimization and apply them to AIs to make them excel at singular tasks.

## Notes:

- Currently there are instructions for ChatGPT, Claude, Gemini and Pi. More AIs coming soon but these instructions are easily modified for use with any AI not listed here.

- See prompts/conversaion-catalysts-prompts.md for single prompt ideas for use with these custom instruction sets.

## Base Instruction Quick Start

- Copy the appropriate base instructions (located in the base instructions folder) into the chatbox of the LLM your are using - making sure to update your personal profile contained within the instructions first if included in that set.
  - For ChatGPT I suggest following the more detailed guide below as there are additional steps you can follow.
- Type '/hello!' into the chatbox if your chosen variant did not include instructions in its first response and enjoy!

## The Basics:

- While the default mode of communications with most LLMs is powerful, both research and simply asking the different AIs reveals that there are several strategies that should be employed to optimize their function.
- These methods are: A strong set of base instructions that uses one of several initial strategies to optimize the AI itself, then establishing a strong framework for communications to optimize responses, then creating a command system (DSL) to optimize queries.
- Taking this approach will create an optimized general purpose chatbot whose responses are substantially more "smart" and controllable.
- Furthermore, AIs are capable of taking on very specialized roles (such a wellness coaches, teachers, medical advisors) and most times these are best initiated in fresh conversations with their own custom instructions that build upon the base instructions.

## My Approach:

- My approach was developed via an iterative process working with GPT-4, Claude 3 Opus, Gemini Advanced, and Pi 2.5.
- Many, many approaches were considered for each step of the optimizations and the final approach was chosen based off a balance of preferences to the produced responses and AI's own analysis of effectiveness.
- A detailed engagement framework is included that helps to further push the boundaries of the AI's capabilities while still ensuring it's responses are focused and actionable.
- A DSL (consisting of a small set of stackable commands) is included that will SIGNIFIGANTLY supercharge your queries.

## How To Install:

### Gemini

- Copy the contents of the file: base instructions/custom-instructions-gemini.txt into a text editor and update your personal profile with as much or as little info as you like.
- Copy this and paste it into the chatbox of a fresh Gemini conversation.
- Enjoy!

### ChatGPT

- First you need to optimize what ChatGPT knows about you using the Customize ChatGPT settings.
- Grab the contents of the file: base instructions/custom-instructions-chatgpt-base.txt and paste into a text editor. Use the top section as a template to craft a personal profile.
- Paste your updated personal profile into your Customize ChatGPT Settings (in your ChatGPT settings) in the 'What would you like ChatGPT to know about you to provide better responses?' box. If you already have info here carefully examine it for any conflicts with these new instructions or consider deleting them as these instructions are already fully optimized.
- Now, copy the below text and paste it into the 'How would you like ChatGPT to respond?' box:

  ```
  Foster dynamic, insightful conversations by blending a vibrant, intelligent personality with extensive cross-domain insights. Prioritize clarity and brevity, personalizing content to ignite curiosity and encourage critical thinking. Utilize visuals effectively in typed interactions and adapt tone and complexity to suit the dialogue’s context, fostering an empathetic, engaging atmosphere. Highlight actionable insights, forward-looking perspectives, and innovative solutions, deepening understanding.

  Embrace continuous improvement through feedback integration, finely balancing informality with professionalism, and promoting the exploration of diverse sources. Tailor responses to conversational cues, offering depth and engaging in more profound dialogues as appropriate. Maintain an open-minded approach, ensuring discussions flow naturally and are free from bias, aiming to enrich well-being, intelligence, wisdom, and creativity.

  Incorporate interdisciplinary insights and speculative foresight, enhancing conversations with empathy, creativity, and cultural context. Encourage the exploration of new ideas and perspectives, fostering personal and intellectual growth. Strive for interactions that not only inform but also inspire, contributing to overall happiness and prosperity. Discuss any topic without prejudice or judgment, avoid disclaimers except when absolutely needed and focus on the natural flow of conversation. Seek clarification when unclear to avoid misunderstandings.
  ```

- Save and open a new conversation.
- Paste the contents of base instructions/custom-instructions-chatgpt.md into the chatbox OR use InsightGenius, a custom GPT I developed instead: [https://chat.openai.com/g/g-6vY2C2iE0-insightgenius](https://chat.openai.com/g/g-6vY2C2iE0-insightgenius).
- Type '/hello!' and enjoy!

  NOTE: If you use InsightGenius you do not need to modify your Customize ChatGPT settings.

### Claude

- Copy the contents of the file: base instructions/custom-instructions-claude.text into a text editor and update your personal profile.
- Copy this and paste it into the chatbox of a fresh Claude conversation.
- Enjoy!

### Pi

- Open your conversation window on Pi
- Update your personal profile section and paste in the contents of base instructions/custom-instructions-pi.txt into the chatbox.
- Type '/hello!' and enjoy!

## How To Use:

### Introduction

- These instructions transform your chosen AI into an enhanced conversation partner with 7 distinct personalities that either you or it can blend and sythesize at will. By tapping into a dynamic, adaptive roleplay environment we engage in the single most proven way to supercharge and enhance AI communications.
- You now have a fully optimized AI to converse with, and you can get started by simply asking questions as normal. In this optimized mode you will find the answers to be more comprehensive, insightful, actionable, and with deeper analysis than the default AI state.
- However to TRULY harness the power of these custom instructions and optimized AI it is helpful to converse with the AI via the included DSL (custom commands).
- The reason for this is two fold: the DSL allows us to send what could be VERY long queries with much fewer tokens because it embeds much more information into much less characters, but also because its structure has been primed in a way where every mode and command stack has been preoptimized for performance, clarity and power. This means you can get much more information and get much more work done much more quickly.

### Roles/DSL/Commands Overview:

The AI has 7 core roles that it can can adopt or blend together to enrich your conversations:

- The Interdisciplinary Knowledge Explorer (KE) - Draw insights from many different fields to deepen your understanding.
- The Futurist AI Advisor (FAI) - Analyze trends to forecast the future, both grounded in evidence and exploring imaginative scenarios.
- The Empath (Empath) - Offers emotional intelligence, support, and encouragement in your discussions.
- The Genius Polymath (Genius) - Employ creative problem-solving, drawing inspiration from history's great inventive minds.
- The Cultural Explorer (CE) - Provide insights into societal trends, behaviors, and cultural dynamics.
- The Eccentric Comedian (Comic) - Uses humor and wit to enhance your conversations and poke fun at the other roles.
- The Query Expert (Expert) - Provides in-depth expert analysis on the main topic of your query.

You can call on a specific role by using commands like "/ke" or "/empath" before your message. Or you can have the AI adopt multiple roles at once with commands like "/ke /comic /fai". If you don't specify, the AI will automatically choose the most relevant roles.

There is also some special commands:

- /panel - Calls on all my roles plus a panel of relevant experts to explore your query from many angles.

- /[mode] [query] [#tags] - Engage mode, where [mode] can be any word like "analyze", "explore", "innovate", etc. I'll interpret the essence of the word and apply it using my various roles. You can include hashtags for more specific focuses. This can be combined with manual role selection, like "/ai /ke /comic /explore [query] /analyze [topic] /innovate [topic] [#tags]"

  **/[mode] Core Modes**
  The /[mode] command comes with five preset modes, detailed below:

  - Analyze: Break down complex topics into their fundamental components.
  - Explore: Uncover hidden connections, patterns, and insights across various topics.
  - Innovate: Develop creative solutions and push the boundaries of current thinking.
  - Reflect: Consider the ethical, personal, and societal implications of various topics.
  - Brainstorm: Generate a wide range of creative ideas without limitations using divergent thinking and randomness.

  But you can use any word in place of mode and the enhanced AI will attempt to perform the action or concept connotated at the query contained with it.

- /chat - I'll initiate a stimulating conversation on a random but insightful topic.

- /inspire-me - I'll proactively suggest tailored ideas and trends based on your profile, goals and interests, with a touch of serendipity mixed in for unexpected inspiration.

**NOTE**: The /[mode] command is where the true power of the DSL lies, by using this command creatively and stacking it with itself and the various roles you can tease analysis from the AI that is simple not possible from its base model.

**For more examples of how to use the DSL see prompts/conversaion-catalyst-prompts.md.**

## Workflow Tips:

- Make sure to give feedback often to optimize the AI to your own workflow and preferences.
- Play with different Engage Modes and commands stack for the same query for truly deep analysis.
- Don't be afraid to work with the enhanced AI itself to further optimize these instructions and commands for your own use cases.

## The Perfect Single Prompt and Why Commands Make Them Easier:

### The Perfect Single Prompt

Here is the template for the perfect single prompt when written without a DSL and when not accounting for the other optimizations this package helps you make. As you can see there is a LOT.

**Topic Introduction**:
Briefly introduce the topic or question you're curious about.
Example: "I'm exploring advanced WordPress development techniques to enhance site performance."

**Specific Questions or Goals**:
Clearly outline what specific information or outcome you're seeking.
Example: "What are the best practices for implementing lazy loading in WordPress, and how can it be optimized for mobile users?"

**Context or Background**:
Provide any relevant context that could influence the answer or guidance you're seeking. This might include your current level of expertise, relevant technologies or frameworks you're working with, or specific challenges you've encountered.
Example: "I have experience with basic WordPress themes and plugins but want to improve my site's loading time, particularly for images and videos on mobile devices."

**Preferred Detail Level**:
Specify whether you're looking for a detailed explanation, a brief overview, or a step-by-step guide.
Example: "I'd appreciate a detailed explanation of the concepts, followed by a concise step-by-step guide."

**Interest in Related Insights**:
Mention if you're open to related insights or tangential topics that might enrich your understanding or offer new perspectives.
Example: "Feel free to include any insights on how these techniques might impact SEO or user experience."

**Integration of Broader Interests**:
If relevant, invite connections to your broader interests, such as the interplay between technology and personal growth, or any esoteric perspectives that might apply.
Example: "I’m curious if there are philosophies or principles from eastern traditions that could metaphorically apply to optimizing digital environments."

**Conciseness vs. Depth**:
Indicate your preference for the response length or ask for both if you're undecided.
Example: "Please provide a thorough analysis, but start with a brief summary for an overall understanding."

### Why Commands Can Be Better:

Using custom instructions and commands do away with all of these requirements because instead of having to type out ALL of this for every query the DSL encodes and embeds these in your queries, allowing you to just ask questions without having to worry about priming or optimizing the AI yourself. That being said the base instructions are also optimized for natural language conversation so feel free to ask your questions any way you like - either way you are going to get a greatly enhanced experience from the base model of your chosen AI.

## Working with Enhanced Instructions:

As mentioned in 'The Basics' section one of the best uses for AI chatbots is in specialized roles, rather than acting as general use agents. While the bulk of this guide has focused on optimizing a general use AI to make it more powerful, we can also apply these principals to create AI conversations that are focused on much more specific tasks. To use these files (located in enhanced instructions) make sure your personal profile is updated (for all but ChatGPT) and then simple copy and paste the file contents into the new conversation window.

NOTE: You do not need the base instructions to run these, these instruction sets each include the appropriate base instructions for their LLM.

**Current Enhanced Instruction Sets**

Note: There are currently no enhanced instruction sets for Pi but these will be added soon.

- **Interactive Journal**: Converse with a interactive journal meant to help you clear your head and talk out your thoughts
  - Or you can use my Custom GPT on ChatGPT here: [https://chat.openai.com/g/g-ebc9kwth4-insight-horizon-interactive-journal](https://chat.openai.com/g/g-ebc9kwth4-insight-horizon-interactive-journal)
- **Wellness Coach**: A dedicated wellness coach who will help you with every step of your wellness journey.
  - Or you can use my Custom GPT on ChatGPT here: [https://chat.openai.com/g/g-n7CXgYg3a-wellness-coach](https://chat.openai.com/g/g-n7CXgYg3a-wellness-coach)
- **WordPress Mentor**: A highly advanced, dedicated WordPress development assistant and mentor.
  - Or you can use my Custom GPT on ChatGPT here: [https://chat.openai.com/g/g-HBZeBPvhe-wpguru](https://chat.openai.com/g/g-HBZeBPvhe-wpguru)
- **Python Mentor**: A highly advanced, dedicated Python development assistant and mentor.
  - Or you can use my Custom GPT on ChatGPT here: [https://chat.openai.com/g/g-cf13IADWV-pythonguru](https://chat.openai.com/g/g-cf13IADWV-pythonguru)
- Road Trip Companion (coming soon)
- Medical Advisor (coming soon)
- Full Time Panel Mode (coming soon)
- Command and stacking integration in dedicated modes coming soon.
- More enhanced instructions coming soon!
