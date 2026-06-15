# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").

**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input       | Expected Behavior      | Actual Behavior                                     | Console Output / Error |
| ----------- | ---------------------- | --------------------------------------------------- | ---------------------- |
| Guess of 5  | Input added to history | Input only added when Submit Guess is clicked twice | None                   |
| Guess of 20 | Too High hint          | Too low hint shown                                  | None                   |
| Guess of 25 | Go lower               | Go higher shown                                     | None                   |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

I used Claude Code for this project

One AI suggestion that was correct was that the hint's were in the wrong
cases. For example if the guess was higher than the secret, the hint provided was to "Go HIGHER!" instead of "Go LOWER!" I verified this by reviewing the code Claude found the bug in. 

One AI suggestion that was misleading was that it said I could run the tests by using pytest, however I specifically needed to use python -m since I could not import check_guess from logic_utils by just using pytest. 
---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
