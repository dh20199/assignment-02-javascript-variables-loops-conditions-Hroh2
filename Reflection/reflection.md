# Reflection

## Question 1 (50 words)
#### When and why should you use a function like `carefulSubract` rather than `subtract`? 

Function like "carefulsubstract" places parameters into two or more categories before processing them, and this function asks the user to place the parameters. If the input is incorrect, the user will be told what the correct input ought to be. By contrast, a function like "subtract" does not differntiate between parameters, or tell the user what is wrong with their input. 

## Question 2 (100 words)
#### What are `data types`, and how does data typing work in JavaScript? Name at least 4 built-in data JS data types. 

Data types are the variables that exist in coding, and they are done through three methods of statistically, dynamically and weakly. In JavaScript, there are seven basic data types: number, string, boolean, "null" value, "undefined" value, objects and symbols, and the typeof operator. Since JavaScript is a dynamically typed programming language - capable of working with a variety of data types, it automatically identifies each data type through syntax. For example, it uses square bracketes to indicate the data as an array, curly brakcets as an object, single quotation marks as a string and etc.

## Question 3 (100 words)
#### What is the advantage to storing information as an object (`{firstName: 'Italo', lastName: 'Calvino', profession: 'novelist' }`) rather than as an array (`['Italo', 'Calvino', 'novelist']`)? Are there any disadvantages?

An object refers to a variable with names parts, and each part called a property. The parts are not related to one another and may be dealt separately, however, when in an array, the elements are not separable. The advantages of storing information as an object are that they are easier to access as there is no need to use index by just calling the keys with names like "firstName", they are more efficient by improving the total running time of the function due to its fast access, and it has a clear format with correspondence between the key and the value. The disadvantages are the larger storage required, and the index of each pair is changing. 

## Question 4 (150 words)
#### The function `sentences` transforms a data structure (in this case, a list of object literals) into a sequence of sentences. If the data structure were less predictable (e.g., if some properties of each object were occasionally missing, or if their data type was not always the same), what programming techniques could you use to ensure that your function produced a coherent output? Also, can you think of a more interesting "transform" that could be done with the same data structure?

If the data structure were less predictable, which refers to cases of missing properties from certain objects or when their data types were not the same, one could produce a coherent output by adding conditionals to the function. By using conditionals which perform the duty of categorizing data type before and produce results that are appropriate according to the pre-set conditions, the function may be able to process more complicated data. In turn, this function will be able to change data sets into sentences with the same basic structure. For example, rather than only stating the names of major battles during WWII, the function may also be able to provide brief summaries, dates and historical figures of the numerous battles. By utilizing computing, rather than manual power, information may be more easily transformed into paragraphs with similar structure - permitting an easier reading process for the reader.