# Task Assignment with Answers

## Section 1: Multiple Choice Questions

1. What is the powerhouse of the cell?
   - A) Nucleus
   - B) Mitochondria
   - C) Ribosome
   - D) Endoplasmic Reticulum
   - **Answer:** B) Mitochondria

2. Which planet is known as the Red Planet?
   - A) Venus
   - B) Saturn
   - C) Mars
   - D) Jupiter
   - **Answer:** C) Mars

3. What is the chemical symbol for gold?
   - A) Ag
   - B) Au
   - C) Pb
   - D) Fe
   - **Answer:** B) Au

---

## Section 2: Short Answer Questions

1. Explain the difference between renewable and non-renewable energy sources and provide one example of each.
   - **Answer:** Renewable energy sources are replenished naturally over a short period and will not run out (e.g., solar energy). Non-renewable energy sources exist in finite amounts and are depleted through use much faster than they can be formed (e.g., coal or petroleum).

2. Solve for $x$ in the linear equation: $3x + 5 = 20$.
   - **Answer:** 
     $$3x + 5 = 20$$
     $$3x = 15$$
     $$x = 5$$

3. What is photosynthesis, and why is it important for life on Earth?
   - **Answer:** Photosynthesis is the process used by plants, algae, and some bacteria to convert light energy into chemical energy, using carbon dioxide and water to produce glucose and oxygen ($6CO_2 + 6H_2O \rightarrow C_6H_{12}O_6 + 6O_2$). It is vital because it produces the oxygen we breathe and forms the base of the global food web.

---

## Section 3: Practical Coding / Logic Task

Write a short algorithm or description for a function that checks whether a given string is a palindrome (reads the same forwards and backwards, ignoring spaces and capitalization).

- **Answer Solution (Pseudocode):**
  ```text
  function isPalindrome(text):
      // Step 1: Convert to lowercase and remove non-alphanumeric characters
      cleaned = lowercase(removeNonAlphanumeric(text))
      
      // Step 2: Compare cleaned string with its reverse
      reversedText = reverse(cleaned)
      
      return cleaned == reversedText
  end function
  ```