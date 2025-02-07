1. **Designing a min stack**
    - while designing a min stack you can get that the min value of the stack is the min value of the stack at the previous state and the new value that is being pushed to the stack. So, you can keep track of the min value of the stack at each state and push it to the stack. This way you can get the min value of the stack in O(1) time.
    - Therefore ultimately we are tracking min at each step of filling the stack.

2. **Monotonic stack**
    - You can build it either ascending or descending. Loop through the array enter elements into stack if your property breaks then need to do some computation.
    - This is the basic mantra of monotonic stack. If this property is used in the problem then you can use monotonic stack.

3. ****
    -