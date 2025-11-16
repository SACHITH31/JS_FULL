# JS_FULL
- Going to complete total JS😁😜

## INTRO TO THIS REPO
- ### DATA TYPES: 
  1. let, const, var(which is not used in more cases).
  2. Knowing about them and also where to use them.
  3. Difference between them.

  ## WHERE JS STORES VARIABLES?🤔
  > Well variabls are stored inside the STACK and HEAP 
  > - STACK(fast, simple, small-data)
  >    - Examples - all primitive data-types(numbers, strings, boolean, null, symbols, etc.., )
  > - HEAP(big-data, slow, complex)
  >   - Examples - Anything which is not primitive(objects, arrays, functions, large strings, etc..,)
 
  ## HOW CAN WE SEE THERE LOCATIONS? 🤔
  > Well unlike C/C++ we cannot see the addresses of variables in JS. But instead of the locations we can see the **OBJECT ID'S (or) DEVTOOL ID'S** using the **DEV-TOOLS😎**.
  1. Well the difference between this **id** and **real memory address** is: 
     - where this **id** is only a label created by Chrome, while the real memory address is the actual physical location in your computer’s RAM.
  ### 📌 Short Example

  Imagine you have a notebook.

  - Your mom puts a **sticker number** on it:  
  **Sticker: #25**  
  → This is like the **DevTools ID (`@350912`)**  
  → Only used for identification  
  → Not the real location
  
  - The notebook’s **real place** is:  
    **Inside the second shelf of your cupboard**  
    → This is like the **real memory address**  
    → Actual place where it is stored  
    → JavaScript does NOT show this

  ### ⭐ Summary
  - **DevTools ID = Sticker number (just a label)**  
  - **Memory address = Actual location where the data lives in RAM**  
  - JavaScript hides real memory addresses for security reasons.

  > ### But How TO SEE THIS DEVTOOL ID'S?🤔
  >  Well goto **DEV-TOOLS -> MEMORY-TAB -> SELECT Heap snapshot -> Click Take Snapshot Button -> Click Ctrl+F and search what you want to see(any variable name)** 

