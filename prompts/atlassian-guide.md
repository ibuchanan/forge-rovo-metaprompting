# Atlassian Prompt Engineering Framework

Documented in 
[The ultimate guide to writing effective AI prompts](https://www.atlassian.com/blog/announcements/ultimate-guide-writing-ai-prompts)
by [Jamil Valliani](https://www.atlassian.com/blog/author/jamil-valliani),
Atlassian recommends specific areas to focus on when writing an AI prompt.

## The framework

When writing an AI prompt,
there are four key areas to focus on:
persona, task, context, and format.

### Persona

The persona refers to
the information you provide about yourself
when writing an AI prompt.
You could write a simple prompt like:

```markdown
Write an email to [contact] welcoming them to the company.
```

but you can add more context with a persona in order to get a better response.
Instead, try:

```markdown
I am an HR manager.
Write an email to [contact] welcoming them to the company.
Invite them to schedule a meeting with me on [date].
```

### Task

The task refers to the actual task you're telling AI to perform.
You should be specific about your task instructions to get the best results.
However, it's also important to be clear and concise 
when assigning AI tasks.
For example, your task could be:

```markdown
Write an email to [contact] to schedule a meeting on [day].
```

If you want to include anything specific in your email,
you can add context once you've clearly stated your task.

### Context

Context is the best way to get targeted results from your AI prompts.
Whether you're using AI for content creation, automation, 
or refining your writing, 
providing context is a great way to tell AI how you want it to perform a task. 

Let's say you're sending a welcome email to a new hire, 
and there are a few details you want to include. 
You could say:

```markdown
Write an email to [contact] to schedule a meeting on [day].
Ask them if they have any questions about their new role.
Thank them for joining the team.
```

### Format

Different formats work for different types of content.
Emails should be short and sweet, 
but blog posts can be thousands of words long. 
When writing an AI prompt, 
tell AI what format you want the response to be in. 
For example, you could say:

```markdown
Write an email to [contact] to schedule a meeting on [day]. 
Use less than 200 words.
```

You can also ask AI to provide your results in the form of 
a list, a table, or any other format you want.

## Tips

### Use natural language

Using natural language is one of the most critical parts of effective AI prompting.
Think of it like having a conversation with AI.
You should write your prompts in a way that mimics everyday speech.
That way, AI tools can better understand what you're asking for.
The words you use 
and the way you phrase things 
can significantly impact the output you receive. 

Try phrasing your prompts differently 
if you're having trouble getting the results you want from AI tools, 
and you'll learn what works and what doesn't.

For example, if you want to generate ideas 
to create a knowledge base for a specific problem, 
you could say:

```markdown
Write a knowledge base article for troubleshooting a VPN issue using these steps
```

This prompt uses natural language to ask for 
a knowledge base article for a specific task with a specific set of principles that you set.


### Provide clear and detailed instructions

Whether you want AI to create a Confluence page or refine your writing, 
you must tell it precisely what you want. 
When you write an AI prompt, 
provide clear and detailed instructions 
about the task. 

Open-ended prompts usually result in more open-ended results, 
which means you have less control over your output. 
The more details you provide, 
the more targeted results you'll get; 
as long as you're not adding too many unnecessary words or details.

For example, if you want to refine your writing, you can say:

```markdown
Please refine the following paragraph to make it more engaging and professional [insert paragraph]. 
Use varied sentence structures and more descriptive language 
to enhance the readability.
```

This prompt gives clear instructions for improving a piece of writing, 
specifying the desired outcome, 
the text to refine, 
and the techniques to use. 
This helps the AI to deliver a more focused and high-quality output.

### Keep your prompts concise and straightforward

It can be tempting to include a lot of details when writing an AI prompt, 
but that's not how you get the best results. 
Details are good, 
but lengthy prompts with too many details can confuse AI tools. 
Add essential details, 
but keep your prompts concise and straightforward 
to ensure they're easy to parse.

If you need to add more details to refine your output, 
you can do that after you write your first prompt.

For example, ask AI to explain how social media marketing works. 
If the answer doesn't include a detail you're interested in, 
simply tell AI to add that detail to the explanation.

If you were to use a vague and long-winded prompt instead like:

```markdown
Social media marketing is very important today with platforms 
like Facebook, Instagram, and Twitter. 
It includes creating content, 
engaging with followers, 
running ads, 
and tracking performance. 
Can you explain all this 
and guide me on how to measure ROI?
```

it can lead to poor results.

Instead of asking that, say:

```markdown
Explain social media marketing on Facebook, Instagram, and Twitter, 
including content creation, follower engagement, ad strategies, and ROI measurement.
```

This prompt is straightforward and specific, 
and it clearly states the purpose of the email 
and what it should include without using unnecessary details or words. 

### Be conversational

We mentioned earlier that writing AI prompts is similar to having a conversation with AI;
and it's essential that you understand 
and take advantage of that.
Write your prompts like you're talking to a person to get more interactive results.
If you don't get the results you're looking for, 
tell AI how to improve those results until you get what you want.
