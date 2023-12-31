---
description: stick that number in a box
---

# Variables

Okay - time for one of the most important concepts in programming - variables. Read the newbox to figure out what they are.&#x20;

<details>

<summary>New concept: Variables</summary>

Think of variables as boxes with a label slapped on top. They hold data, and you can change and read that data. There are also some rules that apply to variables:

1. You can't mix and match data types. For example, you shouldn't set `MyVar` to `"cool"` when it was already `43`.
2. It's bad practice to name variables things already reserved - so you shouldn't name your variable `input` or `print`.

To set variables, do this:

```python
MyVar = 5
TextToPrint = "hello"
print(TextToPrint) # This works
print("TextToPrint") # This doesn't.
print(MyVar) # Python automatically converts the integer to a string
```

</details>

While we're at it, let's introduce a few more things:

<details>

<summary>New concept: Returning</summary>

Functions sometimes _return_ data to you - for example, an addition function might return the sum of it's arguments. Here's an example:

```python
# the add() function isn't a builtin, it's just an example
a = 4
b = 2
result = add(a,b)
print(result)
```

</details>

<details>

<summary>New data type: <code>int</code></summary>

An `int` (short for integer) is basically a number with no decimals.\


4, 12, 83, 1292, 1033, 12, and 8 are all integers.

3.22, 1.1, 55.21, 542.942 and 12.7 are **not** integers.

</details>

<details>

<summary>New function: <code>input(prompt)</code></summary>

This function takes one `str` (short for String) and prints it, then allows the user to type in something. After the user hits Enter, the function returns what the user typed it.

```python
text = input("What would you like me to say? > ")
print(text)
```

</details>

Oh, one more thing.

{% hint style="info" %}
You can do math pretty easily:

`x = 4 + 2 # x will be 6`
{% endhint %}

Okay - that's all you need to know to make some pretty cool stuff.

Let's try making a greeting program. You can copy this code into your compiler ([here's the link](https://www.online-python.com/fQBxnG5oVK) if you forgot it)

```python
name = input("What is your name?")
```

Here we're getting the user's name and storing it in a variable called `name`.

```python
greeting = "Hello, " + name # Wait, this looks a lil sus...
```

Wait, did we just add a string to a string? Yes, we did! This is called _concatenation_, and it's when we stick two strings together.

```python
print(greeting)
```
