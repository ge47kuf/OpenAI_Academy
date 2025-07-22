# Prompting 101

## conversation vs task - base prompting

- **Conversation**: back-and-forth interaction, often with multiple turns like a chat.

- **Task**: a single, detail specific request or instruction, defined by a clear goal.

## A good prompt

1. context: provide background information or details relevant to the task.
2. instruction: clearly state what you want the model to do, like: translate, summarize, or programme.
3. persona: specify the role or perspective you want AI to be, like: expert, dev, ...
4. output: specify the format or structure of the response, like: JSON, table, links, ...
5. structure using RAW Markdown:
6. examples: provide examples of the desired output or format to guide the model.

```bash
# task
text
## persona
text
## context
text
## output
text
## examples
text
```

### tips

1. ask AI to ask you questions, to get context clearer.
2. use structured formats like JSON or md.
3. use examples to guide the model.
4. ask AI to redo the task: "thank you, please try again with more details".
5. this is a custom GPT that transforms the input into a structured format:
   [https://chatgpt.com/g/g-kXxPg653x-structured-prompt-generator]
