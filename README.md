# Grokking-Functional-Programming

- contents
- preface xix
- acknowledgments xxi
- about this book xxiii
- about the author xxvii

## Part 1 the functional toolkit . . . . . . . . . . . . . . . . . . .1

### 1 Learning functional programming 3
01 Perhaps you picked up this book because... 4
02 What do you need to know before we start? 5
03 What do functions look like? 6 
04 Meet the function 7 
05 When the code lies... 8
06 Imperative vs. declarative 9 
07 Coffee break: Imperative vs. declarative 10
08 Coffee break explained: Imperative vs. declarative 11
09 How useful is learning functional programming? 12
10 Leaping into Scala 13
11 Practicing functions in Scala 14
12 Getting your tools ready 15
13 v
14 
15 vi
16 contents
17 Getting to know the REPL 16
18 Writing your first functions! 17
19 How to use this book 18

### 2 Pure functions 21
Why do we need pure functions? 22
Coding imperatively 23 
Breaking the code 24
Passing copies of the data 25
Breaking the code...again 26 
Recalculating instead of storing 27
Focusing on the logic by passing the state 28
Where did the state go? 29
The difference between impure and pure functions 30 
Coffee break: Refactoring to a pure function 31 
Coffee break explained: Refactoring to a pure function 32 
In pure functions we trust 34 
Pure functions in programming languages 35 
Difficulty of staying pure... 36 
Pure functions and clean code 37 
Coffee break: Pure or impure? 38 
Coffee break explained: Pure or impure? 39
Using Scala to write pure functions 40 
Practicing pure functions in Scala 41 
Testing pure functions 42 
Coffee break: Testing pure functions 43 
Coffee break explained: Testing pure functions 44

## 3 Immutable values 47
The fuel for the engine 48 
Another case for immutability 49 
Can you trust this function? 50
vi

vii
Mutability is dangerous 51
Functions that lie...again 52 
Fighting mutability by working with copies 53 
Coffee break: Getting burned by mutability 54 
Coffee break explained: Getting burned by mutability 55 
Introducing shared mutable state 58 
State’s impact on programming abilities 59 
Dealing with the moving parts 60 
Dealing with the moving parts using FP 61 
Immutable values in Scala 62 
Building our intuition about immutability 63 
Coffee break: The immutable String API 64 
Coffee break explained: The immutable String API 65 
Hold on...Isn’t this bad? 66 
Purely functional approach to shared mutable state 67 
Practicing immutable slicing and appending 69
vii

## 4 Functions as values 71
Implementing requirements as functions 72 
Impure functions and mutable values strike back 73 
Using Java Streams to sort the list 74 
Function signatures should tell the whole story 75 
Changing requirements 76 We just pass the code around! 77 
Using Java’s Function values 78 
Using the Function syntax to deal with code duplication 79 
Passing user-defined functions as arguments 80 
Coffee break: Functions as parameters 81 
Coffee break explained: Functions as parameters 82 
Problems with reading functional Java 83 
Passing functions in Scala 84 
Deep dive into sortBy 85 
Signatures with function parameters in Scala 86

contents vii
   
viii
contents
Passing functions as arguments in Scala 87
Practicing function passing 88 
Embracing declarative programming 89
Passing functions to custom-made functions 90 
Small functions and their responsibilities 91 
Passing functions inline 92 
Coffee break: Passing functions in Scala 93 
Coffee break explained: Passing functions in Scala 94 
What else can we achieve just by passing functions? 95 
Applying a function to each element of a list 96 
Applying a function to each element of a list using map 97 
Getting to know map 98 
Practicing map 99 
Learn once, use everywhere 100 
Returning parts of the list based on a condition 101 
Returning parts of the list using filter 102 
Getting to know filter 103 Practicing filter 104 Our journey so far... 105 Don’t repeat yourself? 106 Is my API easy to use? 107 Adding a new parameter is not enough 108 Functions can return functions 109 Using functions that can return functions 110 Functions are values 111 Coffee break: Returning functions 112 Coffee break explained: Returning functions 113 Designing functional APIs 114 Iterative design of functional APIs 115 Returning functions from returned functions 116 How to return functions from returned functions 117 Using the flexible API built with returned functions 118 Using multiple parameter lists in functions 119 We have been currying! 120 Practicing currying 121

Programming by passing function values 122 Reducing many values into a single value 123 Reducing many values into a single one using foldLeft 124 Getting to know foldLeft 125 foldLeft must-knows 126 Practicing foldLeft 127 Modeling immutable data 128 Using product types with higher-order functions 129 More concise syntax for inline functions 130
Part 2 functional Programs . . . . . . . . . . . . . . . . . . . .133
5 Sequential programs 135
Writing pipeline-based algorithms 136 Composing larger programs from smaller pieces 137 The imperative approach 138 flatten and flatMap 139 Practical use case of using more flatMaps 140 flatMap and changing the size of the list 141 Coffee break: Dealing with lists of lists 142 Coffee break explained: Dealing with lists of lists 143 Chained flatMaps and maps 144 Nested flatMaps 145 Values that depend on other values 146 Practicing nested flatMaps 147 A better syntax for nested flatMaps 148 For comprehensions to the rescue! 149 Coffee break: flatMaps vs. for comprehensions 150 Coffee break explained: flatMaps vs. for comprehensions 151 Getting to know for comprehensions 152 It’s not the for you are looking for! 153 Inside a for comprehension 154 More sophisticated for comprehensions 155
contents ix
   
x
contents
6
Checking all combinations using a for comprehension 156 Filtering techniques 157 Coffee break: Filtering techniques 158 Coffee break explained: Filtering techniques 159 Looking for a greater abstraction 160 Comparing map, foldLeft, and flatMap 161 Using for comprehensions with Sets 162 Using for comprehensions with many types 163 Practicing for comprehensions 164 Defining for comprehensions... again 165 Using for comprehensions with noncollection types 166 Avoiding nulls: Option type 167 Parsing as a pipeline 168 Coffee break: Parsing with Option 169 Coffee break explained: Parsing with Option 170
Error handling 173
Handling lots of different errors, gracefully 174 Is it even possible to handle them all? 175 Sort the list of TV shows by their running time 176 Implementing the sorting requirement 177 Dealing with data coming from the outside world 178 Functional design: Building from small blocks 179 Parsing Strings into immutable objects 180 Parsing a List is just parsing one element 181 Parsing a String into a TvShow 182 What about potential errors? 183 Is returning null a good idea? 184 How do we handle potential errors more gracefully? 185 Implementing a function that returns an Option 186 Option forces us to handle possible errors 187 Building from small blocks 188 Functional design is building from small blocks 189
   
contents xi
Writing a small, safe function that returns an Option 190 Functions, values, and expressions 192 Practicing safe functions that return Options 193 How do errors propagate? 194 Values represent errors 195 Option, for comprehensions, and checked exceptions... 196 What about checked exceptions? 197 Conditional recovery 198 Conditional recovery using the imperative style 199 Checked exceptions don’t compose—Options do! 201 How does orElse work? 202 Practicing functional error handling 203 Functions compose, even in the presence of errors 204 Compiler reminds us that errors need to be covered 205 Compilation errors are good for us! 206 Transforming a List of Options into a flat List 207 Let the compiler be our guide... 208 ...but let’s not trust the compiler too much! 209 Coffee break: Error-handling strategies 210 Coffee break explained: Error-handling strategies 211 Two different error-handling strategies 212 All-or-nothing error-handling strategy 213 Folding a List of Options into an Option of a List 214 We now know how to handle multiple possible errors! 215 How to know what failed 216 We need to convey error details in the return value 217 Conveying error details using Either 218 Refactoring to Either 219 Returning an Either instead of an Option 220 Practicing safe functions that return Either 223 What we learned about Option works with Either 224 Coffee break: Error handling using Either 225 Coffee break explained: Error handling using Either 226 Working with Option/Either 227

xii
contents
7
Requirements as types 229
Modeling data to minimize programmers’ mistakes 230 Well-modeled data can’t lie 231 Designing using what we know so far (which is primitive types) 232 Using data modeled as primitive types 233 Coffee break: The pain of primitive types 234 Coffee break explained: The pain of primitive types 235 Problems with the primitive type approach to modeling 236 Using primitive types makes our jobs harder! 237 Newtypes protect against misplaced parameters 238 Using newtypes in data models 239 Practicing newtypes 240 Making sure only valid data combinations are possible 241 Modeling possibility of absence in your data 242 Changes in the model force changes in the logic 243 Using data modeled as Options in your logic 244 Higher-order functions for the win! 245 There is probably a higher-order function for that! 246 Coffee break: forall/exists/contains 247 Coffee break explained: forall/exists/contains 248 Coupling a concept inside a single product type 249 Modeling finite possibilities 250 Using sum types 251 Even better modeling with sum types 252 Using the sum type + product type combo 253 Product types + sum types = algebraic data types (ADTs) 254 Using ADT-based models in behaviors (functions) 255 Destructuring ADTs using pattern matching 256 Duplication and DRY 257 Practicing pattern matching 258 Newtypes, ADTs, and pattern matching in the wild 259 What about inheritance? 260 Coffee break: Functional data design 261 Coffee break explained: Functional data design 262
   
Modeling behaviors 263 Modeling behaviors as data 264 Implementing functions with ADT-based parameters 265 Coffee break: Design and maintainability 266 Coffee break explained: Design and maintainability 267
8 IO as values 269
Talking to the outside world 270 Integrating with an external API 271 Properties of a side-effectful IO action 272 Imperative solution to side-effecting IO code 273 Problems with the imperative approach to IO 274 Can we really do better using FP? 275 Doing IO vs. using IO’s result 276 Handling IO imperatively 277 Computations as IO values 278 IO values 279 IO values in the wild 280 Pushing the impurity out 281 Using values fetched from two IO actions 282 Combining two IO values into a single IO value 283 Practicing creating and combining IO values 284 Disentangling concerns by working with values only 285 The IO type is viral 286 Coffee break: Working with values 287 Coffee break explained: Working with values 288 Toward functional IO 289 What about IO failures? 290 Running a program described by IO may fail! 291 Remember orElse? 292 Lazy and eager evaluation 293 Implementing recovery strategies using IO.orElse 294 Implementing fallbacks using orElse and pure 295
contents xiii
   
xiv
contents
9
Practicing failure recovery in IO values 296 Where should we handle potential failures? 297 Toward functional IO with failure handling 298 Pure functions don’t lie, even in the unsafe world! 299 Functional architecture 300 Using IO to store data 301 Coffee break: Using IO to store data 304 Coffee break explained: Using IO to store data 305 Treating everything as values 306 Treating retries as values 307 Treating an unknown number of API calls as values 309 Practicing functional signature intuitions 311
Streams as values 313
To infinity and beyond 314 Dealing with an unknown number of values 315 Dealing with external impure API calls (again) 316 The functional approach to the design 317 Immutable maps 318 Practicing immutable maps 319 How many IO calls should we make? 320 The bottom-up design 321 Advanced list operations 322 Introducing tuples 323 Zipping and dropping 324 Pattern matching on tuples 325 Coffee break: Working with maps and tuples 326 Coffee break explained: Working with maps and tuples 327 Functional jigsaw puzzle 328 Following types in a bottom-up design 329 Prototyping and dead ends 330 Recursive functions 331 Infinity and laziness 332
   
Recursive function structure 333 Dealing with an absence in the future (using recursion) 334 Usefulness of infinite recursive calls 335 Coffee break: Recursion and infinity 336 Coffee break explained: Recursion and infinity 337 Creating different IO programs using recursion 338 Using recursion to make an arbitrary number of calls 339 Problems with the recursive version 340 Introducing data streams 341 Streams in imperative languages 342 Values on demand 343 Stream processing, producers, and consumers 344 Streams and IO 345 The functional Stream 346 Streams in FP are values 347 Streams are recursive values 348 Primitive operations and combinators 349 Streams of IO-based values 350 Infinite streams of IO-based values 351 Executing for side effects 352 Practicing stream operations 353 Using streams to our advantage 354 Infinite stream of API calls 355 Handling IO failures in streams 356 Separated concerns 357 Sliding windows 358 Waiting between IO calls 360 Zipping streams 361 Benefits of using the stream-based approach 362
10 Concurrentprograms 365 Threads, threads everywhere 366
Declarative concurrency 367
contents xv
   
xvi
contents
Sequential vs. concurrent
Coffee break: Sequential thinking
Coffee break explained: Sequential thinking 370 The need for batching 371 Batching implementation 372 The concurrent world 373 The concurrent state 374 Imperative concurrency 375 Atomic references 377 Introducing Ref 378 Updating Ref values 379 Using Ref values 380 Making it all concurrent 381 parSequence in action 382 Practicing concurrent IOs 384 Modeling concurrency 385 Coding using Refs and fibers 386 IOs that run infinitely 388 Coffee break: Concurrent thinking 389 Coffee break explained: Concurrent thinking 390 The need for asynchronicity 391 Preparing for asynchronous access 392 Designing functional asynchronous programs 393 Managing fibers manually 394 Coding functional asynchronous programs 395

Part 3 aPPlied functional Programming .  .  .  .  .  .  .  .  .  .  .397

## 11 Designing functional programs 399
Make it work, make it right, make it fast 400 
Modeling using immutable values 401 
Business domain modeling and FP 402 
Data access modeling 403

368 369
   
A bag of functions 404
Business logic as a pure function 405 
Separating the real data access concern 406 
Integrating with APIs using imperative libraries and IO 407 
Following the design 410 
Implementing input actions as IO values 411 
Separating the library IO from other concerns 413 
Currying and inversion of control 414 
Functions as values 415 
Connecting the dots 416 
We made it work 417 
Making it right 418 
Resource leaks 419 
Handling resources 420 
Using a Resource value 421 
We made it right 422 
Coffee break: Make it fast 423 
Coffee break explained: Make it fast 424

## 12 Testingfunctionalprograms 427
Do you have tests for that? 428 
Tests are just functions 429 
Choosing functions to test 430 
Testing by providing examples 431 
Practicing testing by example 432 
Generating good examples 433 
Generating properties 434 
Property-based testing 435 
Testing by providing properties 436 
Delegating the work by passing functions 437 
Understanding failures of property-based tests 438 
Wrong test or a bug? 439 
Custom generators 440

contents xvii
   
xviii
contents
Appendix A 481
Appendix B 477
index

Scala cheat sheet 471 
Functional gems 
Using custom generators
Testing more complicated scenarios in a readable way 442 
Finding and fixing bugs in the implementation 443 
Coffee break: Property-based tests 444 
Coffee break explained: Property-based tests 445 
Properties and examples 446 
Requirements coverage 447 
Testing side-effectful requirements 448 
Identifying the right test for the job 449 
Data usage tests 450 
Practicing stubbing external services using IO 452 
Testing and design 453 
Service integration tests 454 
Local servers as Resources in integration tests 455 
Writing isolated integration tests 456 
Integration with a service is a single responsibility 457 
Coffee break: Writing integration tests 458 
Coffee break explained: Writing integration tests 459 
Integration tests take more time 460 
Property-based integration tests 461 
Choosing the right testing approach 462 
Test-driven development 463 
Writing a test for a feature that doesn’t exist 464 
Red-green-refactor 465 Making tests green 466 
Adding more red tests 467 The last TDD iteration 468
441
