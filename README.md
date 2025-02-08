# Expo Go Blank Screen/Crash Issue

This repository demonstrates a common issue encountered with Expo Go: a blank screen or unexpected crash on the simulator or physical device.  The problem's root cause can vary widely, from simple configuration issues to more complex code-related problems.  This example provides a potential scenario and a solution.

**Problem:**

The application, when launched on a simulator or physical device using Expo Go, displays a blank screen, crashes immediately, or exhibits unexpected behavior.

**Solution:**

This solution focuses on one common cause:  issues with asynchronous operations and state management. The included code snippets showcase a potential problem and its resolution. While this isn't a comprehensive solution for all scenarios, it represents a typical situation developers might encounter. 

**To reproduce (using the included `bug.js`):** Run the provided code on an Expo Go simulator or physical device. Observe the unusual behavior.

**To fix (using `bugSolution.js`):** Examine the updated code to understand how proper error handling and state management can prevent unexpected crashes and blank screens.  Consider similar techniques for debugging other similar issues you may face with Expo Go.