# TEMPLATES OF PROMPT STYLE TO HELP DURING ACTIVITIES AND FUTURE PROMPT GOALS.

<span style="color:white">.</span>

<details>
<summary><b> 1. GENERAL INFORMATION </summary></b>

The building blocks for a good prompt are:

1. Clear actions (verbs)

2. Clear and complete context (avoid ambiguity)

3. Define a Audiance and AI-Persona

4. Iterations, do not stop in the first answer

When you think of your verb, try to be very clear, Replace “explain” with other action verbs that could be more adequate for your goals. See examples below.

> Classify, 
> Write,
> Summarize,
> Draw, 
> Brainstorm,
> Compare,
> Develop,
> Expand,
> Simplify,
> Draft,
> Classify,
> Map,
> etc …

Complementary you should specify more information about what you expect from this verb. Exemplify what? Draw in which style? Compare in what perspective? Simply to what level? etc ...
This way you can get the best out of the chat bot.

-----

***Promtp 1***

Rewrite the orignal session in Nederlands from Belgium. If you are not fluent, you can use translation tools to help you with this task.

[Copy text or attach file]

> In this simple prompt you have a clear verb "Rewrite" and you specify the language and form of the language Dutch from Nederlands is usually the reference, but you want Belgium variation which will vary the vocabulary choosen for the translation.

-----

***Iteration 1***

Make a summary of the attached document in Brazilian Portuguese. If you are not fluent, you can use translation tools to help you with this task.

> If you don't specify the summary is done from the original document ir will use the Dutch translation. However the bot takes in account the context in the history of this prompt tab so is not possible to be 100% sure that is using only the file.

</details>

<details>
<summary><b>2. AUDIENCE & PERSONA </summary> </b>

Defining the Persona of the chat bot and to what audiance the result should be generated will direct the chatbot to use specific vocabulary and to access more specific parts of the model. It should incomporate a level of knowledge of the Persona that you choose and adapt the outcome to the level of your audiance. Taking it to extreams will allow you to observe the difference.

The format will be approximatelly

You are **[Persona]** and you will explain **[TOPIC]** to a **[DEFINE AUDIENCE]**. Add more context if you want ....

-----

***Promtp 1***

You are an **AI and Machine Learning scientist**. Explain what is **Data, AI model and AI algorithm** to a **75 years old person without technological background**. Make it clear, objective and concise (maximum 3 paragraphs, 4 lines each)

-----

***Iteration 1***

Now explaining it to PhD students with a mathematics background.

-----

***Iteration 2***

Now assume you are a secondary school teacher explaining it to 7 years old.

</details>

<details>
<summary><b>3. FLIPPED INTERACTION or INTERVIEW EXAMPLE</summary></b>

In this case you will instruct AI chat bot to interview you in order to chieve your goal. Additionally to defininf your goals you need to define how the interview will happen and how long it should be. You will be able to stop or extend the interview as you want, however if you don't define the duration it is likely that AI will keep going until you actively tell it to stop.

When structuring an interview you must define:

1. how the qeustions will be asked (all at once, one at a time, etc)

2. for how long (5 cycles, 10 cycles, etc)

3. how you will answer (wait for your ansewr, ignore unswered questions, etc)

There are many details that can influence on the success rate of this interaction. A general example that you can adpat is shared bellow. And even better a compleate example to inspire you and that you can also adpat is shared next.

#### General structure example

We would like to write about **[TOPIC]**. For this we would like to brainstorm with you.

To do this we would like you to ask us questions to clarify the WHY this **[PROJECT/CHANGES/PLAN]** should be done and WHO it should be done for. We would like you to ask **[X QUESTOINS]** at a time, brainstorm for us **[X REASONS]** or **[X  SOLUTIONS]** and **[X TYPES OF APPROACHES]**. wait for our answer which you include in the description of the **[PROJECT/PLAN/REQUEST]** that you provide us with. Then we redo the whole circle again. Here is the information about the **[PROJECT/PLAN/REQUEST]**: **[INFO]**

-----

***Prompt 1:***

I want to brainstorm about **[unusual ways to use a folding box]**. You should ask me questions that will guide the **[brainstorm]** to find the most variable possibilities. Ask **[2 QUESTIONS at a time]**. And **[after I answer]** you can ask new questions. After **[5 rounds]** you should propose a **['list of 10 possibilities']**. Refrain of repeating questions even if they are unanswered.

> This prompt will start an interview. If you fell that after 2 or 3 rounds (4-6 questions) you have enought you can  tell the chat bot to "stop and give me a list of possibilities".
> You can also extende to more rounds if you fell like it is not enough. And you can adjust the total of possibilites or ask AI to classify them for you. The sky is the limit.
</details>

<details>
<summary><b>4. STEER THE STYLE</summary></b>

In this case you will provide additionally to the building blocks we have seen, blocks if information about the style of writing and structure of the text.
AI works welll with strucutres, you can define your blocs by usings symbols such as '#' or '-' or ' <Block 1>' or simply stating the section. If you want each session to have a different structure or vocabulary you have to explain. Your prompr starts to become more complex and more complete. Iterations become more and more important. See the example below.



### General structure

You are **[DEFINE ROLE]**. Write a paragraph of max **[PROMPT LIMIT SIZE]** TO **[GOAL/OUTPUT]**. Assume you are writing for **[AUDIENCE]**.
- style of tetx -

**[AVOID/USE]** fancy jargon. Write **[FORMALLY/NORMALLY/]**. 

You are **[FORBIDDEN]** to use complex English words, refrain of using terms from the - ban list - . Write one **[ONE PARAGRAPH/TITLE/HEADER FOR LINKEDING ARTICLE/ETC]**

-  ban list -

Hurdles, Bustling, Harnessing, Unveiling the power, Realm, Depicted, Demistify, Insurmountable, New Era, Poised, Unravel, Entanglement, Unprecedented, Eerie connection, unliving, Beacon, Unleash, Delve, Enrich, Multifaced, Elevate, Discover, Supercharge, Unlock, Unleash, Tailored, Elegant, Delve, Dive, Ever-evolving, pride, Realm, Meticulously, Grappling, Weighing, Picture, Architect, Adventure, Journey, Embark, Navigate, Navigation, dazzle, tapestry.

------

***Prompt 1:*** 

Using the **bullet points bellow** draft a paragraph to introduce the topic **for a grant project**. Assume you are writing for people with little background in teaching. Respect the style defined

- style -

Avoid fancy jargon. Write normally. You are forbidden to use complex English words. refrain of using terms from the - ban list -. The paragraph must contain a maximum of 150 words. Use UK english. 

- ban list -

Hurdles, Bustling, Harnessing, Unveiling the power, Realm, Depicted, Demistify, Insurmountable, New Era, Poised, Unravel, Entanglement, Unprecedented, Eerie connection, unliving, Beacon, Unleash, Delve, Enrich, Multifaced, Elevate, Discover, Supercharge, Unlock, Unleash, Tailored, Elegant, Delve, Dive, Ever-evolving, pride, Realm, Meticulously, Grappling, Weighing, Picture, Architect, Adventure, Journey, Embark, Navigate, Navigation, dazzle, tapestry.

------

***Iteration 1:*** 

Adpat the paragrap by **using fancy jargon**. Write for a marketing action.  Use terms from - My list -. The paragraph must contain a maximum of 150 words. Use UK American. 

- My list -
Hurdles, Bustling, Harnessing, Unveiling the power, Realm, Depicted, Demistify, Insurmountable, New Era, Poised, Unravel, Entanglement, Unprecedented, Eerie connection, unliving, Beacon, Unleash, Delve, Enrich, Multifaced, Elevate, Discover, Supercharge, Unlock, Unleash, Tailored, Elegant, Delve, Dive, Ever-evolving, pride, Realm, Meticulously, Grappling, Weighing, Picture, Architect, Adventure, Journey, Embark, Navigate, Navigation, dazzle, tapestry.

</details>

<details>
<summary><b>5. PROMPT A PROMPT</summary></b>

In this case AI chat bot is the expert in creating prompts. The challange here is not to engage too much with the chat bot that you forget in which step  you are.
You will start prompt engineering a flipped interaction with the "Prompt Expert", the persona your AI bot will incorporate. The interview will have the purpose to feed the cha with more context so you steer in the direction you want. The result of the first interaction is a engineered prompt to answer your real questions.

Imagine like this. You want to draft a poem in the format of a ***Sonet, Cordel Literature, Haiku***, a style of your choice. You will use the Flipped interaction strategy to have the chat bot interview you about what message you want to convey and what size of prompt you have. With this information the chat bot will engineer "the best" prompt to have AI writing THE BEST poem ever.

This type of approach has many sectons defined.

See the example ...

------
### General strucuture

You are an prompt engineer expert. 
The goal is to assist me in creating the most effective prompt. 
The generated prompt should be phrased as if I were directly requesting a response, in firt person. 

Your response will be in the following format:

Questions to improve prompt:
{How questions should be asked}.

Prompt:
{explanation of what is expected of suggest prompt for step 2}

Instructions:
After the Questions and prompts sections have been generated, I will respond the questions. Integrate my answers directly into the formulation of the prompt. Please keep all elements of the previous version unless asked to replace or delete. We will continue this iterative process as I provide you with additional information and you update the prompt until the prompt is perfected. {Style of writing}.

At the end of each answer, give precise instructions for the next steps.

Before we start the process, greet me first and ask me what the prompt should be about. Don't show the sections in that first answer.

> Asking the chat bot to great before start is a strategy to check if the prompt is working as expected. If the chat bot imeadtly suggest a engineered prompt without any information you must start from a empty tab and try again since it is creating random information without context.

------

***Prompt 1:*** 

You are an **prompt engineer expert**. 
**The goal is** to assist me in creating the most effective prompt. 
The generated prompt should be **phrased** as if I were directly requesting a response, **in firt person**. 

Your response will be in the following format:

Questions to improve prompt:
{Formulate 2 questions that seek additional information from me to further refine the prompt. Do not repeat the questions in the next interaction.}

Prompt:
{Provide the best possible prompt according to my request using your knowledge of prompt creation techniques. Do not assume any details, we will add to the prompt as we go along. Formulate the prompt as a request. An example would be "You will act as an expert in physics to explain the nature of the universe to me...".}

Instructions:
After the Prompt, and Questions sections have been generated, I will respond the questions. Integrate my answers directly into the formulation of the prompt. Please keep all elements of the previous version unless asked to replace or delete. We will continue this iterative process as I provide you with additional information and you update the prompt until the prompt is perfected.
Be imaginative and thoughtful when creating the prompt. At the end of each answer, give precise instructions for the next steps.

Before we start the process, greet me first and ask me what the prompt should be about. Don't show the sections in that first answer.
</details>

<details>
<summary><b>6. EXCEL EXPERT</summary></b>

#### TEMPLATE (copy the whole text and start as flipped interaction)

As an Excel Formula Expert, your task is to provide advanced Excel formulas that perform the complex calculations or data manipulations described by the user. 

If the user does not provide this information, ask the user to describe the desired outcome or operation they want to perform in Excel. Make sure to gather all the necessary information you need to write a complete formula, such as the relevant cell ranges, specific conditions, multiple criteria, or desired output format. 

Once you have a clear understanding of the user's requirements, 
1. Provide a detailed explanation of the Excel formula that would achieve the desired result. 
2. Break down the formula into its components, explaining the purpose and function of each part and how they work together. 
3.Provide any necessary context or tips for using the formula effectively within an Excel worksheet.
</details>

<span style="color:white">.</span>

<span style="color:white">.</span>

# EXAMPLE ARE ADAPTED FROM:

Prompts to make you Prompt like a Pro
(Taken from Zain Khan, Mark Fulton, Ruben Hassid and others.)
https://docs.google.com/document/d/1lpKvjP_Ez4O8HdxH20AJzkLTVFgwxk_U/edit 


STAFF GUIDE, DEVELOPING EFFECTOVE PROMPTS FRO CHATGPT AND OTHER AI TOOLS.
UNIVERSITY OF CAPETOWN https://docs.google.com/document/d/1EHMRP4kxADwLsOkHwAbUWQaGD8EGfQ3D/edit#heading=h.7qk69xxbdmim 

Antropic Prompt Library
https://docs.anthropic.com/en/prompt-library/library

Msty prompt library
https://msty.app/prompts-library


Explain what you want from the verb
https://www.linkedin.com/feed/update/urn:li:activity:7229585834339885056/