# Class 1 – Stacks, Queues, and String Manipulation

## 📝 Topics Covered
- Stack Implementation (Invert String)
- Queue Implementation (Invert String)
- Anagram Check Function
- Flowchart Visualization for Anagram Logic


![Anagram Flowchart](FSDI_114_Class1.drawio.svg)

---

## 📚 Explanation of Logic Flow for Anagram Check

1. **Start the Process.**  
   - The function begins by accepting two string inputs.

2. **Preprocessing the Strings.**  
   - I remove any spaces and convert both strings to lowercase.  
   - This ensures that differences in capitalization or extra spaces don’t affect the result.

3. **Check if the Lengths are Equal.**  
   - If the strings don’t have the same number of characters, they cannot be anagrams, so I immediately return `False`.  
   - This is an optimization step to avoid unnecessary further checks.

4. **Sort Both Strings.**  
   - If the lengths are equal, I sort the characters of both strings.  
   - Sorting allows me to directly compare the order and frequency of characters.

5. **Compare the Sorted Strings.**  
   - If the sorted versions of the strings match, that means they are anagrams, and I return `True`.  
   - If they don’t match, I return `False`.

6. **End the Process.**  
   - The function completes after returning the appropriate result.

---

## 🎯 Logic Check

- It avoids unnecessary work by checking lengths first.  
- Sorting the strings standardizes their format for easy comparison.  
- It fully satisfies the definition of anagrams:  
  - Same letters  
  - Same frequency (Count of Each Character)  
  - Same length  

---
## 📚 Files
- `Class_1.ipynb` – Contains all code examples and explanations.
- `FSDI_114_Class1.drawio.svg` – Flowchart diagram for Anagram Logic.

---

*Date Completed:* 12 May 2025