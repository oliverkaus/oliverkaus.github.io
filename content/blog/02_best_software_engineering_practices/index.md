---
title: "🤓☝ Software Engineering Best Practices For Data Scientists"
date: 2018-10-07T11:39:10+02:00
publishdate: 2018-10-07T11:39:10+02:00
image: "/images/blog/2.jpg"
tags: ["Software Engineering", "Data Science"]
imagecaption: Photo by pxhere
postsummary: "Did you ever need to make some changes to an ML project that you worked on a long time ago? Very likely it was not a pleasant experience."

comments: false
---
*Image by pxhere.com*

# Introduction

There are some well-established practices in the software engineering community that are less established in the Data Science world. 
Now that the Data Science community is maturing, these practices get more important in Data Science. 

But when should you use those practices and when is it okay to ignore them? 

You should use the principles:
- In a production setting
- When you collaborate with others
- When your code will be re-used

You can ignore them:
- When you are creating a one-off analysis that you likely won't need to revisit

This blog post will speak about the following three software engineering best practices:
- Coding Practices
- Collaboration Practices
- Testing Practices

## Coding Practices
Following the key software engineering principles, your code should be:
- Clean
- Modular
- Efficient
- Well-documented

Each part will be described in more detail. 

### Clean
Some guidelines to write clean code:
- Give meaningful names to variables
  - Prefix is_ or has_ for booleans, e.g. is_active_customer
  - Imply type in name, e.g. names_list
  - Give concise names, not too short, not too long (e.g. age_gender_stat_mean_value_comparison is difficult to understand; a is also not useful)
- Correct indentation and whitespacing
    - Follow pep8 guidelines

### Modular
Modularity is all about making your code reusable and avoiding to repeat code. 

Some hints:
- Functions should do exactly one thing
- Functions should ideally not take more than 3-5 arguments

### Efficient
Your code should consume least resources, meaning to run least amount of CPU/memory. In Data Science, there are several libraries that help you achieve this. If you are using a for loop to iterate over data points to apply some processing, you can likely improve your logic. 

Some hints: 
- Use vector operations: e.g. numpy arrays
- Use sets

### Well-documented
Comments are useful to make it easy for your future self or somebody else to understand your code. 

There are a few ways to achieve this:
- Inline comments - line level
   - Should be used where code is not self-explanatory
- Docstrings - module and function level
   - Should always be used at a function level
- Project documentation - project level
   - Explaining broad code functionalities


# Summary
The best coding practices described above will take some time initially. For one-off analyses, applying the best coding practices are often not worth it. However, you are putting code into production, you are collaborating with others or your code will be re-used, then your code should contain all software engineering best practices. 