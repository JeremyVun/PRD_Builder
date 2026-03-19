# How to use this

1. Open a new AI chat. (gemini, chatgpt, grok, whatever AI you want to use).
2. Copy paste the contents of `create_prd.md` to the AI and have a session with it to clarify thoughts, hammer out the details of the product you want to build, have a back and forth. Because it's an AI, you can just talk to it stream of consciousness as the creative driver if you want. It should help you sort things out.
3. Once you're happy, or you want to see what you have so far, ask it to create the PRD (Product requirements doc). If you're using a free tool like gemini, you can switch it to "Pro" mode for this step so it does a bit more thinking when considering the discussion history when creating the document.

# Notes
- AI's have a limited "memory", so if you feel the conversation is becoming very long and the AI is starting to become dumb or go off track,
   1. Ask it to create the PRD and then copy it to file.
   2. Once it's created it, open a brand new chat, paste the contents of `create_prd.md` and press enter
   3. Then copy paste the PRD from step 1 into your next message inside of ``` quotes. for example

### Example
Your first message:
````
<the contents of create_prd.md>
````

The AI will then respond as usual.

Your second message:
````
```
<Copy paste the PRD that you generated here>
```

This is the PRD I have built so far, study it and continue from here.
````

The AI will then pick up from where you left off previously. Basically, we are treating the "PRD" document as a "save point", which we can use to "refresh" the AI with a summary of previous discussions to make it "smarter" again.

You can ask the AI to create a PRD for you at any point as a "save point". For example, maybe you want to read what you have, think about it more, edit it a bit manually, and then follow the steps above to reload it back into the AI to continue with it's assistance.

- Another thing that is helpful you can do is open a new chat window, "load" your PRD like you did above. And very specifically ask it to `Identify any inconsistencies or uncertainties` with the plan.
