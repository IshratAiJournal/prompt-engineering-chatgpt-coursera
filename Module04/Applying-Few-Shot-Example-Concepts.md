# 📘 Prompt Engineering for ChatGPT – Module 4

## ✅ Module Title: Applying Few-Shot Example Concepts

### 💡 Key Concept: Few-Shot Prompting
Train the model by showing 2–3 examples of a task before asking it to perform the task.


## 1️⃣ Assignment – Complex Task with Few-Shot Examples

### 🧾 Prompt:
```txt
I want you to convert casual phrases into polite, professional email language. Here are a few examples:

Example 1:
Input: "Hey, can you send me that file ASAP?"
Output: "Hi, could you please share the file with me at your earliest convenience? Thank you."

Example 2:
Input: "Need those figures by tomorrow."
Output: "May I kindly request those figures by tomorrow? That would be greatly appreciated."

Example 3:
Input: "You didn’t attach the document."
Output: "I noticed the document might not have been attached. Would you mind checking?"

Now, please convert the following:
Input: "What's going on with the budget thing?"
```

### 📥 Sample Output:
```txt
Output: "I wanted to follow up on the budget matter. Could you kindly provide an update when you have a moment?"
```

## 2️⃣ Assignment – Complex Task with Sub-Steps

### 🧾 Prompt:
```txt
I want you to solve math word problems by breaking them down into sub-steps before arriving at the final answer. Follow these examples:

Example 1:
Question: Sarah has 3 apples. She buys 4 more. Then she gives 2 to her friend. How many apples does she have now?
Step 1: Start with 3 apples.
Step 2: Add 4 more → 3 + 4 = 7 apples.
Step 3: Subtract 2 given away → 7 - 2 = 5 apples.
Final Answer: 5 apples

Example 2:
Question: A car travels 60 km in the first hour and 45 km in the second hour. How far did it travel in total?
Step 1: First hour distance = 60 km
Step 2: Second hour distance = 45 km
Step 3: Total distance = 60 + 45 = 105 km
Final Answer: 105 km

Now solve this problem:
Question: A bakery sold 120 muffins in the morning and 85 in the afternoon. Then they baked 50 more. What’s the total number of muffins they had sold and baked by the end of the day?
```

### 📥 Sample Output:
```txt
Step 1: Morning sales = 120 muffins  
Step 2: Afternoon sales = 85 muffins  
Step 3: Total sold = 120 + 85 = 205 muffins  
Step 4: Baked later = 50 muffins  
Step 5: Total sold and baked = 205 + 50 = 255 muffins  
Final Answer: 255 muffins
```

### 🎓 Status:
✅ **Assignment Submitted & Scored: 100%**
📅 **Completed on Day 49 of Learning Journey**
