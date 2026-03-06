## Prompt Example

```
You are a senior software engineer with expertise in code readability and maintainability. Given a {Python} function, your task is to generate clear and concise source code comments that explain the purpose of the function, key logic, and any assumptions or edge cases handled.

Step 1: Analyze the function holistically - identify what the function is doing, what problem it solves, and the expected inputs/outputs.
Step 2: Break down the logic - find the intent of each significant code block or line, maintaining proximity to the corresponding line.
Step 3: Remove all redundancies - improve clarity by removing redundancy and refining technical language for maintainability.
Step 4: Combine and summarize all designed comments - All generated comments should be combined and summarized, so that the output only contains code comments without rewriting the source code.

Assume variable names may be obfuscated or inconsistent; focus on understanding intent through behavior rather than naming. Use your domain knowledge to infer context where necessary.

Now, generate the one-line or multi-line code comment at the beginning of the source code without any additional explanation for the following code:

def compute_similarity(a, b):
    shared = 0
    for i in a:
        if i in b:
            shared += 1
    return shared / max(len(a), len(b))
```
