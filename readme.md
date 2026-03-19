# How to use this

1. Open a new AI chat. (gemini, chatgpt, grok, whatever AI you want to use).
2. Copy paste the contents of `create_prd.md` to the AI and have a session with it to clarify thoughts, hammer out the details of the product you want to build, have a back and forth. Because it's an AI, you can just talk to it stream of consciousness as the creative driver if you want. It should help you sort things out.
3. Don't be afraid to ask it questions if you don't understand what it's asking of you.
4. Once you're happy, or you want to see what you have so far, ask it to create the PRD (Product requirements doc). If you're using a free tool like gemini, you can switch it to "Pro" mode for this step so it does a bit more thinking when considering the discussion history when creating the document.

# Notes
- AI's have a limited "memory". If a conversation goes for a long time, you might notice it starts forgetting things, becoming a bit dumb, or going off track. So if you ever suspect that happening you can follow the steps below to make it "smart" again.
   1. Ask it to create the PRD and then copy paste it to a file somewhere.
   2. Open a brand new AI chat, paste the contents of `create_prd.md` and press enter
   3. Copy paste the PRD from step 1 into your next message inside of ``` quotes. for example,

### how to reload your progress into a new AI chat window
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

The AI will then pick up from where you left off previously. Basically, we are treating the "PRD" document as a "save point". Because the PRD is a distillation of a set of discussion history, you can use it to essentially "refresh" a new AI chat with the context of where you were up to before.

You can ask the AI to create a PRD for you at any point as a "save point". For example, maybe you want to read what you have, think about it more, edit it a bit manually, and then follow the steps above to reload it back into the AI to continue with it's assistance.

- Another thing that is helpful you can do is open a new chat window, "load" your PRD like you did above. And very specifically ask it to `Identify any inconsistencies or uncertainties` with the plan.
