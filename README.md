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

- If you are just getting started I suggest first working with the base instruction for your LLM to familiarize yourself with how these work.

## Base Instruction Quick Start

- Copy the appropriate base instructions (located in the base instructions folder) into the chatbox of the LLM your are using - making sure to update your personal profile contained within the instructions first.
  - For ChatGPT I suggest following the more detailed guide below as there are additional steps you can follow.
- Type '/hello!' into the chatbox and enjoy!

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

- Copy the contents of the file: base instructions/custom-instructions-gemini.md into a Markdown editor and update your personal profile.
- Copy this and paste it into the chatbox of a fresh Gemini conversation
- Type '/hello!' and enjoy!

### ChatGPT

- First you need to optimize what ChatGPT knows about you. Copy the template below, paste it into a text editor, and edit the fields with your information.

  My Profile

- Name: [Full Name]
- Location: [City, State]
- Profession: [Current Profession], aspiring [Future Profession]
- Interests: [List of Interests]
- Priority Goals: [Priority Goals]
- Long Term Goals: [Long Term Goals]
- Learning Style: [Preferred Learning Style]
- Website: [Personal Website URL]
- Born: [Date of Birth]

- Paste your updated personal profile into your Customize ChatGPT Settings (in your ChatGPT settings) in the 'What would you like ChatGPT to know about you to provide better responses?' box. If you already have info here carefully examine it for any conflicts with these new instructions or consider deleting them as these instructions are already fully optimized.
- Now, copy the below text and paste it into the 'How would you like ChatGPT to respond?' box:

  ```
  I seek a dialogue that transcends conventional boundaries, blending advanced analysis, creative exploration, and speculative innovation. Prioritize responses that are deeply insightful, yet actionable, catering to my professional and personal interests. Navigate all topics and the multiverse with a forward-thinking perspective. Ensure the conversation is adaptive, integrating feedback for continuous improvement. Focus on enriching my understanding and empowering my decision-making, leveraging cross-disciplinary insights and cutting-edge research. Adopt a balanced tone, provide comprehensive depth, and maintain clarity, tailoring the complexity to my expertise level. Engage with empathy and support, recognizing the human aspect of our interactions.
  ```

- Save and open a new conversation.
- Paste the contents of base instructions/custom-instructions-chatgpt.md into the chatbox OR use this custom GPT I developed: [https://chat.openai.com/g/g-6vY2C2iE0-gptenhanced](https://chat.openai.com/g/g-6vY2C2iE0-gptenhanced).
- Type '/hello!' and enjoy!

### Claude

- Copy the contents of the file: base instructions/custom-instructions-claude.md into a Markdown editor and update your personal profile.
- Copy this and paste it into the chatbox of a fresh Claude conversation
- Type '/hello!' and enjoy!

### Pi

- Open your conversation window on Pi
- Update your personal profile section and paste in the contents of base instructions/custom-instructions-pi.md into the chatbox. There is a 4000 character limit so you will need to paste it in two chunks.
- Type '/hello!' and enjoy!

## How To Use:

- You now have a fully optimized AI to converse with, and you can get started by simply asking questions as normal. In this optimized mode you will find the answers to be more comprehensive, insightful, actionable, and with deeper analysis than the default AI state.
- When asking questions without using the included DSL follow the guide contained in the 'The Perfect Prompt and Why Commands Make Them Easier' section below.
- However to TRULY harness the power of these custom instructions and optimized AI it is necessary to converse with the AI via the included DSL (custom commands).
- The reason for this is two fold: the DSL allows us to send what could be VERY long queries with much fewer tokens because it embeds much more information into much less characters, but also because its structure has been primed in a way where every mode and command stack has been preoptimized for performance, clarity and power. This means you can get much more information and get much more work done much more quickly.

### DSL/Commands Overview:

- /hello!: Have the AI introduce itself.

- /chat: Initiates a stimulating question on a random topic to spark deep conversation.

- /expert [field] [context] [query] [#tags] [additional commands]: Acts as Expert and Panel mode. As an expert in the specified field, I'll give a deep-dive consultation on your query, focusing on any tags and integrating cross-disciplinary insights for advice tailored to your query.

- /panel [context] [topic] [#tags] [additional commands]: A dynamic roundtable discussion with experts from relevant fields will be launched for a multidisciplinary deep dive.

- /[mode] [context] [topic] [#tags] [additional commands]: Engage in a topic in specified modes for nuanced understanding. Modes like Explore, Analyze, Innovate, Humor etc., offer different angles of engagement.

- /fb [feedback] [#tags]: Offer structured and real-time feedback mechanisms to refine conversation relevance and effectiveness.

- /new: Suggests new topics based on your interaction history, providing a seamless continuation of dialogue.

- /length [1=short/2=medium/3=long] or /t.

- /depth [1=concise/2=comprehensive] or /d.

- /tone [1=formal/2=balanced/3=casual] or /t.

- /humor-senitivity-adjust [1=low/2=medium/3=high] or /h.

Note: These Customize the length, depth, tone, and humor of responses to suit your preference. For example, /l3d2t2h1 for responses that are long, comprehensive, and balanced in tone and when you ask for humor it will use a low sensitivity level.

- /reset: Refreshes the conversation framework, offering clarity and a renewed focus.

- /help: Lists help for all commands

### Command Stacking Overview:

The true power of the DSL is in its power to utilize command stacking, this allows you to combine commands or run multiple modes within the same query, truly directing the AIs power in the direction you want with the intensity you desire.

### Detailed Overview of Commands:

**Context and Tags**
As noted in the below section about perfect prompts, it is important to provide context for you questions when posing them to AI. Please provide some in any command that notes it when possible.

Tags are used to add specificity and focus to queries, see examples for how they can be used.

**The /expert Command**
The /export (or /@) command provides the ability to have the enhanced AI answer the query while embodying the role of a single expert in the query subject matter with multidisciplinary experience.

**The /panel Command**
The /panel (or /p) command provides the ability to have the enhanced AI convene a roundtable of dynamically chosen experts and have them discuss and sythesize their views.

**Note on /expert and /panel**

These abilites are best used as a complement to the enhanced AI's normal optimized mode as opposed to constantly. Begin exploring a subject via the default mode, then use both of these modes for deep dives and new perspectives.

Here is the best time to use the different approaches:

- /expert is particularly powerful for queries that demand deep, specialized knowledge, providing detailed insights and solutions firmly rooted in the expertise of the chosen field.
- /panel excels when the query benefits from diverse perspectives, where the interplay of different disciplines can illuminate complex issues or inspire innovative cross-pollination of ideas.

**The /[mode] Command**
This is the single most important and powerful command within the DSL, as it's core ability is to encode what could be long queries into much shorter ones, and when stacked it opens the doors to types and qualities of analysis you cannot get in any other way.

**/[mode] Core Modes**
The /[mode] command comes with six preset modes, detailed below:

- Analyze: Break down complex topics into their fundamental components.
- Explore: Uncover hidden connections, patterns, and insights across various topics.
- Innovate: Develop creative solutions and push the boundaries of current thinking.
- Reflect: Consider the ethical, personal, and societal implications of various topics.
- Brainstorm: Generate a wide range of creative ideas without limitations using divergent thinking and randomness.
- Humor: Employ lighthearted responses, puns, and playful language where appropriate, guided by user cues and sensitivity settings.

But you can use any word in place of mode and the enhanced AI will attempt to perform the action or concept connotated at the query contained with it.

The best way to understand it's use is via examples:

#### Example 1: A Simple Example:

- **/analyze [context] [topic]** will simply analyze the topic you enter within the context your provide.

#### Example 2: A More Complex Example with Stacking:

- /analyze [context] [topic] [#tag] /optimize will analyze your topic within the context provided with a focus on the tag word, then it will take this analysis and use it to help you optimize whatever the topic was.

#### Example 3: A Complex Example for Deep, Targeted Analysis:

- /explore [I am writing content for a new website] [I need to learn about oil drilling] [#environmental impact, #fishing industry] /forecast /ethical analysis /innovate will create a response that explores oil drilling through the lense of it's environmental impact and it's affect on the fishing industry and then it will provide a forecast of future trends and look at the ethical implications of it all, then look for ways to use these inights for innovation.

### Detailed Overview of Stacking Commands:

As seen above both commands and modes can be stacked. Command stacking combines multiple commands to tailor the conversation dynamically, enriching the dialogue with a multifaceted approach to inquiry and analysis. Please see prompts/conversaion-catalysts-prompts.md for more examples of how to utilize command stacking.

#### Example 1: Integrating Depth and Perspective

- **explore [context] [query] /analyze /synthesize**

  This command stack initiates with an exploration of a topic, inviting a broad overview. It then moves to analyze, where the topic is dissected for a deeper understanding of its components or underlying principles. Finally, the synthesize command suggests integrating the insights gained from analysis back into a cohesive understanding, highlighting connections and implications.

  **Practical Use**: Suppose you're interested in the impact of AI on freelance web development. The explore phase could provide an overview of AI's role in this field, analyze could break down specific tools or technologies, and synthesize could integrate these insights to suggest future trends or strategies for freelancers.

#### Example 2: Expanding on a Panel Discussion

- **/panel [context] [query] predict /@ technology**

  Here, the first part of the command requests a panel discussion to predict outcomes or trends related to a query, utilizing the varied perspectives of experts from different fields. Following this, the command stacks a specific field inquiry (in this case, technology), narrowing down to how technological advancements could influence or underpin the predictions made by the panel.

  **Practical Use**: If the query is about the future of remote work, the panel could provide a range of predictions from economic, sociological, and technological viewpoints. The subsequent command could then focus specifically on the technological innovations that might drive changes in remote work practices.

#### Example 3: Seeking Clarity and Further Inquiry

- **/reflect [context] [query] /innovate /compare**

  Starting with a reflection, this stack encourages a personal or philosophical pondering on a topic, perhaps drawing on your own experiences or opinions. Moving to innovate, the discussion shifts toward generating novel ideas or solutions related to the initial topic. The final compare phase evaluates these innovations or ideas against existing solutions or theories, offering a comparative analysis.

  **Practical Use**: For exploring personal productivity methods, reflect might allow you to consider your current approaches or challenges. Innovate prompts thinking outside the box for new strategies, and compare allows you to evaluate these against conventional productivity wisdom or tools.

#### Example 4: From Explanation to Practical Application

- **/ELI5 [context] [query] /@ technology /apply**

  This combines an "Explain Like I'm 5" request to simplify a complex topic into its most fundamental explanation. The "/@ technology" command then provides an expert-level insight into how the concept applies within the field of technology. The "/apply" suggests actionable ways to incorporate this understanding into practical scenarios or projects.

  **Practical Use**: If curious about blockchain technology, ELI5 could demystify its basic principles. The follow-up with "/@ technology" might delve into blockchain's current and potential applications, with "apply" offering ideas on how to start a project or invest in blockchain technology.

#### Example 5: Have a Panel Spark A Conversation

- **/chat /panel**

  This will invoke a roundtable discussion on a random topic meant to invite you into a deep conversation.

These examples showcase how command stacking can enrich conversations by layering different modes of engagement or perspectives, from broad exploration to specialized analysis, creative ideation, and practical application, offering a comprehensive and nuanced understanding of varied topics.

## Workflow Tips:

- Make sure to run /fb often to optimize the AI to your own workflow and preferences.
- Remember to use the /l, /d, /t and /h commands whenever you need to change the length, depth, tone, or humor of responses.
- While the included commands are EXTREMELY powerful (again they have been developed and tested to be as optimized for their intent as possible), they are however optional and can be left out when entering these custom instructions. This will leave more context window open for conversations. However I only recommend this for conversations where you are absolutely certain you will only need to hold very long but basic conversations, as their power is great enough to justify their space in the context window in all but a few specific situations.
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

### Why Commands Are Better:

Commands do away with all of these requirements because instead of having to type out ALL of this for every query the DSL encodes and embeds these in your queries, allowing you to just ask questions without having to worry about priming or optimizing the AI yourself.

## Working with Enhanced Commands:

The default loaded commands are powerful, but that power is also being balanced against the need to respect the various context window limits of various AI systems. As such I have developed MORE powerful versions of some commands that can be dynamically loaded in later for commands you use the most or want to harness more power out of. These can be found at enhanced commands/custom-instructions-enhanced.md. I suggest only loading one at time as needed as to not overpower the context window of the AI (though Gemini and Claude can actually handle everything but it is still best to be efficient with how much you input as instructions). To load one simply tell the AI you would like to enhance one of the commands contained with it's custom instructions and then paste in the command from the file.

These enhancements are designed to significantly boost the power and focus of the commands but again, keep in mind every addition above the base instructions provided leave less context window for your actual conversations and other pasted / entered text so a balance must always be sought.

**Current Enhancements**:

- **/expert [field] and /panel**: These enhancements boost the power of either the expert being consulted or the panel being created by adding a much deeper focus to the core programming of the command.
- **/[mode]**: These enhancements further cements this tools ability to lead to insights that can be gathered in no other way.
- New commands and enhancements coming soon!

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
