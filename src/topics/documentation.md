# Documentation

One of the statements of the [Agile Manifesto](http://agilemanifesto.org/principles.html "Agile Manifesto") is:

> Working software
>
> over comprehensive documentation.

This does not mean there is no need for documentation at all. Just keep it simple and as lightweight as possible, but still as big as necessary to fulfill its purpose.

## Tooling: Gitbook

Gitbook allows you to write documentation in Markdown \(\*.md\) files. You can create seperate chapters and sub-chapters for topics. Each chapter is stored as a seperate file. This allows you to to version you documentation together with code and to edit different chapters synchronious without getting merge conflicts. The documentation can easily be shipped as a PDF, a html page, etc. This allows you, for example, to always automatically host the matching version of your documentation together with your software.

## Things that should be documented

### Code of Conduct

The Code of Conduct defines some basic rules every team member has to accept and respect. It is usually defined at the beginning of a project but can evolve over time:

Examples:

* **Respect each other**  
  People are different. They can differ in age, sex, origin, education, skills, characteristics. Respect these differences. A heterogeneous team can be better for creativity than a team where all team members have the same mindset.

* **Welcome change**  
  The environment changes all the time. The scope of the project may change, team members may leave the team, new team members may join, new ideas

* **Do not just criticize, criticise constructively**  
  It does not help if you say to your team colleague "your solution is bad", try to bring up ideas how he could do better e.g. by saying "I think the way you solved problem XY is not ideal, wouldn't it be better if you ...".

* You can find more examples in the [Django Code of Conduct](https://www.djangoproject.com/conduct/)

### Core Concepts  \(Architecture\)

Every team member should be given the idea of the \(architectural\) core concepts of the project, especially new team members who do not know anything about it yet. If a team member understands these concepts he will have a better understanding of the impact of a user story, can estimate more precisely and will hopefully solve new problems in a similar way as the other team members.

### Problem to be solved & Vision

The team members need to have a good knowledge about the problem to be solved with the current project and about the plan how to get there. This can be a great motivational boost for the team. By having a common goal the team can pull together.

### Glossary

It is important that all persons in a project share a common vocabulary, otherwise there can be confusion if someone talks about a topic and the listener understands something completely different.

Create a glossary that contains all expressions that are relevant for the project. Do not add a glossary entry for an expression and all its synonyms but describe the expression that is used most frequently and create links from the synonyms to the main descriptions.

Also describe homonyms \(words with different meanings\), e.g. "close" could mean "near" but it could also mean shut \(opposite of open\).

Everybody working in the project should be able to access the glossary \(web, shared file, ...\) and usually it is good practice that the glossary can be edited by everyone as well.

### Know How Distribution Matrix

We had good experience with documenting the distribution of know how in a matrix.

Each topic deemed worthy being listed is rated from 0 to 3 \(having no clue about it to being an expert\) per team member. This helps to visualize that we have at least 2 people up to speed for each topic. In addition it makes it easier to identify risks and measures if a member of the team leaves the project. Color codes for the certain values are recommended \(e.g.: red, orange, blue, green\).

Beyond a sample of a simple matrix:

|  | UI | CI/CD | Architectur | Message Queue |
| :--- | :--- | :--- | :--- | :--- |
| Curt Continous | 2 | 3 | 1 | 1 |
| Tom Tester | 3 | 2 | 1 | 1 |
| Pistol Pete | 1 | 1 | 2 | 3 |
| Albert Architectstein | 1 | 1 | 3 | 2 |
| Ned Newcomer | 2 | 0 | 1 | 0 |



