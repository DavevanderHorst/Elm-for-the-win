# Elm for the win!

Elm is purely functional programming language. hallo

## Some examples

The first line is a so called type annotation, it describes the input and output type of functions.
In this first case there is only 1 annotation, String, this is the output.

    helloWorld: String
    helloWorld =
        "Hello world!"

A little more complicated example example :
    
    addNumbers: Int -> Int -> Int    
    addNumbers number1 number2 =
        number1 + number2        
        
As you can see AddNumbers needs 2 inputs, number1 and number2, both of these are an Int.
And the output is an Int aswell. 

    -addNumbers: Int (number1) -> 
                                    -Int (number2) -> 
                                                        -Int (output, in this case: number1 + number2)
                                                        
Everything in elm returns something, the last line is always the return type.                                                        
        

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
