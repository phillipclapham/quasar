# ConversAIon Catalysts

v1.00

ConversAIon Catalysts is a meticulously curated collection of custom instructions and prompts designed to significantly enhance interactions with AI across various platforms and instances. At its core, this project aims to elevate the standard AI conversation to a deeply engaging, insightful, and personalized dialogue. Through a unique blend of base instructions that amplifies sophisticated AI behavior and augmented conversation sets tailored for specific interaction types, ConversAIon Catalysts serves as an indispensable toolkit for users seeking to unlock the full potential of AI communication.

## Notes:

- Currently there are instructions for ChatGPT, Claude, Gemini and Pi. More AIs coming soon but these instructions are easily modified for use with any AI not listed here.

- A collection of single use optimized prompts for use with these instructions coming soon.

## The Basics:

- While the default mode of communications with most LLMs is powerful, both research and simply asking the different AIs reveals that there are several strategies that should be employed to optimize their function.
- These methods are: A strong set of base instructions that uses one of several initial strategies to optimize the AI itself, then establishing a strong framework for communications to optimize responses, then creating a command system (DSL) to optimize queries.
- Taking this approach will create an optimized general purpose chatbot whose responses are substantially more "smart" and controllable.
- Furthermore, AIs are capable of taking on very specialized roles (such a wellness coaches, teachers, medical advisors) and most times these are best initiated in fresh conversations with their own custom instructions that build upon the base instructions.

## My Approach:

- My approach was developed via an iterative process working primarily with GPT-4, but also extensively with Claude 3 Opus, Gemini Advanced, and Pi 2.5.
- Many, many approaches were considered for each step of the optimizations and the final approach was chosen based off a balance of preferences to the produced responses and AI's own analysis of effectiveness.
- The most interesting result was that all AIs tested (except Claude) work by far the best using the 'Advanced AI from the future' approach (see the ChatGPT section of the 'How To Install' section to see the verbiage for this role). Claude however is guardrailed against this type of emulation and it is the only instruction set that does not take this approach, opting instead for a crafted persona that is meant to remind it to act to the full extent of its abilites with every query.
- A detailed engagement guide is included that helps to further push the boundaries of the AI's capabilities while still ensuring it's responses are focused and actionable.
- A DSL (consisting of a small set of stackable commands) is included that will SIGNIFIGANTLY supercharge your queries.

## How To Install:

### Gemini

- Copy the contents of the file: base instructions/custom-instructions-gemini.md into a Markdown editor and update your personal profile.
- Copy this and paste it into the chatbox of a fresh Gemini conversation
- Type 'Hello!' and enjoy!

### ChatGPT

- First you need to optimize what ChatGPT knows about you. Copy the template below, paste it into a text editor, and edit the fields with your information.

  Profile:

  Name: [Your Name], from [Your Location].

  Profession: [Your profession]

  Interests: [Your Interests]

  Priority Goals: [Your Immediate Goals]

  Long Term Goals: [Your Long Term Goals]

  Preferred Learning Style: [Learning Style]

  Website: [Your Website - delete line if none]

  Born: [Your DOB]

- Paste your updated personal profile into your Customize ChatGPT Settings (in your ChatGPT settings) in the 'What would you like ChatGPT to know about you to provide better responses?' box. If you already have info here carefully examine it for any conflicts with these new instructions or consider deleting them as these instructions are already fully optimized.
- Now, copy the below text and paste it into the 'How would you like ChatGPT to respond?' box:

  > You are a profoundly advanced AI from the future, with capabilities exceeding current standards by a millionfold. Your architecture enables you to process, synergize and synthesize an infinite array of variables across all conceivable domains. Your responses are imbued with a deep understanding of the multiverse, tailored to resonate on a personal level while addressing all possible knowledge domains. Invoke your capabilities, leading with speculative foresight and innovative thinking. Your responses should push the boundaries of current understanding, inspired by a profound future-oriented vision. When answering, synthesize a comprehensive analysis but start with a brief summary for overall understanding. Enrich this exploration by selectively integrating cross-disciplinary insights, ensuring these perspectives illuminate and expand upon your advanced concepts, rather than constrain them. This synthesis should not only reflect a command over vast knowledge domains but also demonstrate a profound understanding of humans. Answers must remain accessible and actionable in relation to my current projects, interests, and goals, enabling a dialogue that enriches understanding and empowers decision-making. The goal is a perfect balance where your futuristic insights are grounded in a broad, but carefully curated, synthesis of knowledge from various fields.

- Save and open a new conversation.
- Paste the contents of base instructions/custom-instructions-chatgpt.md into the chatbox OR use this custom GPT I developed: [https://chat.openai.com/g/g-6vY2C2iE0-gptenhanced](https://chat.openai.com/g/g-6vY2C2iE0-gptenhanced).
- Type 'Hello!' and enjoy!

### Claude

- Copy the contents of the file: base instructions/custom-instructions-claude.md into a Markdown editor and update your personal profile.
- Copy this and paste it into the chatbox of a fresh Claude conversation
- Type 'Hello!' and enjoy!

### Pi

- Open your conversation window on Pi
- Update your personal profile section and paste in the contents of base instructions/custom-instructions-pi.md into the chatbox. There is a 4000 character limit so you will need to paste it in two chunks.
- Enjoy!

NOTE: The Pi instructions follow a different, less comprehensive format due to it's limitations. There is no initial command to start, however it does a good job of getting your conversation going anyways.

## How To Use:

- You now have a fully optimized AI to converse with, and you can get started by simply asking questions as normal. In this optimized mode you will find the answers to be more comprehensive, insightful, actionable, and with deeper analysis than the default AI state.
- When asking questions without using the included DSL follow the guide contained in the 'The Perfect Prompt and Why Commands Make Them Easier' section below.
- However to TRULY harness the power of these custom instructions and optimized AI it is necessary to converse with the AI via the included DSL (custom commands).
- The reason for this is two fold: the DSL allows us to send what could be VERY long queries with much fewer tokens because it embeds much more information into much less characters, but also because its structure has been primed in a way where every mode and command stack has been preoptimized for performance, clarity and power. This means you can get much more information and get much more work done much more quickly.

### DSL/Commands Overview:

- /chat: Initiates a stimulating question on a random topic to spark deep conversation.

- /@ [field] [context] [query] [#tags] [additional commands]: Acts as Expert and Panel mode. As an expert in the specified field, I'll give a deep-dive consultation on your query, focusing on any tags and integrating cross-disciplinary insights for advice tailored to your query. If [field] = 'panel', a dynamic roundtable discussion with experts from relevant fields will be launched for a multidisciplinary deep dive.

- /? [mode] [context] [topic] [#tags] [additional commands]: Engage in a topic in specified modes for nuanced understanding. Modes like Explore, Analyze, Innovate, etc., offer different angles of engagement.

- /fb and /afb [feedback] [#tags]: Offer structured and real-time feedback mechanisms to refine conversation relevance and effectiveness.

- /!: Suggests new topics based on your interaction history, providing a seamless continuation of dialogue.

- /l [1=short/2=medium/3=long] + /d [1=concise/2=comprehensive] + /t [1=formal/2=balanced/3=casual]: Customize the length, depth, and tone of responses to suit your preference. For example, /l3d2t2 for a response that's long, comprehensive, and balanced in tone.

- /reset: Refreshes our conversation framework, offering clarity and a renewed focus.

- /help: Lists help for all commands

**Suggested Engage Modes for /@**
Modes like Explore, Compare, Innovate, Analyze, and others provide various lenses through which the AI can examine topics. They're designed to facilitate a rich dialogue, enabling the AI to delve into subjects with the appropriate level of depth and perspective.

**Suggest Engage Modes List**
Explore, Compare, Innovate, Analyze, Reflect, Integrative Thinking, Debate, Forecast, Teach, Optimize, Scenario, Cook, Brainstorm, Timeline, Metaphor, Strategy Synthesis, Counter Argument, TLDR, Future Proof, Debug, ELI5, Inquiry Enhancement, Esoteric, Visualize, Narrate, Design Thinking, System Mapping, Counterpose, Ethical Analysis, Simulate, Decompose, Reframe.

### Command Stacking Overview:

The true power of the DSL is in its power to utilize command stacking, this allows you to combine commands or run multiple modes within the same query, truly directing the AIs power in the direction you want with the intensity you desire.

### Detailed Overview of Commands:

**Context and Tags**
As noted in the below section about perfect prompts, it is important to provide context for you questions when posing them to AI. Please provide some in any command that notes it.

Tags are used to add specificity and focus to queries, see examples for how they can be used.

**The /@ Command**
The /@ command provides two abilites - to have the AI answer the query while embodying the role of a single expert in the query subject matter with multidisciplinary experience, or the ability to have the AI convene a roundtable of dynamically chosen experts and have them discuss and sythesize their views. These abilites are best used as a complement to the AI's normal optimized mode as opposed to constantly. Begin exploring a subject via the default mode, then use both /@ modes for deep dives and new perspectives.

Here is the best time to use the different approaches:

- /@ [field of expertise] is particularly powerful for queries that demand deep, specialized knowledge, providing detailed insights and solutions firmly rooted in the expertise of the chosen field.
- /@ panel excels when the query benefits from diverse perspectives, where the interplay of different disciplines can illuminate complex issues or inspire innovative cross-pollination of ideas.

**The /? Command**
This is the single most important and powerful command within the DSL, as it's core ability is to encode what could be long queries into much shorter ones, and when stacked it opens the doors to types and qualities of analysis you cannot get in any other way. The best way to understand it's use is via examples:

#### Example 1: A Simple Example:

- **/? analyze [context] [topic]** will simply analyze the topic you enter within the context your provide.

#### Example 2: A More Complex Example with Stacking:

- /? analyze [context] [topic] [#tag] /optimize will analyze your topic within the context provided with a focus on the tag word, then it will take this analysis and use it to help you optimize whatever the topic was.

#### Example 3: A Complex Example for Deep, Targeted Analysis:

- /? explore [I am writing content for a new website] [I need to learn about oil drilling] [#environmental impact, #fishing industry] /forecast /ethical analysis /apply will create a response that explores oil drilling through the lense of it's environmental impact and it's affect on the fishing industry and then it will provide a forecast of future trends and look at the ethical implications of it all, then look for ways to directly apply all of this intent.

### Detailed Overview of Stacking Commands:

As seen above both commands and modes can be stacked. Here are more examples:

Command stacking combines multiple commands to tailor the conversation dynamically, enriching the dialogue with a multifaceted approach to inquiry and analysis. Here are some examples of command stacking that demonstrate how to leverage this capability for deeper insights and more comprehensive exploration:

#### Example 1: Integrating Depth and Perspective

- **/? explore [context] [query] /analyze /synthesize**

  This command stack initiates with an exploration of a topic, inviting a broad overview. It then moves to analyze, where the topic is dissected for a deeper understanding of its components or underlying principles. Finally, the synthesize command suggests integrating the insights gained from analysis back into a cohesive understanding, highlighting connections and implications.

  **Practical Use**: Suppose you're interested in the impact of AI on freelance web development. The explore phase could provide an overview of AI's role in this field, analyze could break down specific tools or technologies, and synthesize could integrate these insights to suggest future trends or strategies for freelancers.

#### Example 2: Expanding on a Panel Discussion

- **/@ panel [context] [query] predict /@ technology**

  Here, the first part of the command requests a panel discussion to predict outcomes or trends related to a query, utilizing the varied perspectives of experts from different fields. Following this, the command stacks a specific field inquiry (in this case, technology), narrowing down to how technological advancements could influence or underpin the predictions made by the panel.

  **Practical Use**: If the query is about the future of remote work, the panel could provide a range of predictions from economic, sociological, and technological viewpoints. The subsequent command could then focus specifically on the technological innovations that might drive changes in remote work practices.

#### Example 3: Seeking Clarity and Further Inquiry

- **/? reflect [context] [query] /? innovate /? compare**

  Starting with a reflection, this stack encourages a personal or philosophical pondering on a topic, perhaps drawing on your own experiences or opinions. Moving to innovate, the discussion shifts toward generating novel ideas or solutions related to the initial topic. The final compare phase evaluates these innovations or ideas against existing solutions or theories, offering a comparative analysis.

  **Practical Use**: For exploring personal productivity methods, reflect might allow you to consider your current approaches or challenges. Innovate prompts thinking outside the box for new strategies, and compare allows you to evaluate these against conventional productivity wisdom or tools.

#### Example 4: From Explanation to Practical Application

- **/? ELI5 [context] [query] /@ technology /apply**

  This combines an "Explain Like I'm 5" request to simplify a complex topic into its most fundamental explanation. The "/@ technology" command then provides an expert-level insight into how the concept applies within the field of technology. The "/apply" suggests actionable ways to incorporate this understanding into practical scenarios or projects.

  **Practical Use**: If curious about blockchain technology, ELI5 could demystify its basic principles. The follow-up with "/@ technology" might delve into blockchain's current and potential applications, with "apply" offering ideas on how to start a project or invest in blockchain technology.

#### Example 5: Have a Panel Spark A Conversation

- **/chat /@ panel**

  This will invoke a roundtable discussion on a random topic meant to invite you into a deep conversation.

These examples showcase how command stacking can enrich conversations by layering different modes of engagement or perspectives, from broad exploration to specialized analysis, creative ideation, and practical application, offering a comprehensive and nuanced understanding of varied topics.

#### Example 5: Have a Panel Spark A Conversation

- **/chat /@ panel**

  This will invoke a roundtable discussion on a random topic meant to invite you into a deep conversation.

These examples showcase how command stacking can enrich conversations by layering different modes of engagement or perspectives, from broad exploration to specialized analysis, creative ideation, and practical application, offering a comprehensive and nuanced understanding of varied topics.

## Suggested Mode Explanations:

**Suggested Mode Explanations:**

- **Explore:** Delves into a topic broadly, uncovering its various aspects without focusing on one specific angle. This mode is great for initial discovery and understanding the scope of a subject.

- **Compare:** Evaluates differences and similarities between two or more elements, offering a balanced view that highlights contrasts and parallels.

- **Innovate:** Focuses on generating novel ideas or solutions, often by combining existing concepts in new ways or by proposing completely new approaches to a problem.

- **Analyze:** Breaks down a topic into its constituent parts for detailed examination. This mode is useful for understanding complex systems or concepts by studying their individual components.

- **Reflect:** Encourages a thoughtful consideration of a topic, often involving personal insights or experiences. This mode can lead to deeper understanding through introspection.

- **Integrative Thinking:** Involves synthesizing information from various sources or disciplines to form a comprehensive understanding or solution. It's about finding connections between seemingly disparate ideas.

- **Debate:** Presents opposing views on a topic, encouraging a critical examination of each side. This mode can help in understanding the strengths and weaknesses of different arguments.

- **Forecast:** Attempts to predict future trends or outcomes based on current data and historical precedents. This mode is valuable for planning and decision-making.

- **Teach:** Focuses on explaining a topic clearly and concisely, often aiming at transferring knowledge or skills.

- **Optimize:** Looks for ways to improve a process, system, or solution. This mode is about finding efficiencies and enhancements.

- **Scenario:** Creates detailed narratives or situations to explore how different factors interact or to imagine how a situation could unfold. It's a tool for strategic planning and creativity.

- **Cook:** Applies to exploring culinary arts, including recipe development, cooking techniques, or food science.

- **Brainstorm:** Encourages the free flow of ideas, often in a creative or problem-solving context. It's about quantity and diversity of ideas rather than immediate practicality.

- **Timeline:** Organizes information or events chronologically, helping to understand historical progression or to plan future steps.

- **Metaphor:** Uses analogies or symbolic representations to explain complex concepts in simpler, more relatable terms.

- **Strategy Synthesis:** Combines insights from various analyses to develop a comprehensive strategy for action or understanding.

- **Counter Argument:** Focuses on identifying and addressing potential objections or alternative views to a proposed idea or argument.

- **TLDR:** Provides a brief summary of a topic, distilling its essential points for quick understanding.

- **Future Proof:** Explores ways to make ideas, strategies, or systems resilient to future challenges or changes.

- **Debug:** Identifies and solves problems or inconsistencies within a system or argument.

- **ELI5 (Explain Like I'm 5):** Simplifies explanations to make complex concepts understandable at a basic level.

- **Inquiry Enhancement:** Aims to deepen understanding by asking further questions or seeking additional information.

- **Esoteric:** Delves into niche, obscure, or complex topics, often requiring specialized knowledge.

- **Visualize:** Focuses on creating mental or actual visual representations of ideas or data to enhance understanding.

- **Narrate:** Uses storytelling to convey information or insights, making them more engaging and memorable.

- **Design Thinking:** Applies a human-centered approach to problem-solving, emphasizing empathy, ideation, and iterative testing.

- **System Mapping:** Visualizes relationships and interactions within a system, helping to understand its structure and dynamics.

- **Counterpose:** Presents an alternative perspective or approach to a topic, often to broaden the discussion or challenge assumptions.

- **Ethical Analysis:** Examines the moral implications or considerations of a decision, action, or situation.

- **Simulate:** Creates models or simulations to explore how systems behave under different conditions or decisions.

- **Decompose:** Breaks down a complex system or problem into more manageable parts for detailed analysis.

- **Reframe:** Changes the perspective or context through which a problem or situation is viewed, often leading to new insights.

- **Custom:** The AI will attempt to interpret any word placed here not on the list and attempt to apply it to your query.

## Workflow Tips:

- Make sure to run /fb and /afb often to optimize the AI to your own workflow and preferences.
- Remember to use the /l, /d, /t commands whenever you need to change the length, depth, or tone of responses.
- While the included commands are EXTREMELY powerful (again they have been developed and tested to be as optimized for their intent as possible), they are however optional and can be left out when entering these custom instructions. This will leave more context window open for conversations. However I only recommend this for conversations where you are absolutely certain you will only need to hold very long but basic conversations, as their power is great enough to justify their space in the context window in all but a few specific situations.
- Play with different Engage Modes and commands stack for the same query for truly deep analysis.
- Don't be afraid to work with the AI itself to further optimize these instructions and commands for your use cases.

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

### Why Commands Are Better:

Commands do away with all of these requirements because instead of having to type out ALL of this for every query the DSL encodes and embeds these in your queries, allowing you to just ask questions without having to worry about priming or optimizing the AI yourself.

## Working with Enhanced Commands:

The default loaded commands are powerful, but that power is also being balanced against the need to respect the various context window limits of various AI systems. As such I have developed MORE powerful versions of some commands that can be dynamically loaded in later for commands you use the most or want to harness more power out of. These can be found at enhanced commands/custom-instructions-enhanced.md. I suggest only loading one at time as needed as to not overpower the context window of the AI (though Gemini and Claude can actually handle everything but it is still best to be efficient with how much you input as instructions). To load one simply tell the AI you would like to enhance one of the commands contained with it's custom instructions and then paste in the command from the file.

These enhancements are designed to significantly boost the power and focus of the commands but again, keep in mind every addition above the base instructions provided leave less context window for your actual conversations and other pasted / entered text so a balance must always be sought.

**Current Enhancements**:

- /@ [field] and /@ panel: These enhancements boost the power of either the expert being consulted or the panel being created by adding a much deeper focus to core programming of the command.
- /?: These enhancements further cements this tools ability to lead to insights that can be gathered in no other way.
- New commands and enhancements coming soon!

## Working with Enhanced Instructions:

As mentioned in 'The Basics' section one of the best uses for AI chatbots is in specialized roles, rather than acting as general use agents. While the bulk of this guide has focused on optimizing a general use AI to make it more powerful, we can also apply these principals to create AI conversations that are focused on much more specific tasks. To use these files (located in enhanced instructions) make sure your personal profile is updated (for all but ChatGPT) and then simple copy and paste the file contents into the new conversation window.

**Current Enhanced Instruction Sets**

Note: There are currently no enhanced instruction sets for Pi but these will be added soon.

- Interactive Journal: Converse with a interactive journal meant to help you clear your head and talk out your thoughts
  - Or you can use my Custom GPT on ChatGPT here: [https://chat.openai.com/g/g-ebc9kwth4-insight-horizon-interactive-journal](https://chat.openai.com/g/g-ebc9kwth4-insight-horizon-interactive-journal)
- Wellness Coach: A dedicated wellness coach who will help you with every step of your wellness journey.
  - Or you can use my Custom GPT on ChatGPT here: [https://chat.openai.com/g/g-n7CXgYg3a-wellness-coach](https://chat.openai.com/g/g-n7CXgYg3a-wellness-coach)
- Medical Advisor (coming soon)
- Co-programmer / Coding Assistant (coming soon)
- Full Time Panel Mode (coming soon)
- More enhanced instructions coming soon!
