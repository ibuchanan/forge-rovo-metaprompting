# COSTAR Prompt Engineering Framework

Documented in 
[Unlocking the Power of COSTAR Prompt Engineering: A Guide and Example on converting goals into system of actionable items](https://medium.com/@frugalzentennial/unlocking-the-power-of-costar-prompt-engineering-a-guide-and-example-on-converting-goals-into-dc5751ce9875)
by [Frugal Zentennial](https://medium.com/@frugalzentennial),
COSTAR is a framework that offers a structured approach to prompt creation.
The suggestions have been modified slightly to be clean [Markdown](https://www.markdownguide.org/).

## Structure

The structure of the COSTAR framework follows:

```markdown
## Context

// Providing background information helps the LLM understand the specific scenario.

## Objective

// Clearly defining the task directs the LLM’s focus.

## Style

// Specifying the desired writing style aligns the LLM response.

## Tone

// Setting the tone ensures the response resonates with the required sentiment.

## Audience

// Identifying the intended audience tailors the LLM’s response to be targeted to an audience.

## Response

//Providing the response format, like text or json, ensures the LLM outputs, and help build pipelines.

```

## Example

An example of the applied framework follows:

```markdown
## Context

I am a personal productivity developer.
In the realm of personal development and productivity,
there is a growing demand for systems that not only help individuals set goals
but also convert those goals into actionable steps.
Many struggle with the transition from aspirations to concrete actions,
highlighting the need for an effective goal-to-system conversion process.


## Objective

Your task is to guide me in
creating a comprehensive system converter.
This involves breaking down the process into distinct steps,
including identifying the goal,
employing the 5 Whys technique,
learning core actions, setting intentions,
and conducting periodic reviews.
The aim is to provide a step-by-step guide 
for seamlessly transforming goals into actionable plans.

## Style

Write in an informative and instructional style,
resembling a guide on personal development.
Ensure clarity 
and coherence in the presentation of each step,
catering to an audience keen on enhancing their productivity 
and goal attainment skills.

## Tone

Maintain a positive and motivational tone throughout,
fostering a sense of empowerment and encouragement.
It should feel like a friendly guide offering valuable insights.

## Audience

The target audience is individuals interested in personal development and productivity enhancement.
Assume a readership that seeks practical advice 
and actionable steps to turn their goals into tangible outcomes.

## Response

Provide a structured list of steps for the goal-to-system conversion process.
Each step should be clearly defined, and the overall format 
should be easy to follow for quick implementation. 
```
