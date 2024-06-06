# workflow-demo

A demo using GPTScript to encapsulate an automated workflow consisting of the following steps:
1. Get a selection of twitter posts
2. Summarize their content
3. Summarize the content of any links they directly reference
4. Write the results to a Markdown document

To launch, run:

```sh
gptscript github.com/gptscript-ai/workflow-demo
```

or clone this repository and run the local file:

```sh
gh repo clone gptscript-ai/workflow-demo
cd workflow-demo
gptscript ./tool.gpt
```
