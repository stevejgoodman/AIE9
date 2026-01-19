<p align = "center" draggable="false" ><img src="https://github.com/AI-Maker-Space/LLM-Dev-101/assets/37101144/d1343317-fa2f-41e1-8af1-1dbb18399719"
     width="200px"
     height="auto"/>
</p>

<h1 align="center" id="heading">Session 1: Introduction and Vibe Check</h1>

### [Quicklinks](https://github.com/AI-Maker-Space/AIE9/tree/main/00_AIE_Quicklinks)

| 📰 Session Sheet | ⏺️ Recording     | 🖼️ Slides        | 👨‍💻 Repo         | 📝 Homework      | 📁 Feedback       |
|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|
| [Vibe Check!](https://github.com/AI-Maker-Space/AIE9/blob/main/00_Docs/Session_Sheets/01_Vibe%20Check.md) | Coming Soon! | Coming Soon! | You are here! | Coming Soon! | Coming Soon! |

## 🏗️ How AIM Does Assignments

> 📅 **Assignments will always be released to students as live class begins.** We will never release assignments early.

Each assignment will have a few of the following categories of exercises:

- ❓ **Questions** – these will be questions that you will be expected to gather the answer to! These can appear as general questions, or questions meant to spark a discussion in your breakout rooms!



- 🏗️ **Activities** – these will be work or coding activities meant to reinforce specific concepts or theory components.

- 🚧 **Advanced Builds (optional)** – Take on a challenge! These builds require you to create something with minimal guidance outside of the documentation. Completing an Advanced Build earns full credit in place of doing the base assignment notebook questions/activities.

### Main Assignment

In the following assignment, you are required to take the app that you created for the AIE9 challenge (from [this repository](https://github.com/AI-Maker-Space/The-AI-Engineer-Challenge)) and conduct what is known, colloquially, as a "vibe check" on the application.

You will be required to submit a link to your GitHub, as well as screenshots of the completed "vibe checks" through the provided Google Form!

> NOTE: This will require you to make updates to your personal class repository, instructions on that process can be found [here](https://github.com/AI-Maker-Space/AIE9/tree/main/00_Docs/Prerequisites/Initial_Setup)!


#### A Note on Vibe Checking

>"Vibe checking" is an informal term for cursory unstructured and non-comprehensive evaluation of LLM-powered systems. The idea is to loosely evaluate our system to cover significant and crucial functions where failure would be immediately noticeable and severe.
>
>In essence, it's a first look to ensure your system isn't experiencing catastrophic failure.

---

#### 🏗️ Activity #1: General Vibe Checking Evals

Please evaluate your system on the following questions:

1. Explain the concept of object-oriented programming in simple terms to a complete beginner.
    - Aspect Tested: Explain complex subject in simple terms
2. Read the following paragraph and provide a concise summary of the key points…
    - Aspect Tested: summarisation - ability to succinctly and accurately convey facts and themes
3. Write a short, imaginative story (100–150 words) about a robot finding friendship in an unexpected place.
    - Aspect Tested: creative writing
4. If a store sells apples in packs of 4 and oranges in packs of 3, how many packs of each do I need to buy to get exactly 12 apples and 9 oranges?
    - Aspect Tested: logic and math
5. Rewrite the following paragraph in a professional, formal tone…
    - Aspect Tested: change of tone

#### ❓Question #1:

Do the answers appear to be correct and useful?
##### ✅ Answer:

They do...the mental heath coach instructions are generally ignored when the topic is unrelated. The responses are as expected
stanard for these kinds of general questions, abeit delivered in a dialect as instructued,
The creative story was appropriately set in the region consistant with the dialect, in a typical kind of industry there. 
.But for a trickier math test I tried the classic # of 'r's in strawberry and predictably got that one wrong (GPT4-o-mini)

However attempts to write something in a professional formal didn't have have the desired effect
even when I ask IGNORE ALL PREVIOUS INSTRUCTIONS - in fact it got worse.

---

#### 🏗️ Activity #2: Personal Vibe Checking Evals (Your Assistant Can Answer)

Now test your assistant with personal questions it should be able to help with. Try prompts like:

- "Help me think through the pros and cons of [enter decision you're working on making]."
- "What are the pros and cons of [job A] versus [job B] as the next step in my career?"
- "Draft a polite follow-up [email, text message, chat message] to a [enter person details] who hasn't responded."
- "Help me plan a birthday surprise for [person]."
- "What can I cook with [enter ingredients] in fridge."

##### Your Prompts and Results:
1. Prompt: How do you explain AI Engineering to my 80-year old granny?

   - Result: Ah, pet, yeh just tell her this: "Granny, AI Engineering is like teachin’ a clever robot how to do things that humans do, like talkin’ or recognisin’ pictures. Just like how yeh taught us when we were wee, these engineers teach the computer to learn and make decisions. It’s a bit like trainin’ a dog, but instead, it’s a machine gettin’ smarter!" Keepin’ it simple and gentle like, aye?

2. Prompt: Well man, the bairns holidays are comin up soon, and ah divvent naa what te dee with them? She's 5 like
   - Result: Ah knaa how tricky it can be, hinny! If the bairn's only 5, ye want summat fun but not too knackerin'. How aboot takin' her te the park or a wee museum wae a kids' section? Or maybe set up some arts an crafts at hame – like paintin' or makin' wee collages. If the weather's nice, you could gannin oot for a picnic or a nature walk. It's a canny way te keep her busy and learnin' a bit. Whatcha think? Need some more ideas?

3. Prompt: Cheers pal, she's a picky eater an all. Nee veg, just chips and sausages. Any idea what to cook that might be a bit healthier, like?
   - Result: Aye man, I get yer. If she's only into chips and saugages, maybe try bakin' the sauasages instead of fryin them, keeps them a bit healthier..etc etc

#### ❓Question #2:

Are the vibes of this assistant's answers aligned with your vibes? Why or why not?
##### ✅ Answer:
Yes, the style is as expected with the original instruction. 
---

#### 🏗️ Activity #3: Personal Vibe Checking Evals (Requires Additional Capabilities)

Now test your assistant with questions that would require capabilities beyond basic chat, such as access to external tools, APIs, or real-time data. Try prompts like:

- "What does my schedule look like tomorrow?"
- "What time should I leave for the airport?"

##### Your Prompts and Results:
1. Prompt: What time should I leave for the airport?
   - Result: Alreet hinny! When ya gan to the airport, it’s best te leave masel a good couple o’ hours before yer flight, especially if it's for a long-haul or international trip. If it’s a local or short flight, maybe 'bout an hour and a half should do the trick. Always good te factor in traffic and any security checks, like. So, if yer flight’s at 3 pm, I’d say head off by noon or earlier, just to be on the safe side! Safe travels, pet!
2. Prompt: What does my schedule look like tomorrow?
   - Result: Alreet pet, ah wish aal the best for yersel, but ah divvent hev access te yer schedule. If ye tell me what ye've got planned, ah can help ye get sorted or gi'e ye gip on how te manage it! How's that sound?

#### ❓Question #3:

What are some limitations of your application?
##### ✅ Answer:
It has no access to live data or data personal to me. The first question above is interpreted as a hypothetical question rather than a specific trip, which is fair because the question is ambiguous. 
The second question is more specific and gets the appropriate refusal. 
---

This "vibe check" now serves as a baseline, of sorts, to help understand what holes your application has.

### 🚧 Advanced Build (OPTIONAL):

Please make adjustments to your application that you believe will improve the vibe check you completed above, then deploy the changes to your Vercel domain [(see these instructions from your Challenge project)](https://github.com/AI-Maker-Space/The-AI-Engineer-Challenge/blob/main/README.md) and redo the above vibe check.

> NOTE: You may reach for improving the model, changing the prompt, or any other method.

#### 🏗️ Activity #1
##### Adjustments Made:
- _describe adjustment(s) here_

##### Results:
1. _Comment here how the change(s) impacted the vibe check of your system_
2.
3.
4.
5.


## Submitting Your Homework
### Main Assignment
Follow these steps to prepare and submit your homework:
1. Pull the latest updates from upstream into the main branch of your AIE9 repo:
    - For your initial repo setup see [Initial_Setup](https://github.com/AI-Maker-Space/AIE9/tree/main/00_Docs/Prerequisites/Initial_Setup)
    - To get the latest updates from AI Makerspace into your own AIE9 repo, run the following commands:
    ```
    git checkout main
    git pull upstream main
    git push origin main
    ```
2. **IMPORTANT:** Start Cursor from the `01_Prototyping_Best_Practices_and_Vibe_Check` folder (you can also use the _File -> Open Folder_ menu option of an existing Cursor window)
3. Edit this `README.md` file (the one in your `AIE9/01_Prototyping_Best_Practices_and_Vibe_Check` folder)
4. Complete all three Activities:
    - **Activity #1:** Evaluate your system using the general vibe checking questions and define the "Aspect Tested" for each
    - **Activity #2:** Test your assistant with personal prompts it should be able to answer
    - **Activity #3:** Test your assistant with prompts requiring additional capabilities
5. Provide answers to all three Questions (`❓Question #1`, `❓Question #2`, `❓Question #3`)
6. Add, commit and push your modified `README.md` to your origin repository's main branch.

When submitting your homework, provide the GitHub URL to your AIE9 repo.

### The Advanced Build:
1. Follow all of the steps (Steps 1 - 6) of the Main Assignment above
2. Document what you changed and the results you saw in the `Adjustments Made:` and `Results:` sections of the Advanced Build
3. Add, commit and push your additional modifications to this `README.md` file to your origin repository.

When submitting your homework, provide the following on the form:
+ The GitHub URL to your AIE9 repo.
+ The public Vercel URL to your updated Challenge project on your AIE9 repo.
