# Which one is which? Declarative or Imperative?!

Loom Recording Link : 
1. [Example #: 1](https://www.loom.com/share/1e900762aa064f3281d6eda24851a0ac?sid=26c7a84c-5d9a-4098-9332-56e06d4935b0)
2. [Example #: 2](https://www.loom.com/share/6c5595d9e468489999661653912729f1?sid=17d31a74-b6da-47cc-ac42-e031c0b746d1)
3. [Learning Outcome:](https://www.loom.com/share/da18c17d0a8f489f99b0e309d7275b35?sid=d5abd206-bf0d-490f-81f0-f04e649c9ebb)

## Project Overview

In this project we were tasked to make a video presentation distiguishing the two expamples provided, on which one is the imperative and declarative programming paradigm. we had to analysis the two examples and determine which one follows an imperative programming style and which one follows a declarative programming style.

## How to complete the project

### Step 1: Clone the Repository
### Step 2: Analyze the Examples
### Step 3: Record the Presentation
### Step 4: Insert Loom Links 
### Step 5: Submit the Project

## Presentation Talking Points

**Example #: 1**

### Imperative Approach [2 Minutes]
Imperative programming consists of sets of detailed instructions that are given to the computer to execute in a given order. It's called "imperative" because as programmers we dictate exactly what the computer has to do, in a very specific way.

In the given imperative code, the function cookSteak takes two parameters: steakWeight and desiredDoneness. The function then follows a series of explicit steps to cook the steak.

+ The function starts by initializing two variables, grillTemperature, and steakTemperature, to track the state of the grill and the steak.

+ The grill is then preheated to a specific temperature (204 degrees), which is directly assigned to the grilltemperature variable.

+ The steak is seasoned with 'Salt and Pepper'. This is a direct action that doesn't depend on any condition or previous state.

+ The steak is then cooked. This is done in a while loop, which continues to run as long as the steakTemperature is less than the desiredDoneness. Inside the loop, the steak is grilled and its internal temperature is measured and adjusted based on the steakWeight and desiredDoneness.

+ Once the steak is cooked to the desired doneness (i.e., when steakTemperature is no longer less than desiredDoneness), the loop breaks, and the steak is served.

+ The function then checks if the steak is cooked to the desired doneness. If it is, it returns 'Steak is ready to serve!'; otherwise, it returns 'Steak needs more cooking.'.

Its explicitness and step-by-step instructions characterize this approach. It uses mutable variables (grillTemperature and steakTemperature) to track the state and progress of the cooking process, and it uses a loop and conditional statements to control the flow of the program.



**Example #: 2**

### Declarative Approach [2 Minutes]
Declarative programming is all about hiding away complexity and bringing programming languages closer to human language and thinking. It's the direct opposite of imperative programming in the sense that the programmer doesn't give instructions about how the computer should execute the task, but rather on what result is needed.

In the given declarative code, the function cookSteak also takes two parameters: steakWeight and desiredDoneness. However, instead of outlining each step in detail, the function defines a high-level process for cooking the steak.

+ The function starts by defining the cooking process as an array of objects, with each object representing a step in the process. Each step is defined by an action and some associated data (e.g., the grill temperature, the seasoning, and the desired doneness).

+ The function then iterates over this array using a for loop. For each step, it uses a switch statement to determine what action to take based on the action property of the step object.

+ Depending on the action, the function then logs a message to the console. These messages describe what is happening (e.g., 'Preheating grill to X°C', 'Seasoning the steak with Y', 'Cooking steak to Z°C', 'Steak is ready to serve!'), but they do not describe how these actions are being carried out.

This approach is characterized by its use of data structures (in this case, an array of objects) to represent the steps of the process. It abstracts away the details of how each step is executed, focusing instead on defining what each step should accomplish. The function itself does not maintain any mutable state; instead, any necessary state is encapsulated within the step objects.


## Learning Outcome [1 Minute]
- I have learned that programming paradigms are different ways or styles in which a given programming langauge can be organized. Each programming paradigm consists of certain structure and features. 
- Programming paradigms are more problem dependent meaning each problem will require a different paradigm and approach. 
- Choosing the correct paradigm for a problem can actually save time and resources in solving a problem.

