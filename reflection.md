# Reflection

This document follows the required structure from the project guidelines.

## Part A: AI Grading Reflection

### A1. AI Model 1 Summary

ChatGPT, GPT-5.6, run by Mohammed Faizan on 11 August 2026. Full prompt and response in ai-evaluation/ai-model-1.md.

Suggested grade: 76 out of 100. Content and Presentation 21, GitHub Collaboration 22, AI Evaluation Setup 13, Reflection Quality 20.

Strengths it named: the topic choice, which it called genuinely new and socially relevant; the GitHub workflow, which it said did not look like two people dumping files at the end; and the fact that our research notes had already spotted the biggest accuracy trap by warning that this is not a ban on ordinary chatbots.

What it said to improve: finish the two AI evaluations, finish the reflection, and fix three specific pieces of wording. It checked our claims against the Chinese text rather than English coverage and cited article numbers. It said "the first rulebook anywhere" was too absolute, that "block virtual relationships for minors entirely" was too broad because Article 14 bans virtual partners and virtual relatives for minors rather than all anthropomorphic services, and that "no training on user data without consent" was too simple because the rule is specifically about sensitive personal information and has legal exceptions. It also pointed out that Article 16 already requires providers to let users copy and delete their interaction data, which matters because our discussion question is about exactly that.

### A2. AI Model 2 Summary

Google Gemini, Flash, run on 12 August 2026. Full prompt and response in ai-evaluation/ai-model-2.md.

Suggested grade: 88 out of 100. Content and Presentation 22, GitHub Collaboration 23, AI Evaluation Setup 22, Reflection Quality 21.

Strengths it named: the topic, the plain language, the README structure, and the commit history across branches.

What it said to improve: tighten the video runtime, make the discussion question more explicitly ethical, use Issues and pull request reviews more fully, and add peer responses on the Discussion board.

### A3. Comparison

The two models agreed almost exactly on the halves of the project that were finished and disagreed by nine points on the half that was not.

On Content and Presentation they were one point apart, 21 against 22. On GitHub Collaboration they were one point apart, 22 against 23. Both picked the topic as the strongest thing we did.

On AI Evaluation Setup they were nine points apart, 13 against 22, and that gap is the whole story. ChatGPT opened by saying it would grade what was actually visible in the repository rather than give credit for material the README promised. It then found that ai-evaluation contained only ai-model-1.md, that the file still had [PASTE THE COMPLETE, UNEDITED RESPONSE HERE] in it, and that the prompt still had [PASTE YOUR REPO LINK] and [PASTE YOUR YOUTUBE LINK]. It scored the category on that evidence.

Gemini did not do that. It gave us 22 out of 25 and wrote that we had "prompts saved cleanly alongside complete output logs from two distinct LLMs." At the moment it was asked, ai-model-2.md did not exist and ai-model-1.md was still a template. It also credited us with a "direct comparison of the point variance between the two AI models" and a "clear stance on which AI grade the team felt was fairer", when Part A of this reflection was still a list of unanswered prompts. It went further and described a disagreement between two models about whether concise phrasing showed lack of depth. That exchange never happened. It then advised us to add peer responses on the Discussion board, which we had already done.

The difference in sourcing is just as clear. ChatGPT worked from the Chinese regulation and cited Articles 2, 13, 14, 16 and 18. Gemini cited Wikipedia and a finance blog and did not correct any of our specific wording.

So ChatGPT gave us the more useful feedback by a wide margin, and it did so while giving us the lower grade. Gemini was more pleasant to read and less trustworthy.

### A4. Do You Agree With the AI's Grade?

We agree with ChatGPT's 76 for the state the project was in when it was graded, and we do not agree with Gemini's 88.

ChatGPT's marks are defensible line by line. Two required deliverables genuinely were missing, and it said so and priced it. The 13 out of 25 on AI Evaluation Setup was correct at the time even though it stung, because the folder really did contain a placeholder file claiming to be an evaluation.

Gemini's 88 is the higher number and the less honest one. It did not check whether the things it was praising existed. If we had only run Gemini we would have gone to bed thinking the project was close to finished, and it was not.

The thing that surprised us most was not either grade. It was that the model which flattered us was the one that made things up, and that the two were nine points apart on the single category where the truth was easiest to verify by opening a folder.

What ChatGPT got wrong: not much, but it did assume the reflection was untouched when Part B was already written, and it could not open the video, which it said plainly instead of guessing. Gemini also could not open the video and did not say so.

### A5. What Would You Do Differently?

We would fix the three wording problems ChatGPT identified. "First rulebook anywhere" is a global claim we cannot support from law firm summaries. "Block virtual relationships for minors entirely" overstates Article 14. "No training on user data without consent" flattens a rule that is really about sensitive personal information and has exceptions. All three came from us making a real regulation sound tidier than it is, which is the same failure we describe in Part B.

We would also run the AI evaluations earlier. Doing them last meant our own evaluation files were the weakest evidence in the repository at the exact moment the models were reading it, and both models docked us for it.

What we would not change is the discussion question. Gemini told us to rewrite it as something like "Should governments limit AI emotional companions to prevent addiction, or does this restrict personal freedom?" We think that is a worse question. It is a two sided prompt with an obvious shape, and ChatGPT specifically praised ours for not being generic. We are keeping ours.

We are also not adding the extra prompt criteria Gemini suggested, because its own answer is the evidence that a more elaborate prompt does not produce a more careful reader.

## Part B: AI Research Assistance Reflection

### B1. How You Used AI During Research

We used Claude for most of the working side of this project. It read the assignment guidelines and pulled out the requirements that were easy to miss, like the video needing to be set to public and all collaboration needing to happen on GitHub rather than in our group chat. It also helped set up the repository structure, drafted the first version of the README from our research notes, and created the issues we used to track who was doing what.

GitHub Copilot reviewed our pull requests automatically and left comments on formatting and wording, some of which we committed.

ChatGPT and Gemini were used only at the end, to grade the finished project.

### B2. What Worked Well

The most useful thing was having AI read the full assignment page and turn it into a concrete list of what still needed doing. The guidelines are long and it is easy to skim past a requirement. Getting back a set of issues we could assign to each other meant we did not find out at the end that we had missed something like the Discussion board requirement.

### B3. What Did Not Work Well

The clearest example was on the regulation itself. There is no official English translation of the Interim Measures, so every English description of it is somebody's interpretation of the Chinese text. That meant we could not treat any AI summary of what the law requires as fact, and had to attribute those points to law firm summaries instead. We also had to be careful with the figure of 345 million monthly users for Doubao, because that is a company disclosure covering the whole app rather than an independently verified count of people who lost a companion feature.

AI also overstated how certain it was about a requirement. It told us the rubric required both of us to appear on camera. When we checked the guidelines ourselves, it turned out to be genuinely ambiguous. The presentation style section allows slides with voiceover as a format, but the Excellent band of the rubric says all team members "appear and speak". Two parts of the same document pull in different directions, and the AI presented one reading as settled fact rather than flagging the conflict. We ended up asking rather than assuming, which is what we should have done first.

The grading step produced the sharpest example of all. Gemini credited us with two completed AI evaluations and a finished comparison at a moment when neither existed, and invented a specific disagreement between two models to illustrate a point. It was not being lazy in a way we could see. It was confident, specific and wrong, and it was wrong in the direction that made us look good. Details are in A3.

### B4. Overall Reflection

Using AI changed the shape of the work more than the amount of it. It handled the organising, the formatting, and the first drafts, which meant the time we actually spent went into deciding what the story was and checking whether the claims held up. That checking turned out to be the real work.

What we would keep is using AI to break a large assignment into tracked pieces. What we would watch more closely is accepting confident sounding detail without going back to the source, especially on a topic where the primary document is in another language and every English version of it is an interpretation.

The lesson we did not expect is that you cannot tell how careful a model has been from how the answer reads. Gemini's response was better organised and more encouraging than ChatGPT's and it was the one that had checked less. The only way we caught it was by knowing what was actually in our own repository. If we had been less familiar with our own work, the wrong answer is the one we would have believed.
