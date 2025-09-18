---
layout: essay
type: essay
title: "Smart Questions and Smart Takeaways"
# All dates must be YYYY-MM-DD format!
date: 2025-09-10
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/OIP.png">

A common phrase I got a few too many times growing up was "think before you speak next time." It's a good motto to remember in general, but especially applicable for the concept of asking questions the "smart way." Now, in the world of software engineering, it's a bit more complex than just thinking for a few brief moments before saying something out loud, but the same general principle applies. What you say matters, and you want to get the most bang for your buck when you ask anything in a complicated and highly technical field. Every new piece of information, help, and guidance is ever so crucial. So, how do we get the most out of our questions? 

## Getting good ROQ (return on question) 

You like that double entendre? Get it, "return" and the ROI reference? Eh? Anyway, a good place to look at how other software engineers are asking their questions is on the site "Stack Overflow." Although it is clear that not all questions are equal, there are several key aspects of what makes a question worth your precious time of typing away. In the following example, we can observe the makings of a question asked the "smart way." Below, we can see a user on Stack Overflow asking how to convert a string to boolean in JavaScript.

```
Q: How can I convert a string to boolean in JavaScript?

Can I convert a string representing a boolean value (e.g., 'true', 'false') into an intrinsic type in JavaScript?

I have a hidden form in HTML that is updated based on a user's selection within a list. This form contains some fields which represent boolean values and are dynamically populated with an intrinsic boolean value. However, once this value is placed into the hidden input field it becomes a string.

The only way I could find to determine the field's boolean value, once it was converted into a string, was to depend upon the literal value of its string representation.

var myValue = document.myForm.IS_TRUE.value;
var isTrueSet = myValue == 'true';
Is there a better way to accomplish this?
```
Going through a quick checklist: first, the heading of the question is clear and specific to the subject of the question. It's tagged in the proper categories such as "javascript," "boolean-operations," and "string-conversion," which all directly correlate to the question. Not only did the user give a concise and straightforward question, they also gave context to their situation/project and even showed an example of what they'd tried and described the result they got in an attempt to find a better method of choice. Lastly, the user could have shown more courtesy in their original question or in the replies to help encourage community answers, but that's on the nitpickier side of things.


## For there to be good, there must be bad.

Like I mentioned earlier, not all questions are created equal. Not-so-"smart" questions can be labeled as such for a variety of factors. Obviously, anything to the opposite effect of what was mentioned in the "smart" question would be some telltale signs. However, this next question presents an entirely new set of issues that may cause an unintended and frankly unwanted answer that makes the question itself... questionable. Ha ha... ha... ha?

```
Q: How do I code in Python?

I am a beginner programmer and new to Python. I want to learn more Python, can someone give me the steps in coding for Python? Thanks a lot.

```

This question has some good parts to it—at least the heading is on topic and relates to the question. However, simply asking for the "steps" is too vague to give a concise answer, and there are many possible viable answers to the general question. What the user is precisely asking for is entirely unclear. To what extent would someone give you "steps"? Is the user looking for a source to learn Python from, or instead an order of concepts to learn first? More prior research that could be accomplished with a simple Google search would likely be more effective. Based on the numerous discrepancies in this question, it can help us identify this question as "not smart."

## Conclusion

Questions are meant to be answered, and in order to receive a quality and ideal answer, the one who provides the answer would be best equipped with a well-stated question. It is integral as a software engineer to understand that asking for help is a standard practice and simply part of the process, but as we've learned on the programming side of things, efficiency and effectiveness are key. Therefore, getting efficient and effective answers heavily relies on asking "smart" questions that can give us a higher likelihood of finding the solution we desire and giving our fellow helpful programmers an easier path to providing us some assistance.


