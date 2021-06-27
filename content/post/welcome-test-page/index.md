+++
author = "Hugo Authors"
title = "Hello world!"
date = "2021-06-27"
slug = "welcome-test-page"
description = "This article is pretty much saying hello and testing out all the formatting "
tags = [
    "welcome"
]
categories = [
    "reference",
    "syntax"
]

image = "pawel-czerwinski-8uZPynIu-rQ-unsplash.jpg"
+++

Right, so where do I begin? Hello visitor!
<!--more-->

# Headings

# H1
## H2
### H3
#### H4
##### H5
###### H6

# Paragraph

Right, so here are just a few lines so that you're able to gauge the feel of the paragraph.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Code Highlighting

Playing around with `code`!  

# Blockquote without attribution

> Ask and you shall receive.

# Blockquote with attribution

> "The shortest distance between two points is a straight line."<br>
> — <cite>Timothy Chung[^1]</cite>

[^1]: Quote taken from Epsom Leaver's Book, 2021. Often used as a catchphrase by the author when taking a shortcut through the rain.

# Tables

Implication Connective

| P | Q | P → Q |
| --- | --- | --- |
| false | false | true |
| false | true | true |
| true | false | false |
| true | true | true |

With support for Markdown formatting within:

| Italics   | Bold     | Code   |
| --------  | -------- | ------ |
| *italics* | **bold** | `code` |

Ummm....

| Inference Method | Knowledge Base... | ...Inferences from KB | Example Knowledge Base | Example Inference with Explanation |
| :---: | :---: | :---: | :---: | :---: |
| Modus Ponens | (a → b), a | b | If it’s raining, Harry is inside. It is raining. | Harry is inside. |
| And Elimination | a ˄ b | b | Harry is friends with Ron and Hermione. | Harry is friends with Hermione. |
| Double Negation Elimination | ¬(¬a) | a | It’s untrue that I didn’t write this logic. | I wrote this logic. |
| Implication Elimination | a → b | ¬ a ˅ b | If it is raining, then Harry is inside. | It is not raining or Harry is inside. |
| Biconditional Elimination | a ⇔ b | (a → b)(b → a) | If and only if it is raining,  then Ron is inside. | If it is raining, then Ron is inside, and vice versa. |
| De Morgan’s Law | ¬(a ˄ b) | ¬a ˅ ¬b | It’s untrue that Harry or Ron  passed the test. | Harry did not pass the test and Ron did not passed the test. |
| Distributive Property | (a ˄ (b ˅ c)) | (a ˄ b) ˅ (b ˄ c) | It rained today, Harry  or Ron could be indoors. | It rained and Harry was indoors, or it rained and Ron was indoors. |
| Distributive Property | (a ˅ (b ˄ c)) | (a ˅ b) ˄ (b ˅ c) | It’s sunny today, or  it rained and thundered. | It’s sunny or raining today, and it’s sunny or thundering today. |
| Resolution 1 | (p ˅ q), ¬p | q | Ron is in the Great Hall or Hermione is in the library. Ron is not in the Great Hall. | Hermione is in the library. |
| Resolution 1 (extended) | (p ˅ q1 ˅ q2 ˅...˅ qn), ¬p | q | Ron is inside or Hermione is inside or  Harry is inside or Hagrid is away. Ron is not inside. | Hermione is inside or  Harry is inside or Hagrid is away. |
| Resolution 2 | (p ˅ q),(¬p ˅ r) | q ˅ r | Harry or Ron is in the Great Hall, Either Hermione is in the Great Hall or Harry isn’t there. | Ron or Hermione must be in the Hall. (Think about it...Hermione must be in there, otherwise the lack of Harry means Ron should be there.) |
| Resolution 2 (extended) | (p ˅ q1 ˅ q2 ˅...˅ qn)), (¬p ˅ r1 ˅ r2 ˅...˅ rn)) | q1 ˅ q2 ˅...˅ qn   ˅ r1 ˅ r2 ˅...˅ rn | Harry or Ron or Dumbledore is in the Great Hall, Either Hermione or Hagrid is in the Great Hall or Harry isn’t there. | Either Ron, Dumbledore, Hermione  or Hagrid is in the Great Hall. Either Hermione or Hagrid is in the Great Hall or Harry isn’t there, so that means Ron or Dumbledore could be in the Great Hall too. |
| Empty Clause | p, ¬p | () \[an empty clause with a false value\] | Harry is in the Great Hall and Harry is not inside the Great Hall. | This entire sentence cannot be true because it contradicts itself. |

# Code Blocks

#### Code block with backticks

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

#### Code block indented with four spaces

    <!doctype html>
    <html lang="en">
    <head>
      <meta charset="utf-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

#### Code block with Hugo's internal highlight shortcode

{{< highlight html >}}
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

# List Types

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

* List item
* Another item
* And another item

#### Nested list

* Fruit
  * Apple
  * Orange
  * Banana
* Dairy
  * Milk
  * Cheese

# Unfinished Work — abbr, sub, sup, kbd, mark ARE NOT YET SUPPORTED.

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.

# Maths
{{< math.inline >}}
<p>
Inline math: \(\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…\)
</p>
{{</ math.inline >}}

Block math:
$$
 \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
$$

# Experimental Emoji
<p><span class="nowrap"><span class="emojify">🙈</span> <code>:see_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙉</span> <code>:hear_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙊</span> <code>:speak_no_evil:</code></span></p>
<br>

# Picture Arrangement Test
![Photo by Florian Klauer on Unsplash](florian-klauer-nptLmg6jqDo-unsplash.jpg)  ![Photo by Luca Bravo on Unsplash](luca-bravo-alS7ewQ41M8-unsplash.jpg)

![Photo by Helena Hertz on Unsplash](helena-hertz-wWZzXlDpMog-unsplash.jpg)  ![Photo by Hudai Gayiran on Unsplash](hudai-gayiran-3Od_VKcDEAA-unsplash.jpg)


## YouTube Privacy Enhanced Shortcode

{{< youtube VaSstf9VJGQ >}}

<br>
