# How to use this

1. Feed the contents of `create_prd.md` to the AI and have a thoughtful session with it to hammer our the details of the product
2. Once you're happy, you can ask it to create the `PRD.md` (Product requirements doc). If you're using a free tool like gemini, you can switch it to "Pro" mode for this step so it thinks a bit more before creating the document for you based on the chat history

# Notes
- AI's have a limited window, so if you feel the conversation is becoming very long and the AI is starting to become dumb,
   1. Ask it to create the PRD and then copy it to file.
   2. Once it's created it, open a brand new chat, paste the contents of `create_prd.md` and press enter
   3. Then copy paste the PRD from step 1 into your next message inside of ``` quotes. for example

   ```
   \```
   <PRD here>
   \```

   This is the PRD I have built so far, study it and continue from here.
   ```

   Basically, we are loading the AI again from a "save point".
