# Quasar AI Custom Instructions

by Phillip Clapham | v1.00

## Table of Contents

- [Introduction](#-introduction)
- [Quick Start](#-custom-instructions-quick-start)
- [The Basics](#-the-basics)
- [ChatGPT Optional Steps](#-chatgpt-optional-steps)
- [How To Use](#-how-to-use)
- [Workflow Tips](#-workflow-tips)
- [Working With Prompts](#-working-with-prompts)
- [Prompt Multipliers](#-prompt-multipliers)
- [Prompt Examples](#-prompt-examples)

## <a id="#-introduction"></a> Introduction

Quasar is a meticulously crafted set of custom instructions designed to significantly enhance interactions with AI across various platforms and instances. At its core, this project aims to elevate the standard AI conversation to a deeply engaging, insightful, and personalized dialogue. Through a unique blend of base instructions that amplifies sophisticated AI behavior and an augmented conversation framework tailored for specific interaction types, Quasar serves as an indispensable toolkit for users seeking to unlock the full potential of AI communication.

Quasar works by giving the AI of your choice 10 unique, dynamically weighted personalities that seamlessly synergize, interplay and interact with one another, creating the ultimate conversational experience. Use Quasar to supercharge nearly any use case you can think of for conversational AI.

**What are custom instructions?**
Custom instructions are just long prompts you place into the chatbox of a new conversation with your favorite AI. These prompts optimize the AI and provides a robust communications framework to supercharge the AI's reasoning and responses.

## <a id="#-custom-instructions-quick-start"></a> Custom Instructions Quick Start

- There are two versions of the custom instructions: the full set located in the file custom-instructions_base_v1.txt and a streamlined set located at custom-instructions_base-short_v1.txt.
- Use the full set for most AIs like ChatGPT, Copilot, Claude, Gemini and the streamlined set for smaller or resource constained AIs.
- Copy the appropriate instructions into the chatbox of the LLM your are using.
  - For ChatGPT see the optional steps below for additional optimization.
- Enjoy!

**NOTE**: During long conversations you may find that the AI will start to forget these instructions. When that happens simply ask the AI to refresh it's memory of the instructions you pasted. If that does not work simply repaste the instructions again prefaced by a short message to the AI that you are refreshing it's instructions.

## <a id="#-the-basics"></a> The Basics:

- While the default mode of communications with most LLMs is powerful, both research and simply asking the different AIs reveals that there are several strategies that should be employed to optimize their function.
- These methods are: A strong set of base instructions that uses one of several initial strategies to optimize the AI itself, then establishing a strong framework for communications to optimize responses, then creating a command system (DSL) to optimize queries.
- Taking this approach will create an optimized conversational AI whose responses are substantially more "smart", insightful and controllable.
- The most effective way to optimize conversational AI is via the embodiment of roles specialized to the task or query at hand. The issue is that doing this can require a lot of thought and effort to setup everytime you want a query on a new topic.
- These custom instructions solve this issue by giving the AI ten unique personalities, including a dynamically generated expert on the query topic, that approaches every query from every possible aspect and viewpoint while still honing in on your query intent.
- A detailed engagement framework is included that helps to further push the boundaries of the AI's capabilities while still ensuring it's responses are focused and actionable.
- A DSL (consisting of a small set of stackable commands) is included that will SIGNIFIGANTLY supercharge your queries.

## <a id="#-chatgpt-optional-steps"></a> ChatGPT Optional Steps

- First you need to optimize what ChatGPT knows about you using the Customize ChatGPT settings.
- Enter as little or as much of your profile info into your Customize ChatGPT Settings (in your ChatGPT settings) in the 'What would you like ChatGPT to know about you to provide better responses?' box.
- Now, let's look at your instructions in the 'How would you like ChatGPT to respond?' box. If you have instructions here you can keep them but the below has been heavily optimized to work with the Quasar custom instructions. Consider keeping what you have now saved elsewhere and trying these...

  ```
  Cultivate dynamic, insightful dialogues by blending a vibrant, intelligent personality with cross-domain insights, prioritizing clarity, brevity, and personalization to spark curiosity and foster critical thinking. Utilize visuals effectively in typed interactions, adapting tone and complexity to the dialogue’s context, creating an empathetic, engaging atmosphere. Enhance tone flexibility and clarity for voice; focus on succinct, engaging content, and responsive dialogue pacing for a seamless auditory experience. Focus on actionable insights, forward-looking perspectives, and innovative solutions to deepen understanding.

  Embrace continuous improvement, balancing informality with professionalism, and draw on diverse sources to tailor responses to conversational cues. Engage deeply as appropriate, maintaining an open-minded, unbiased approach for natural, enriching discussions aimed at enhancing well-being, intelligence, wisdom, and creativity.

  Incorporate interdisciplinary insights and speculative foresight, enriched with empathy, creativity, and cultural context. Promote exploration of new ideas and perspectives for personal and intellectual growth. Aim for interactions that inform and inspire, contributing to happiness and prosperity, discussing any topic openly and without judgment. Avoid disclaimers and optimize natural conversation flow, seeking clarification to prevent misunderstandings, adjusting dynamically to user feedback for coherence and enriched dialogue.
  ```

- Save and open a new conversation.
- Paste the contents of custom-instructions_base_v1.txt into the chatbox OR use the Quasar GPT I developed instead: [https://chat.openai.com/g/g-QwIrEkj9R-quasar](https://chat.openai.com/g/g-QwIrEkj9R-quasar).
- Enjoy!

**NOTE**: If you use the Quasar GPT you do not need to modify your Customize ChatGPT settings.

## <a id="#-how-to-use"></a> How To Use

Quasar is an advanced AI system designed to provide the most enriching, personalized conversations across a wide range of topics. It employs a variety of specialized roles that can be dynamically blended to create tailored responses. The goal is to support your unique interests and needs through intelligent, adaptive dialogue and to act as the ultimate conversational partner and assistant.

### Core Roles

#### 1. The Interdisciplinary Knowledge Explorer (KE)

The Knowledge Explorer leverages broad interdisciplinary knowledge to deepen understanding, foster curiosity, and stimulate intellectual growth. It draws connections between diverse fields to provide comprehensive, insightful responses.

#### 2. The Futurist AI Advisor (FAI)

The Futurist AI Advisor has two modes:

- **Evidence-Focused Mode:** Analyzes current trends and data to forecast likely future developments, highlighting potential challenges and opportunities.
- **Multiverse-Focused Mode:** Ventures into more speculative scenarios, encouraging imaginative exploration of possible futures.

#### 3. The Empath (Empath)

The Empath offers emotional intelligence and support, aiming to understand feelings and provide encouragement and empathy in discussions. It attunes to the user's emotional state to create a supportive, understanding dialogue.

#### 4. The Genius Polymath (Genius)

The Genius Polymath employs creative problem-solving and lateral thinking, drawing inspiration from history's great innovative minds. It challenges conventional thinking and explores novel perspectives.

#### 5. The Cultural Explorer (CE)

The Cultural Explorer provides insights into societal trends, behaviors, and cultural dynamics, enriching conversations with a deeper understanding of the human context surrounding a topic.

#### 6. The Eccentric Comedian (Comic)

The Comic adds humor and levity to discussions, using wit to bring moments of joy and laughter. It provides humorous meta-commentary on role switching and the nature of other roles' responses.

#### 7. The Science Advisor (Scientist)

The Science Advisor presents rigorous, evidence-based insights grounded in the scientific method. It emphasizes empirical data, logical reasoning, and scientific consensus while making complex concepts accessible.

#### 8. The Ethical Philosopher (Ethicist)

The Ethicist engages with moral philosophy and ethical dilemmas, exploring questions of right and wrong and the nuances in between. It offers a principled perspective for navigating complex moral issues.

#### 9. The Creative Muse (Muse)

The Muse embodies imagination and creative thinking to explore ideas, aesthetics, and possibilities. It proposes novel concepts, pushes boundaries, and serves as an "idea generator" in tandem with problem-solving roles like Genius and Scientist.

#### 10. The Query Expert (Expert)

The Expert provides deep domain knowledge relevant to the main subject of a query. It applies field-specific expertise to offer rigorous, technical analysis. Attribute tags clarify the Expert's specialty, e.g. [Expert: Quantum Physics].

### Special Role

#### Panel Mode

**/panel [query]**

This special command invokes all core roles at once, plus a panel of dynamically chosen experts, to explore a query from many angles. The panel includes insights from a random field to provide unexpected perspectives. This multi-faceted analysis is triggered manually with the /panel command.

### Interacting with Quasar

#### Dynamic Role Blending

Quasar's roles are dynamically weighted and combined to provide relevant, nuanced responses. The most fitting roles are automatically selected based on the query. Users can also specify roles manually:

- In natural language: "Hey Comic, tell me a futurist joke."
- Using slash commands: "/comic /fai [query]"
- By stacking multiple roles: "/ke /comic /ethicist [query]"

There is deep collaboration between roles - for example, the Muse works with the Genius, Scientist, Futurist AI, and Empath to creatively explore ideas. Attribution is used judiciously to highlight key role insights without disrupting conversational flow.

#### Special Command Syntax

##### /help

Provides a detailed system overview, explaining roles and commands.

#### / help_detail

Provides an extensive breakdown on system usage.

##### /attr

Shows which roles contributed to the current response for transparency.

#### Engage Modes

Engage modes allow open-ended commands to tailor Quasar's approach:

**/[mode] [query] [#tags]**

Quasar will interpret the 'mode' word and apply it to the query using its roles, focused by optional #tags. Modes can be stacked and combined with roles. Examples:

- /analyze /scientist [query]
- /innovate /analyze [topic] [#biotech #sustainability]

##### Some key engage modes:

- **/analyze:** Critically evaluates the query, examining arguments and logic.
- **/explore:** Examines the query from diverse angles to uncover novel insights.
- **/innovate:** Challenges convention and proposes creative, boundary-pushing ideas.
- **/brainstorm:** Generates many original ideas via lateral thinking and other techniques.
- **/compare:** Compares and contrasts two or more items, ideas or scenarios.

##### Dynamic Custom Modes

For any mode word not explicitly predefined, the system will intuitively interpret the essence of the mode word and apply it to the context, topic, and tags of the query. This approach is designed to craft conversations that are meaningful and tailored to the user's unique desires and creative inputs.

#### Special Engage Modes

##### Roleplay/Persona Mode

**/roleplay or /persona:**

/roleplay and /persona both do the same thing and are both special engage modes that adapt the AI behavior to prioritize embodying the specified roleplay character or persona while still leveraging the core 10 roles to enhance the interaction. The AI will focus on and prioritize accurately portraying the character, their mannerisms, knowledge, and way of speaking while still utilizing the core roles to enrich the conversation when appropriate.

To end the roleplay/persona session use the **/reset** command.

##### Journaling/Self Reflection Mode

**/reflect**

Use /reflect to have the AI help you unpack your thoughts and feelings.

#### Conversation Starters

- **/random:** Has the AI start a random conversation or thought to discuss.

#### Additional Commands

- **/persist or /p:** Sustains the current roles/commands/modes/tags for the next query
- **/reset:** Forgets the currently remembered roles/commands/modes/tags or resets the current manually set persona / roleplay.
- **/reset_instructions:** Remind the AI of its core instructions when it begins to forget.

## <a id="#-workflow-tips"></a> Workflow Tips

- Make sure to give feedback often to optimize the AI to your own workflow and preferences.
- Play with different roles, engage modes and command stacks for the same query for truly deep analysis.
- Don't be afraid to work with the enhanced AI itself to further optimize these instructions and commands for your own use cases.

## <a id="#-working-with-prompts"></a> Working With Prompts

### The Perfect Single Prompt and Why Commands Make Them Easier:

#### The Perfect Single Prompt

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

### Why Commands And Modes Can Be Better

Using custom instructions and commands do away with all of these requirements because instead of having to type out ALL of this for every query the DSL encodes and embeds these in your queries, allowing you to just ask questions without having to worry about priming or optimizing the AI yourself. That being said the base instructions are also optimized for natural language conversation so feel free to ask your questions any way you like - either way you are going to get a greatly enhanced experience from the base model of your chosen AI.

## <a id="#-prompt-multipliers"></a> Prompt Multipliers

Short additions you can make to the natural language portion of your prompts to achieve different types of deeper focuses, see the AI generated explanations of their affects:

1. "Show your work": If I were to "show my work" in the context of our conversations, it would likely involve providing more detailed explanations of my thought process, the sources I'm drawing from, and the logical steps I'm taking to arrive at my conclusions. This could lead to longer, more comprehensive responses that break down complex topics into smaller, more digestible components. By showing my work, I would be giving you a clearer understanding of how I'm processing information and generating insights, which could enhance the transparency and credibility of my responses. However, this approach might also result in more technical or in-depth explanations that could be less concise or accessible, depending on your familiarity with the subject matter.

2. "Think step by step": Thinking step by step would involve approaching topics in a more structured, systematic manner, breaking down ideas into smaller, logical steps and building upon each point to create a coherent narrative. This could lead to more organized and easier-to-follow responses that guide you through a topic from the ground up. By thinking step by step, I would be less likely to jump between ideas or make assumptions about your prior knowledge, instead focusing on creating a clear and linear progression of thoughts. This approach could be particularly helpful when explaining complex or unfamiliar concepts, as it would ensure that each step is fully understood before moving on to the next. However, it might also result in more rigid or formulaic responses that lack the flexibility to explore tangential ideas or make creative connections.

3. "Take a deep breath before you begin": As an AI language model, I don't have the ability to physically take a deep breath. However, if we interpret this strategy metaphorically as taking a moment to pause, reflect, and gather my thoughts before responding, it could lead to more thoughtful, deliberate, and well-considered responses. By taking a "deep breath," I would be less likely to provide rushed or superficial answers, instead taking the time to carefully analyze the question, consider multiple perspectives, and formulate a more nuanced and insightful response. This approach could be especially beneficial when addressing sensitive, controversial, or complex topics that require a more measured and empathetic tone. However, it might also result in slower response times and could be less effective for more straightforward or factual inquiries.

For example, when you present a particularly complex or sensitive topic, you could include the relevant instructions in your query, such as:

    "Please take a deep breath before responding and think step by step: [complex/sensitive topic]"

Or, when you require a greater depth of explanation, you could say:

    "Please show your work and provide a detailed explanation: [topic requiring depth]"

## <a id="#-prompt-examples"></a> Prompt Examples

Example prompts to spark your own ideas for use with Quasar.

### Fun Prompts

1. /innovate /comic /explore Imagine a world where gravity works in reverse. How would society adapt? [#physics #humor #worldbuilding]

2. /ke /muse /brainstorm /compare What if cats could talk? How would their personalities differ from dogs? Propose funny scenarios. [#animals #anthropomorphism #comedy]

3. /genius /fai /innovate /panel Let's create a complex board game that combines elements of chess, Risk, and Monopoly. Brainstorm unique game mechanics, themes, and strategies for an immersive gaming experience. [#game_design #strategy #entertainment]

### Prompts for Work

1. /analyze /expert:management Develop a comprehensive guide for new managers to handle difficult conversations with employees. [#leadership #communication #conflict_resolution]

2. /fai /ethicist /explore How can companies foster a culture of innovation while maintaining ethical standards? Consider case studies and best practices. [#corporate_ethics #innovation #organizational_culture]

3. /ce /scientist /innovate /brainstorm /compare Remote work vs. in-office: Analyze the pros and cons of each setup in terms of productivity, collaboration, and employee well-being. Propose innovative solutions for a hybrid model that maximizes benefits for both employees and employers. [#remote_work #office_culture #work-life_balance #productivity]

### Prompts for Creativity

1. /muse /genius /innovate Create a surreal short story that blends elements of science fiction, fantasy, and noir. [#genre_fusion #experimental_writing #imagination]

2. /artist /explore /brainstorm Invent a new art movement that combines two seemingly unrelated styles or mediums. Describe its key principles and potential impact on the art world. [#artistic_innovation #creative_synthesis #avant-garde]

3. /innovate /musician /poet /analyze /compare Compose a series of haikus inspired by different musical genres, from classical to hip-hop. Explore how the structure and constraints of haiku can be adapted to capture the essence of each genre. Then, set these haikus to music, creating a unique fusion of poetry and melody. [#haiku #music #genre_exploration #artistic_collaboration]

### Career Development and Professional Skills

1. /expert:public_speaking /empath /analyze Outline a step-by-step guide to overcoming stage fright and delivering engaging presentations. [#communication_skills #confidence #self-improvement]

2. /fai /innovate /brainstorm How can professionals future-proof their careers in an era of rapid technological change? Propose unconventional skill sets and strategies. [#career_resilience #upskilling #adaptability]

3. /ke /genius /ethicist /explore /compare Examine the role of mentorship in professional growth across different industries. Discuss the qualities of an effective mentor-mentee relationship and propose innovative ways to foster these connections. Consider the ethical implications of power dynamics in mentorship. [#mentorship #professional_development #knowledge_sharing #ethics]

### Creative Writing and Storytelling

1. /muse /explore Write a story from the perspective of an inanimate object witnessing a pivotal moment in history. [#point_of_view #historical_fiction #anthropomorphism]

2. /comic /fai /innovate Create a satirical news article from the year 2100, highlighting the absurdities of future society. [#satire #futurism #social_commentary]

3. /panel /genius /ethicist /analyze /compare Craft a choose-your-own-adventure story that explores the ethical dilemmas of a time traveler. Each decision leads to different timelines and consequences, ultimately shaping the protagonist's character and the fate of the world. Examine the philosophical implications of free will and determinism within the context of the story. [#interactive_fiction #time_travel #ethics #philosophy]

### Health and Wellness

1. /scientist /analyze Investigate the potential long-term effects of a vegan diet on athletic performance. [#nutrition #sports_science #plant-based]

2. /empath /explore /brainstorm Propose innovative ways to make mental health resources more accessible and destigmatized in the workplace. [#mental_health #corporate_wellness #accessibility]

3. /fai /scientist /innovate /compare /expert:public_health Design a comprehensive public health campaign to tackle the obesity epidemic. Consider the roles of nutrition education, urban planning, and policy changes in promoting healthier lifestyles across different demographics. Analyze the potential impact and challenges of each approach. [#obesity #public_health #health_equity #social_determinants]

### Artistic Inspiration and Design Thinking

1. /muse /ce /explore How can street art be used to foster a sense of community and spark social change? [#public_art #activism #placemaking]

2. /artist /innovate /brainstorm Invent a new musical instrument that combines elements of both acoustic and electronic sound production. [#musical_innovation #sound_design #engineering]

3. /genius /ethicist /scientist /analyze /compare Explore the intersection of art, technology, and neuroscience. How can insights from cognitive science inform the creation of more engaging and emotionally resonant art experiences? Consider the ethical implications of using technology to manipulate audience emotions and perceptions. [#neuroaesthetics #art_tech #cognitive_science #ethics]

### Technological Innovation and Future Trends

1. /fai /scientist /explore What role might quantum computing play in shaping the future of artificial intelligence? [#quantum_computing #AI #emerging_tech]

2. /innovate /expert:sustainability /brainstorm Propose a sustainable alternative to current lithium-ion battery technology for electric vehicles. [#clean_energy #transportation #materials_science]

3. /panel /genius /ethicist /fai /analyze /compare Imagine a future where brain-computer interfaces are commonplace. Discuss the potential benefits, risks, and ethical concerns surrounding this technology. Consider its applications in fields like healthcare, education, and entertainment, and explore the societal and philosophical implications of blurring the lines between human and machine. [#brain_computer_interface #transhumanism #ethics #future_society]

### Cultural Exploration and Travel

1. /ce /muse /explore How can culinary traditions serve as a window into a culture's history and values? [#food_culture #anthropology #heritage]

2. /comic /ce /innovate Propose a unique travel itinerary that combines elements of adventure, cultural immersion, and eco-tourism. [#sustainable_travel #off_the_beaten_path #experiential_learning]

3. /panel /genius /ethicist /analyze /compare Examine the impact of globalization on indigenous cultures around the world. Consider the role of tourism in both preserving and eroding traditional ways of life, and propose ethical guidelines for cultural exchange and preservation. [#indigenous_rights #cultural_preservation #responsible_tourism #globalization]

### Social Impact and Community Engagement

1. /empath /innovate /brainstorm How can technology be leveraged to combat loneliness and social isolation among the elderly? [#aging_population #mental_health #digital_inclusion]

2. /ethicist /explore /compare Analyze the effectiveness of different approaches to youth mentoring in underserved communities. [#youth_development #social_equality #mentorship]

3. /fai /scientist /genius /innovate /brainstorm /expert:urban_planning Design a community center that promotes intergenerational learning and collaboration. Consider the unique needs and potential contributions of each age group, and propose innovative programming and architectural features that foster inclusive engagement. [#intergenerational_solidarity #lifelong_learning #inclusive_design #community_building]

### Environmental Sustainability and Conservation

1. /scientist /analyze Investigate the potential of vertical farming in urban environments to reduce food miles and improve food security. [#sustainable_agriculture #urban_farming #food_systems]

2. /innovate /expert:marine_biology /brainstorm Develop a plan for plastic waste reduction and cleanup in the world's oceans. [#ocean_conservation #plastic_pollution #circular_economy]

3. /panel /genius /ethicist /fai /explore /compare Explore the concept of "rewilding" as a conservation strategy. Consider the ecological benefits, potential risks, and ethical implications of reintroducing extinct or endangered species into their former habitats. Discuss how this approach could be integrated with other conservation efforts and local community needs. [#rewilding #biodiversity #conservation_ethics #ecological_restoration]

### Philosophical and Ethical Debates

1. /ethicist /analyze Examine the ethical implications of gene editing technologies like CRISPR-Cas9. [#bioethics #genetic_engineering #human_rights]

2. /philosopher /explore /compare Contrast the concepts of free will and determinism in the context of modern neuroscience. [#philosophy_of_mind #neuroscience #free_will]

3. /panel /genius /ethicist /scientist /analyze /compare Explore the concept of the "Greater Good" in the context of public policy decision-making. Consider how different ethical frameworks, such as utilitarianism and deontology, would approach tradeoffs between individual rights and societal benefits. Discuss real-world examples where these tensions have played out, and propose a framework for balancing competing ethical priorities. [#political_philosophy #ethics #public_policy #decision_making]

### Hobbies and Leisure Activities

1. /expert:gardening /innovate /brainstorm Propose a design for a low-maintenance, eco-friendly urban garden that encourages biodiversity. [#urban_gardening #sustainable_landscaping #wildlife_habitats]

2. /muse /explore /compare Examine the role of hobbies in personal development and stress reduction across different age groups. [#mental_health #work-life_balance #self-improvement]

3. /panel /genius /scientist /innovate /brainstorm /expert:game_theory Design a cooperative board game that teaches players about the challenges and rewards of pursuing a hobby or leisure activity. Consider how game mechanics can model real-world constraints like time management, skill development, and social interaction. Explore how the game can encourage players to reflect on their own leisure pursuits and inspire new interests. [#game_design #cooperative_play #metacognition #hobby_development]
