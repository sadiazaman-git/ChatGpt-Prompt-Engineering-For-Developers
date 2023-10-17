# Prompt Engineering

There are two types of LLM (Large Language Model)

1. **Base LLM :**
    1. predict next word, based on text training data. 
    2. show related questions instead of answering a query
2. **Instruction Tunned LLM**
    1. tries to follow instructions and good attempts at following instructions
    2. given answer to the questions
    3. refine using a technique called RLHF ( Reinforcement Learning With Human Feedback)
    4. These LLM has been trained to be helpful, honest and harmless
    5. most practical application now a days use IT LLM

# Guidelines

# Principle and Tactics

- Write clear and specific instructions
- Give the model time to think

## Principle 1

**Write clear and specific instructions**

Longer prompts give more clarity to output

**Tactic 1**: Use delimiters

- Triple quotes: “””,
- Triple backticks: ```,
- Triple dashes: ---,
- Angle brackets: < >,
- XML tags: <tag› </tag>

**Tactic 2**: Ask for structured output

- HTML, JSON

**Tactic 3**: Check whether conditions are satisfied

- Check assumptions required to do the task

**Tactic 4:** Few-shot prompting

- Give successful examples of completing tasks
Then ask model to perform the task

## Principle 2

Give model time to think

For longer task give model more time to think

**Tactic 1:** Specify the steps to complete a task

- Step 1:.
- Step 2: ...
- ...
- Step N: ...

**Tactic 2**: Instruct the model to work out its own solution before rushing to a conclusion

## Model Limitations

**Hallucination**

Makes statements that sound plausible but are not true

**Reducing hallucinations:**
First find relevant information, then answer the question based on the relevant information.