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
  >  - Examples - Anything which is not primitive(objects, arrays, functions, large strings, etc..,)
 
  ## HOW CAN WE SEE THERE LOCATIONS? 🤔
  > Well unlike C/C++ we cannot see the addresses of variables in JS. But instead of the locations we can see the **OBJECT ID'S** using the **DEV-TOOLS😎**. 
  1. Well the difference between this **id** and **real memory address** is: 
     - where this **id** is only a label created by Chrome, while the real memory address is the actual physical location in your computer’s RAM.

     ## 🎯 Simple Probability Example

### **Example:**  
A bag contains **3 red balls** and **2 blue balls** (total **5 balls**).  
If you pick **1 ball randomly**, what is the probability that it is **red**?

---

### ✅ **Step-by-step Solution**

**1. Total balls:**  
3 red + 2 blue = **5**

**2. Favourable outcomes (red balls):**  
There are **3** red balls.

**3. Probability Formula:**  
\[
P(\text{Red}) = \frac{\text{Number of red balls}}{\text{Total balls}}
\]

**4. Substitute values:**  
\[
P(\text{Red}) = \frac{3}{5}
\]

---

### 🎉 **Final Answer:**  
**Probability of picking a red ball = 3/5 = 0.6 = 60%**


  > ### But How ?🤔
  >  Well goto **DEV-TOOLS -> MEMORY-TAB -> SELECT Heap snapshot -> Click Take Snapshot Button -> Click Ctrl+F and search what you want to see(any variable name)** 
