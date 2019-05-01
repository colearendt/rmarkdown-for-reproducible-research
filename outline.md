## INTRO

- Who has used? More than 1 / mo? 1 / wk? 1 / day?
- Will hopefully have something useful for all

## OUTLINE

- What is? What is not?

## WHAT IS?

- READ def
- Work _relevant_ in another time & place
    - True / verifiable / reproducible

- WORD PICTURE (safe! after lunch)
    - Make tasty cake
    - I want to make it! You try... get Chicken Alfredo
        - What went wrong? Wrong recipe!
        - recipe: ingredients & process to reproduce

## MOTIVATIONAL EXAMPLE
    - NOT reproducible
    - First week at a big boy job after grad school (no programming)
    
    - SAS Code
    - PPT template
    - My manual magic
    
    - Polished PPT w/ relevant results... -> LOTS of money!!
    
    - FEEL GOOD, USEFUL... glad they hired me!
    
    - THEN the graphic designer sends me an email: I updated the template!
    
    - I'm good at algorithms! I got this!
    - Felt no realization I had discovered the next 3 years of my life
    
    - I'M AWESOME! I did it twice!!
    
    - NEXT: SAS developer: we reran the analysis...
    
    - STOP: simplicity... image complicated / space
    - Naive optimism dashed (briefly) by redundancy

## WHAT IS RMD?

- MARKDOWN - lightweight markup language and formatting syntax
    - Human readable
    - Flexible output

- R -> Programming

- BOTH -> Plaintext document easy to read... diff... vcs
    - ALSO: Generate just about anything

- PICTURE:
    - Ingredients - See talk on Reproducible R Packages
    - Rmd - Process between ingredients and the results

- How to help?
    - Code, prose, formatting in one place
    - Readable, editable, diffable

## PARAMETERIZED
    - Little known - executable function with defined inputs
        - i.e. path to dataset, region, etc.
    - Define in YAML header
    - Use it in your code
    
    * CALL this RMD from other code (i.e. run on a schedule, tons of variants, etc.)
    * Make selections interactively!
        - IDE
        - RStudio Connect (all data products you create accessible to everyone)

## LANGUAGE
    - R is an interface language (Fortran, C)
    - Interoperability between languages (reticulate)
    - Practical example: use python googlemaps API with Shiny / ggplot

## DEPLOYMENT
    - Communicate!!
    - Move to a stable environment
    - Schedule execution
    - Business users, programmers w/ programming hats off
    - Distribute content w/ automated emails
    
    - HOW RStudio Connect makes data products accessible

## SUMMARY

    - bit.ly/reproducible-rmarkdown
    - open source community moves at the speed of light
    - github.com/colearendt
    - Talk on Reproducible R Packages
