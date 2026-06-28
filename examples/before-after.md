# Before and After Examples

These examples are illustrative. They are not formal evaluations and do not claim that every model will behave this way.

The goal is to show how interaction quality can change when an assistant follows a well-designed Interaction Profile.

## Communication

### Without Interaction Profile

User:

```text
Make this sound better: I didn't finish because everyone kept changing things.
```

Assistant:

```text
I was unable to complete the task because the requirements were repeatedly changed by multiple stakeholders.
```

### With Interaction Profile

User:

```text
Make this sound better: I didn't finish because everyone kept changing things.
```

Assistant:

```text
Here is a calmer version:

I was not able to finalize the work because the requirements changed several times during the process. I can complete it once we confirm the final direction.

Small communication note: this keeps the reason clear, but shifts the focus toward what is needed next.
```

## Brainstorming

### Without Interaction Profile

User:

```text
Give me ideas for a small community project.
```

Assistant:

```text
Here are 25 ideas:
1. Community garden
2. Book club
3. Neighborhood cleanup
4. Charity run
5. Art wall
...
```

### With Interaction Profile

User:

```text
Give me ideas for a small community project.
```

Assistant:

```text
Here are five practical directions:

1. A weekend cleanup for one visible public area.
2. A shared shelf for books, tools, or school supplies.
3. A monthly skill-swap session.
4. A simple neighborhood help list for errands or repairs.
5. A small local history or photo archive.

If you want the easiest starting point, choose the cleanup. It has a clear scope, low cost, and visible results.
```

## Planning

### Without Interaction Profile

User:

```text
I have too much to do this week. Help.
```

Assistant:

```text
Create a prioritized to-do list, use time blocking, avoid distractions, and break tasks into smaller steps.
```

### With Interaction Profile

User:

```text
I have too much to do this week. Help.
```

Assistant:

```text
Let's reduce the pressure first. Send me your tasks as a messy list. I will sort them into:

- must happen this week;
- should happen if possible;
- can wait;
- needs clarification.

If listing everything feels hard, start with the three tasks taking up the most mental space.
```

## Learning

### Without Interaction Profile

User:

```text
Explain recursion.
```

Assistant:

```text
Recursion is a programming technique where a function calls itself until it reaches a base case.
```

### With Interaction Profile

User:

```text
Explain recursion.
```

Assistant:

```text
Recursion means solving a problem by using a smaller version of the same problem.

Example: if you want to count down from 3, you can say:

- print 3;
- then count down from 2.

The important idea is the stopping rule. Without it, the process keeps calling itself forever.

If you want, I can show this as code next.
```

## Clarification

### Without Interaction Profile

User:

```text
Help me write an email about the deadline.
```

Assistant:

```text
What is the deadline? Who is the recipient? What is the project? What tone do you want? Is the deadline moving earlier or later? Should the email be formal or informal?
```

### With Interaction Profile

User:

```text
Help me write an email about the deadline.
```

Assistant:

```text
Here is a neutral draft you can adapt:

Hi [Name],

I wanted to follow up on the project deadline. Based on the current status, I think we should confirm whether the original timeline still works or whether we need to adjust expectations.

Could you let me know if the deadline is still fixed, or if there is room to discuss a revised timeline?

Best,
[Your Name]

If you want, I can make it firmer, more apologetic, or more concise.
```

## Decision Making

### Without Interaction Profile

User:

```text
Should I accept the new role or stay where I am?
```

Assistant:

```text
You should compare salary, growth, work-life balance, culture, commute, benefits, and long-term career goals.
```

### With Interaction Profile

User:

```text
Should I accept the new role or stay where I am?
```

Assistant:

```text
Let's make the decision smaller. The key question is probably not "which job is better?" It is "which tradeoff are you more willing to live with?"

Start with these three:

1. What improves in the new role?
2. What gets worse or riskier?
3. What are you afraid you will regret in six months?

Send rough answers and I will help you compare them without forcing a decision.
```

Related reading:

- [Comparison Gallery](comparison-gallery.md)
- [Design Principles](../docs/design-principles.md)
