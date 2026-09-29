# AndroidDevblog />

<img width="570" height="195" alt="840cee8b164c10b_1440" src="https://github.com/user-attachments/assets/8c84666d-9b10-42ce-96f2-e5dc1f8c2560" />

Kotlin is a modern programming language that helps developers be more productive. For example, Kotlin allows you to be more concise and write
fewer lines of code for the same functionality compared to other programming languages. 
**Apps that are built with Kotlin are also less likely to crash, resulting in a more stable and robust app for users.**
Essentially, with Kotlin, you can write better Android apps in a shorter amount of time. As a result,
Kotlin is gaining momentum in the industry and is the language that the majority of professional Android developers use.
To get started on building Android apps in Kotlin, it's important to first establish a solid foundation of programming concepts in Kotlin. 
**Playground Link = www.play.kotlinlang.org**
      <img width="1830" height="1100" alt="7844a522159be53c_1440" src="https://github.com/user-attachments/assets/6d09fec7-77a2-4ecc-a928-50e62c127ce9" />
**PARTS OF A FUNCTION**
A function is a segment of a program that performs a specific task. Your program may have one or more functions.
*Define versus call a function*
In your code, you define a function first. That means you specify all the instructions needed to perform that task.
Once the function is defined, then you can call that function, so the instructions within that function can be performed or executed.
Here's an analogy. You write out step-by-step instructions on how to bake a chocolate cake. This set of instructions can have a name: bakeChocolateCake. 
Every time you want to bake a cake, you can execute the bakeChocolateCake instructions. If you want 3 cakes, you need to execute the
bakeChocolateCake instructions 3 times.the first step is defining the steps and giving it a name, which is considered defining the function. 
Then you can refer to the steps anytime you want them to be executed, which is considered calling the function.
**Note: You may hear the alternate phrase "declare a function." The words declare and define can be used interchangeably and have the same meaning.
You may also hear the term "function definition" or "function declaration", which refer to the exact code that defines a function. In some other programming languages, 
declare and define have different meanings.**
*Define a function*
These are the key parts needed to define a function:
#The function needs a name, so you can call it later.
#The function can also require some inputs, or information that needs to be provided when the function is called. 
The function uses these inputs to accomplish its purpose. Requiring inputs is optional, and some functions do not require inputs.
#The function also has a body which contains the instructions to perform the task.
      <img width="902" height="348" alt="7132067d45048b93_1440" src="https://github.com/user-attachments/assets/4141d2a8-457c-45c2-8dcd-b9550a7e2ebb" />
to translate the above diagram into Kotlin code, use the following syntax, or format, for defining a function. The order of these elements matters.
The fun word must come first, followed by the function name, followed by the inputs in parentheses, followed by curly braces around the function body.
      <img width="852" height="424" alt="e8b488369268e737_1440" src="https://github.com/user-attachments/assets/b46f0ce7-128e-47d6-bd93-74b2f78ccaff" />
*Notice the key parts of a function within the main function example you saw in the Kotlin Playground:*
*#The function definition starts with the word fun.#*
  Then the name of the function is main.
  There are no inputs to the function, so the parentheses are empty.
  There is one line of code in the function body, println("Hello, world!"), which is located between the opening and closing curly braces of the function.
      <img width="932" height="338" alt="59fb37516122697d_1440" src="https://github.com/user-attachments/assets/0bc8d70b-1174-4152-989f-592999a4d56b" />
Each part of the function is explained in more detail below.
**Function keyword**
To indicate that you're about to define a function in Kotlin, use the special word fun (short for function) on a new line. You must type fun exactly 
as shown in all lowercase letters.\**You can't use func, function, or some alternative spelling because the Kotlin compiler won't recognize what you mean.**
These special words are called keywords in Kotlin and are reserved for a specific purpose, such as creating a new function in Kotlin.
**Function name**
Functions have names so they can be distinguished from each other, similar to how people have names to identify themselves. 
The name of the function is found after the fun keyword.
      <img width="934" height="492" alt="ba432607f21752f4_1440" src="https://github.com/user-attachments/assets/a06c3f55-a88f-4224-ba8f-c83951b0f491" />
Choose an appropriate name for your function based on the purpose of the function.The name is usually a verb or verb phrase.
It's recommended to avoid using a Kotlin keyword as a function name.
Function names should follow the camel case convention, where the first word of the function name is all lower case. 
If there are multiple words in the name, there are no spaces between words, and all other words should begin with a capital letter.
Example function names:
  *calculateTip*
  *displayErrorMessage*
  *takePhoto*
**Function inputs**
Notice that the function name is always followed by parentheses. These parentheses are where you list inputs for the function.
      <img width="926" height="486" alt="6d0b9acf98a9d2e8_1440" src="https://github.com/user-attachments/assets/3336c232-b7ce-423e-90d7-428dc272a39d" />
An input is a piece of data that a function needs to perform its purpose. When you define a function, you can require that certain inputs be passed 
in when the function is called. If there are no inputs required for a function, the parentheses are empty ().
Here are some examples of functions with a different number of inputs:

The following diagram shows a function that is called addOne. The purpose of the function is to add 1 to a given number. 
There is one input, which is the given number. Inside the function body, there is code that adds 1 to the number passed into the function.
        <img width="1664" height="426" alt="2aacdc39be4dafc8_1440" src="https://github.com/user-attachments/assets/b09653ce-2686-4689-be88-375abbd61f9e" />
In this next example, there is a function called printFullName. There are two inputs required for the function, one for the first name and one for the last name.
The function body prints out the first name and last name in the output, to display the person's full name.
      <img width="1066" height="320" alt="51f4d1b94b208dfe_1440" src="https://github.com/user-attachments/assets/1e5f5a54-056d-4069-9695-5fdc60f05ae8" />
This last example shows a function that doesn't require any inputs to be passed in when the function is called. When you call the displayHello() function,
a Hello message gets printed to the output.
                  <img width="676" height="260" alt="2d4050e223850fcf_1440" src="https://github.com/user-attachments/assets/ca0dcbbc-2244-496a-9046-44ff6d064202" />
**Function body**
The function body contains the instructions needed to achieve the purpose of the function. You can locate the function body by looking for the lines of code 
enclosed within the opening and closing curly braces.
            <img width="914" height="506" alt="e012dd6fe687506a_1440" src="https://github.com/user-attachments/assets/15fd30e6-4d71-4200-bae7-99ff6f3e2005" />
            
**Summary**
A Kotlin program requires a main function as the entry point of the program.
To define a function in Kotlin, use the fun keyword, followed by the name of the function, any inputs enclosed in parentheses, 
followed by the function body enclosed in curly braces.
The name of a function should follow camel case convention and start with a lowercase letter.
Use the println() function call to print some text to the output.
Refer to the Kotlin style guide for formatting and code conventions to follow when coding in Kotlin.
Troubleshooting is the process of resolving errors in your code.

**#Create and use variables in Kotlin**
**(In the apps that you use on your phone, notice that some parts of the app stay the same, while other parts change (or are variable).
For example, the names of the categories within the Settings app stay the same – Network & internet, Connected devices, Apps, and more.)**

                  <img width="758" height="1600" alt="72302735e50d7d85_1440" src="https://github.com/user-attachments/assets/25093fea-20bb-4730-a8a1-8d0679c6ffff" />
                  
On the other hand, if you look at a news app, the articles will change often. The article name, source, time posted, and images change.
How do you write your code so that content changes over time? You can't rewrite the code in your app every time there are new articles to post, 
which happens every day, every hour, and every minute!In this codelab, you learn how to write code that uses variables so that certain parts
of your program can change without having to write a whole new set of instructions. You will use the Kotlin Playground as you did in the previous note.

**#Variables and data types**


