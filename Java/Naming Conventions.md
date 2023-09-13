Pascal case -- or PascalCase -- is a programming naming convention where the first letter of each compound word in a variable is capitalized.

When more than one word is needed to properly convey a variable's purpose, the PascalCase naming convention dictates that words be appended to each other. The use of a single uppercase letter for each additional word makes it easier to read code and discern the purpose of variables. 

### Pascal case examples

The following are examples of terms written in Pascal case:

- ItemNumber
- TotalValue
- URLName
- MasterCard

Synonyms for Pascal case include medical case, upper camel case, studly caps, inter-caps and humpy case.

### Pascal case vs. camel case

Pascal case requires that the first letter of a variable be in upper case. In contrast, camel case -- also known as [CamelCase](https://www.techtarget.com/whatis/definition/CamelCase) -- allows the first letter to be either upper or lower case. To clarify between the two options, the terms UpperCamelCase and lowerCamelCase are often used. Pascal case would be equivalent to UpperCamelCase.

### Pascal vs. snake vs. kebab case

Two popular alternatives to Pascal case are [snake case](https://www.theserverside.com/definition/Snake-case) and [kebab case](https://www.theserverside.com/definition/Kebab-case). Snake case separates words with an underscore, while kebab case uses a dash:

- SCREAMING_SNAKE_CASE_EXAMPLE
- kebab-case-example

### Pascal case in Java

In [Java](https://www.theserverside.com/definition/Java), all classes, interfaces and enums are expected to use Pascal case. Variables in Java are to be written in lowerCamelCase, and static variables are in [snake case](https://www.theserverside.com/definition/Snake-case).

### Pascal case naming convention problems

Acronyms and abbreviations can present a challenge for developers who use the PascalCase naming convention. For example, if a developer was to use the NASA images APIs, the following two variable names would comply with Pascal case naming standards:

- NASAImages
- NasaImages

The latter is arguably easier to read. However, the former respects the official NASA trademark.

In addition, the manner in which the term URL is written is a prime example of an inconsistent application of PascalCase throughout the industry. For example, Java network APIs always reference the term URL in all caps, as with the classes URLConnection and URLEncoder. In contrast, the Spring APIs include classes such as UrlResource and UrlTag.

The inconsistent application of any naming convention may result in software defects that are difficult to diagnose. As such, it is important for programming teams to decide how to apply naming conventions for the various corner cases that arise in the [software development lifecycle](https://www.techtarget.com/searchsoftwarequality/definition/software-development-life-cycle-SDLC).