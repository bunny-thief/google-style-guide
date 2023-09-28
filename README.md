# google-style-guide

## What is a style guide?

A style guide provides conventions that make code look uniform across different code bases. Style guides don't affect how code functions, only how it is formatted. Code linters take conventions defined in a style guide and apply it consistently to files in a project.

Style guides are also known as Coding Standards. Most companies adopt coding standards which their programmers are expected to follow when submitting code.

### Examples

  - How variables, methods and classes are named
    - camelCase (variables, methods)
    - Pascal Case (classes) aka UpperCamelCase
    - PI (constants)
    - com.company.project.src (packages)
  - Spacing between variables and operators
  - Placement of curly braces
    - End of line
    - Start of next line
  - Indentation
    - Tabs vs spaces
    - 4 spaces
    - 2 spaces


    if (n > 0) {
        System.out.println(n);
    }

Without coding standards the same code would look different based on personal preference.

    if(n>0)
    {
        System.out.println(n);
    }

## Why use a style guide?

The lack of consistency requires more effort from the reader to adjust to code written by different programmers. Bugs are harder to find because a programmer spends more time and energy adjusting to different formatting.

Groups that agree to use a coding standard spend less time discussing how code should be formatted and more time writing code.

There are also practical reasons. If two programmers work on the same code and submit updates to a version control system, each new version would be cluttered with slight formatting changes that don't affect how the code functions.

## Examples of Style Guides

Companies create their own style guides, which employees their employees follow, to ensure uniformity across the many projects they have. Communities adopt these guidelines because it takes a lot of effort to come up with and maintain these standards.

  - Google Java Style Guide
  - AirBnB [Javascript Style Guide](https://github.com/airbnb/javascript)
  - Python [Black](https://pypi.org/project/black/), follows [PEP8](https://peps.python.org/pep-0008/)
  - Go [fmt](https://go.dev/blog/gofmt)

## Resources
[Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)  
[google-java-format IntelliJ plugin](https://plugins.jetbrains.com/plugin/8527-google-java-format)  
[IntelliJ set up instructions](https://github.com/google/google-java-format/blob/master/README.md#intellij-android-studio-and-other-jetbrains-ides)