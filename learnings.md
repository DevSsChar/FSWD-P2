# Challenges and Learnings During the Lab

## **Challenges**

1. **Dynamic Functionality:**
   - Ensured the renamed functions (`addTaskItem`, `prioritizeTasks`, etc.) handled data correctly without introducing bugs or unintended behavior.
   - Debugged issues related to incorrect parameter validation in `addTaskItem`.

2. **Data Sorting:**
   - Resolved problems in sorting tasks by urgency using a custom priority mapping for `prioritizeTasks`.

3. **Edge Cases:**
   - Handled cases where tasks had incomplete properties (e.g., missing `name` or `deadlineMinutes`).
   - Addressed scenarios with empty task lists or unrealistic deadlines.

4. **Timers and Delays:**
   - Validated the functionality of `setTaskReminders` to ensure reminders triggered at the correct times, accounting for minute-to-millisecond conversions.

## **Learnings**

1. **Function Design and Refactoring:**
   - Practiced renaming and refactoring functions for improved readability and clarity.
   - Gained experience with logical naming conventions that better describe functionality.

2. **Array Methods:**
   - Strengthened understanding of JavaScript array methods like `filter` and `sort` for data manipulation.

3. **Error Handling:**
   - Improved error handling techniques to ensure robust validations in `addTaskItem` and other functions.

4. **Timing and Asynchronous Behavior:**
   - Learned the nuances of `setTimeout` and the importance of testing asynchronous behavior.

5. **Debugging and Edge Case Handling:**
   - Enhanced debugging skills by testing with various input scenarios.
   - Built awareness of edge cases such as empty arrays or mismatched property names.

---

## **Summary**

This lab was instrumental in deepening practical JavaScript skills, especially in dynamic data manipulation, error handling, and asynchronous programming. Refactoring and testing helped reinforce clean code practices and improved problem-solving abilities.
