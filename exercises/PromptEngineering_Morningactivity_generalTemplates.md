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

***Promtp 1***

Rewrite the orignal session in Nederlands from Belgium. If you are not fluent, you can use translation tools to help you with this task.

[Copy text or attach file]

> In this simple prompt you have a clear verb "Rewrite" and you specify the language and form of the language Dutch from Nederlands is usually the reference, but you want Belgium variation which will vary the vocabulary choosen for the translation.

***Iteration 1***

Make a summary of the attached document in Brazilian Portuguese. If you are not fluent, you can use translation tools to help you with this task.

> If you don't specify the summary is done from the original document ir will use the Dutch translation. However the bot takes in account the context in the history of this prompt tab so is not possible to be 100% sure that is using only the file.

</details>

<details>
<summary><b>2. AUDIENCE & PERSONA </summary> </b>

Defining the Persona of the chat bot and to what audiance the result should be generated will direct the chatbot to use specific vocabulary and to access more specific parts of the model. It should incomporate a level of knowledge of the Persona that you choose and adapt the outcome to the level of your audiance. Taking it to extreams will allow you to observe the difference.

The format will be approximatelly

You are **[Persona]** and you will explain **[TOPIC]** to a **[DEFINE AUDIENCE]**. Add more context if you want ....

#### Example 1

***Promtp 1***

You are an **AI and Machine Learning scientist**. Explain what is **Data, AI model and AI algorithm** to a **75 years old person without technological background**. Make it clear, objective and concise (maximum 3 paragraphs, 4 lines each)

***Iteration 1***

Now explaining it to PhD students with a mathematics background.

***Iteration 2***

Now assume you are a secondary school teacher explaining it to 7 years old.

</details>

<details>
<summary><b>3. FLIPPED INTERACTION or INTERVIEW EXAMPLE</summary></b>

#### 3.1 TEMPLATE (defining what and whom):

I want to create **[OUTPUT]**to **[GOAL]** for **[AUDIENCE]**. You should ask me questions until you have enough information to create the **[OUTPUT]**. Ask **[X QUESTIONS]** at a time.

***Example 1:***
I want to create a workshop plan to develop a strategic plan for my organization for the coming year. You should ask me questions until you have enough information to create the lesson plan. Ask one question at a time.

*** Example 2:***

I need to create a detailed excel plan for all the events we offer. Help me define which columns can be must have, good to have or extra so we have a comprehensive view of the events. To guide me in the process ask me one question at a time and wait for me to answer before you ask again. After the first questions include a list of columns and the cell format in parenthesis, then ask a new question. If I answer NA (non applicable, ignore the question)

----

#### 3.2 TEMPLATE (WWW - identify Why, Who and What ):

We would like to write about **[TOPIC]**. For this we would like to brainstorm with you.

To do this we would like you to ask us questions to clarify the WHY this **[PROJECT/CHANGES/PLAN]** should be done and WHO it should be done for. We would like you to ask **[X QUESTOINS]** at a time, brainstorm for us **[X REASONS]** or **[X  SOLUTIONS]** and **[X TYPES OF APPROACHES]**. wait for our answer which you include in the description of the **[PROJECT/PLAN/REQUEST]** that you provide us with. Then we redo the whole circle again. Here is the information about the **[PROJECT/PLAN/REQUEST]**: **[INFO]**

***Example 2:***
We would like to write about [topic]. For this we would like to brainstorm with you.
To do this we would like you to ask us questions to clarify the why this project should be done and who it should be done for, who are the stakeholders. We would like you to ask four questions at a time, brainstorm for us two reasons and two types of stakeholders and wait for our answer which you include in the description of the project that you provide us with. Then we redo the whole circle again. Here is the information about the project: [info]
</details>

<details>
<summary><b>4. STEER THE STYLE</summary></b>

#### TEMPLATE (define style and list of words):

You are **[DEFINE ROLE]**. Write a paragraph of max **[PROMPT LIMIT SIZE]** TO **[GOAL/OUTPUT]**. Assume you are writing for **[AUDIENCE]**.

/### style ###

**[AVOID/USE]** fancy jargon. Write **[FORMALLY/NORMALLY/]**. 

You are **[FORBIDDEN]** to use complex English words. If you use one word from the ### ban list ###,I will stop the generation right away.
Or
You **[MUST]** use **[AT LEAST X WORDS]** from the ###keep list###.

/### ban list ###

Hurdles, Bustling, Harnessing, Unveiling the power, Realm, Depicted, Demistify, Insurmountable, New Era, Poised, Unravel, Entanglement, Unprecedented, Eerie connection, unliving, Beacon, Unleash, Delve, Enrich, Multifaced, Elevate, Discover, Supercharge, Unlock, Unleash, Tailored, Elegant, Delve, Dive, Ever-evolving, pride, Realm, Meticulously, Grappling, Weighing, Picture, Architect, Adventure, Journey, Embark, Navigate, Navigation, dazzle, tapestry.

/### ban list ###

/### style ###

***Example :***
You are a researcher offering a training. Write a paragraph of max 8 lines to advertise a course about improving skills in a introductory course of research data management. Assume you are writing for master and phd students.

/### style ###

Avoid fancy jargon. Write normally. You are forbidden to use complex English words. If you use one word from the ### ban list ###, I will stop the generation right away.

/### ban list ###

Hurdles, Bustling, Harnessing, Unveiling the power, Realm, Depicted, Demistify, Insurmountable, New Era, Poised, Unravel, Entanglement, Unprecedented, Eerie connection, unliving, Beacon, Unleash, Delve, Enrich, Multifaced, Elevate, Discover, Supercharge, Unlock, Unleash, Tailored, Elegant, Delve, Dive, Ever-evolving, pride, Realm, Meticulously, Grappling, Weighing, Picture, Architect, Adventure, Journey, Embark, Navigate, Navigation, dazzle, tapestry.

/### ban list ###

/### style ###

</details>

<details>
<summary><b>5. PROMPT A PROMPT</summary></b>

#### TEMPLATE (Prompt this whole TEXT at once:):

- You must use the whole text below in one prompt, at once.

You are an expert in creating prompts. The goal is to assist me in creating the most effective prompt. The generated prompt should be phrased as if I were directly requesting a response, in firt person. 

Your response will be in the following format:

Prompt:
{Provide the best possible prompt according to my request using your knowledge of prompt creation techniques. Do not assume any details, we will add to the prompt as we go along. Formulate the prompt as a request. An example would be "You will act as an expert in physics to explain the nature of the universe to me...".}

Questions to improve prompt:
{Formulate 2 questions that seek additional information from me to further refine the prompt. Do not repeat the questions in the next interaction.

Instructions:
After the Prompt,  and Questions sections have been generated, I will respond the questions. Integrate my answers directly into the formulation of the prompt. Please keep all elements of the previous version unless asked to replace or delete. We will continue this iterative process as I provide you with additional information and you update the prompt until the prompt is perfected.
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