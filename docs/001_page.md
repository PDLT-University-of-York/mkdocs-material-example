# More presentation options

**Material for Mkdocs provides a number of additional features for displaying content.** 

These features make this framework particularly useful for educators, as they give a range of tools for structuring and presenting learning materials for students.

The [Material documentation](https://squidfunk.github.io/mkdocs-material/reference/) provides clear, step-by-step guidance to the options available, and how they can be incorporated into a Mkdocs project, with copy-and-paste examples. 

The information below is intended to briefly showcase how some of this functionality could be used in an educational context.

## Call-outs (admonitions)

Material for Mkdocs gives content creators the ability to display content in call out boxes, known as admonitions. These can be displayed in a number of ways. 

!!! note

    Styled boxes like this one can be used to prompt learners, drawing attention to key information, tasks, or additional reading and resources.

    A variety of styles are available, using different icons and colours. Custom headings can also be added.


??? Info "Info - Select to display"

    Admonitions can be set to only display when a user selects them. 
    
    This can be useful in cases where you want a learner to reflect on a question or prompt before they immediately see the answer.


## Tabbed content

In Material for mkdocs, it is easy to set-up content to be displayed in a tabbed navigation. Other elements such as images and code blocks can be added to the tabs.

Tabbed content can be useful for taking students through a step by step process, or enabling them to easily compare two items side-by-side.

### Tabs to illustrate a process


=== "Step one"

    * Open the command line on your computer.
    * Navigate to the correct directory.

=== "Step two"

    * Check that you are using the correct version of python by checking the version.     
    ``` 
    python --version
    ```

=== "Step three"

    * Begin the data analysis by running the file  
    ``` 
    python test_analysis.py
    ```

### Tabs to compare two examples

=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

## Footnotes and annotations.

Where required, footnotes[^1] can be added to content. 

The text of the footnote can be added anywhere in the page -- MkDocs will automatically place the content at the bottom of the page[^2]. 


[^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

[^2]:
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

