# Essential of Markdown file in Project documentation

## Table of Content
- [1. Introduction to markdown file](###Introduction-to-markdown-file)
- [2. How to represent element in markdown file](###How-to-represent-element-in-markdown-file)
- [3. How to write useful README.md in technical project](###How-to-write-useful-README.md-in-technical-project)

***

### Introduction to markdown file
- Markdown file used to technocal documentation
- Format in Markdown file easily write and modify

***
### How to represent element in markdown file
#### 1. Formating
- Use symbol # to create heading title
#### 2. Fonts
- Bold will use ** before and after word (example **Hello World**)
- Italic wil use * or _ before and after word (example *Hello world* or _Hello world_)
- Combine bold and italic will use \*** before and after word (example ***Hello World***)
- Use \~~ before and after word if you want to delete (example ~~Hello World~~ ) 
#### 3. Quotation
- Use > to write quotation
> Here is example of quotation in markdown file
> All word will align on the right of page
- Use \` if you want to much focus on word in sentence
Example `Hello`
#### 4. Table

|STT|Name|Age|
|---|----|---|
|1|Name|32|

#### 5. Code Block
```c
print('Hello world')
```
Can use `Tab` button to create code block

    Here is example of using tab

#### 6. Divider line
Here is some type of divider line:

***
#### 7. Embeded link
- Can use [] and () to embedded link

[Google](google.com)

- Another method (need space between paragraph and variable)

This is [google][1] link

[1]: <google.com>

#### 8. Image
Image need to same folder with README.md file
![example](image.png)
#### 9. Chart
Use mermaid: [mermaid](mermaid-js.github.io/mermaid/#/)
Or PlanUML
#### 10. Math
- Use \$ symbol for math formula

|Name|Alpha|Varphi|UpperUnder|Upper|Under|Chemistry|Arrow|Infiniti|Phanso|Canthuc|
|----|-----|------|----------|-----|-----|---------|-----|--------|------|-------|
||$\alpha$|$\varphi$|$x^{n+1}$|$x^2$|$y_1$|$H_2SO_4$|$\to$|$\infty$|$\frac{1}{2}$|$\sqrt[n]{k}$|

***
### How to write useful README.md in technical project
README file used to provide information about repository include:
- What the project does
- How to run the project
- Why it's noteworthy
- Who maintains the project
README file is likely a gateway that everyone can image your project through that document

#### Some negative point that need to avoid when write README
1. The one-liner - It is status of README when that file only have title name and nothing else
2. The ghost - No README file in repository
3. The over-explainer - Write too much content 
4. The out of date - Information of README didn't update
5. The broken promise - 
#### Some benefit of good README can bring in
1. You can SEO value if your repository is public project
2. Gaining user
3. Gain contributor
4. Remind yourself later
#### Guidance of writing README file
1. Strong h1 or h2 for title and sub-title
    h1 used to Title of project
    h2 user to short one-liner about what project does
2. Put an intro paragraph
Intro paragraph is deeper dive into and where you can SEO some keyword in your project that user can catch up and search through it (user search how you project can solve their problem)
3. Diagram / Visual Helper
It is better for user that can image overall what is it in your project and how project can work
4. User intructions
