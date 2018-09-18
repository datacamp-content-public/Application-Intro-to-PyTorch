---
title: Test
description: Test
---

## An exercise title written in sentence case

```yaml
type: NormalExercise
key: 540560e7be
lang: python
xp: 100
skills: 2
```

This is the assignment text. It should help provide students with the background information needed.
The instructions that follow should be in bullet point form with clear guidance for what is expected.

`@instructions`
- Instruction 1
- Instruction 2
- Instruction 3

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`
```{python}
import numpy as np
```

`@sample_code`
```{python}
# construct a 5x2 Numpy array(2d: 2-dimensional), empty (uninitialized)
x = np.empty([5, 3])
print(type(x))
print(x)
print(x.shape)

# let's create an Numpy array of random numbers
y = np.empty([2, 2], dtype=int)
print(type(y))
print(y)
print(y.shape)

# let's create an Numpy array (1d: vector) of zeroes
z = np.zeros([2, 2], dtype=int)
print(type(z))
print(z)
print(z.shape)
```

`@solution`
```{python}
# Answer goes here
# Make sure to match the comments with your sample code
# to help students see the differences from solution
# to given.
```

`@sct`
```{python}
# Update this to something more informative.
success_msg("Some praise! Then reinforce a learning objective from the exercise.")
```

---

## Deep Learning Library

```yaml
type: VideoExercise
key: 7bb3655ce0
xp: 50
```

`@projector_key`
85e49b280cb2436cac6fb7334cd914f3
