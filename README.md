# Grokking Functional Programming

- contents
- preface xix
- acknowledgments xxi
- about this book xxiii
- about the author xxvii

## Part 1 the functional toolkit . . . . . . . . . . . . . . . . . . .1

### 1 Learning functional programming 3
- [ ] 01 Perhaps you picked up this book because... 4
- [ ] 02 What do you need to know before we start? 5
- [ ] 03 What do functions look like? 6 
- [ ] 04 Meet the function 7 
- [ ] 05 When the code lies... 8
- [ ] 06 Imperative vs. declarative 9 
- [ ] 07 Coffee break: Imperative vs. declarative 10
- [ ] 08 Coffee break explained: Imperative vs. declarative 11
- [ ] 09 How useful is learning functional programming? 12
- [ ] 10 Leaping into Scala 13
- [ ] 11 Practicing functions in Scala 14
- [ ] 12 Getting your tools ready 15
- [ ] 13 v
- [ ] 14 
- [ ] 15 vi
- [ ] 16 contents
- [ ] 17 Getting to know the REPL 16
- [ ] 18 Writing your first functions! 17
- [ ] 19 How to use this book 18

### 2 Pure functions 21
- [ ] 20 Why do we need pure functions? 22
- [ ] 21 Coding imperatively 23 
- [ ] 22 Breaking the code 24
- [ ] 23 Passing copies of the data 25
- [ ] 24 Breaking the code...again 26 
- [ ] 25 Recalculating instead of storing 27
- [ ] 26 Focusing on the logic by passing the state 28
- [ ] 27 Where did the state go? 29
- [ ] 28 The difference between impure and pure functions 30 
- [ ] 29 Coffee break: Refactoring to a pure function 31 
- [ ] 30 Coffee break explained: Refactoring to a pure function 32 
- [ ] 31 In pure functions we trust 34 
- [ ] 32 Pure functions in programming languages 35 
- [ ] 33 Difficulty of staying pure... 36 
- [ ] 34 Pure functions and clean code 37 
- [ ] 35 Coffee break: Pure or impure? 38 
- [ ] 36 Coffee break explained: Pure or impure? 39
- [ ] 37 Using Scala to write pure functions 40 
- [ ] 38 Practicing pure functions in Scala 41 
- [ ] 39 Testing pure functions 42 
- [ ] 40 Coffee break: Testing pure functions 43 
- [ ] 41 Coffee break explained: Testing pure functions 44

## 3 Immutable values 47
- [ ] 42 The fuel for the engine 48 
- [ ] 43 Another case for immutability 49 
- [ ] 44 Can you trust this function? 50
- [ ] 45 vi
- [ ] 46 vii
- [ ] 47 Mutability is dangerous 51
- [ ] 48 Functions that lie...again 52 
- [ ] 49 Fighting mutability by working with copies 53 
- [ ] 50 Coffee break: Getting burned by mutability 54 
- [ ] 51 Coffee break explained: Getting burned by mutability 55 
- [ ] 52 Introducing shared mutable state 58 
- [ ] 53 State’s impact on programming abilities 59 
- [ ] 54 Dealing with the moving parts 60 
- [ ] 55 Dealing with the moving parts using FP 61 
- [ ] 56 Immutable values in Scala 62 
- [ ] 57 Building our intuition about immutability 63 
- [ ] 58 Coffee break: The immutable String API 64 
- [ ] 59 Coffee break explained: The immutable String API 65 
- [ ] 60 Hold on...Isn’t this bad? 66 
- [ ] 61 Purely functional approach to shared mutable state 67 
- [ ] 62 Practicing immutable slicing and appending 69

## 4 Functions as values 71
- [ ] 64 Implementing requirements as functions 72 
- [ ] 65 Impure functions and mutable values strike back 73 
- [ ] 66 Using Java Streams to sort the list 74 
- [ ] 67 Function signatures should tell the whole story 75 
- [ ] 68 Changing requirements 76 We just pass the code around! 77 
- [ ] 69 Using Java’s Function values 78 
- [ ] 70 Using the Function syntax to deal with code duplication 79 
- [ ] 71 Passing user-defined functions as arguments 80 
- [ ] 72 Coffee break: Functions as parameters 81 
- [ ] 73 Coffee break explained: Functions as parameters 82 
- [ ] 74 Problems with reading functional Java 83 
- [ ] 75 Passing functions in Scala 84 
- [ ] 76 Deep dive into sortBy 85 
- [ ] 77 Signatures with function parameters in Scala 86
- [ ] 78 contents vii   
- [ ] 79 viii contents
- [ ] 81 Passing functions as arguments in Scala 87
- [ ] 82 Practicing function passing 88 
- [ ] 83 Embracing declarative programming 89
- [ ] 84 Passing functions to custom-made functions 90 
- [ ] 85 Small functions and their responsibilities 91 
- [ ] 86 Passing functions inline 92 
- [ ] 87 Coffee break: Passing functions in Scala 93 
- [ ] 88 Coffee break explained: Passing functions in Scala 94 
- [ ] 89 What else can we achieve just by passing functions? 95 
- [ ] 90 Applying a function to each element of a list 96 
- [ ] 91 Applying a function to each element of a list using map 97 
- [ ] 92 Getting to know map 98 
- [ ] 93 Practicing map 99 
- [ ] 94 Learn once, use everywhere 100 
- [ ] 95 Returning parts of the list based on a condition 101 
- [ ] 96 Returning parts of the list using filter 102 
- [ ] 97 Getting to know filter 103 
- [ ] 98 Practicing filter 104 
- [ ] 99 Our journey so far...105
- [ ] 100 Don’t repeat yourself? 106
- [ ] 101 Is my API easy to use? 107
- [ ] 102 Adding a new parameter is not enough 108 
- [ ] 103 Functions can return functions 109 
- [ ] 104 Using functions that can return functions 110 
- [ ] 105 Functions are values 111 
- [ ] 106 Coffee break: Returning functions 112 
- [ ] 107 Coffee break explained: Returning functions 113 
- [ ] 108 Designing functional APIs 114 
- [ ] 109 Iterative design of functional APIs 115 
- [ ] 110 Returning functions from returned functions 116 
- [ ] 111 How to return functions from returned functions 117 
- [ ] 112 Using the flexible API built with returned functions 118 
- [ ] 113 Using multiple parameter lists in functions 119 
- [ ] 114 We have been currying! 120 
- [ ] 115 Practicing currying 121
- [ ] 116 Programming by passing function values 122
- [ ] 117 Reducing many values into a single value 123
- [ ] 118 Reducing many values into a single one using foldLeft 124 
- [ ] 119 Getting to know foldLeft
- [ ] 120 foldLeft must-knows 126 
- [ ] 121 Practicing foldLeft 127 
- [ ] 122 Modeling immutable data 128 
- [ ] 123 Using product types with higher-order functions 129 
- [ ] 124 More concise syntax for inline functions 130

## Part 2 functional Programs . . . . . . . . . . . . . . . . . . . .133

### 5 Sequential programs 135
- [ ] 125 Writing pipeline-based algorithms 136
- [ ] 126 Composing larger programs from smaller pieces 137
- [ ] 127 The imperative approach 138 
- [ ] 128 flatten and flatMap 139 
- [ ] 129 Practical use case of using more flatMaps 140 
- [ ] 130 flatMap and changing the size of the list 141 
- [ ] 131 Coffee break: Dealing with lists of lists 142 
- [ ] 132 Coffee break explained: Dealing with lists of lists 143
- [ ] 133 Chained flatMaps and maps 144 
- [ ] 134 Nested flatMaps 145 
- [ ] 135 Values that depend on other values 146
- [ ] 136 Practicing nested flatMaps 147 
- [ ] 137 A better syntax for nested flatMaps 148 
- [ ] 138 For comprehensions to the rescue! 149
- [ ] 139 Coffee break: flatMaps vs. for comprehensions 150 
- [ ] 140 Coffee break explained: flatMaps vs. for comprehensions 151
- [ ] 141 Getting to know for comprehensions 152
- [ ] 142 It’s not the for you are looking for! 153
- [ ] 143 Inside a for comprehension 154 
- [ ] 144 More sophisticated for comprehensions 155
- [ ] 145 contents ix
- [ ] 146 x contents 6
- [ ] 147 Checking all combinations using a for comprehension 156
- [ ] 148 Filtering techniques 157 
- [ ] 149 Coffee break: Filtering techniques 158 
- [ ] 150 Coffee break explained: Filtering techniques 159 
- [ ] 151 Looking for a greater abstraction 160 
- [ ] 152 Comparing map, foldLeft, and flatMap 161 
- [ ] 153 Using for comprehensions with Sets 162 
- [ ] 154 Using for comprehensions with many types 163 
- [ ] 155 Practicing for comprehensions 164 
- [ ] 156 Defining for comprehensions...again 165 
- [ ] 157 Using for comprehensions with noncollection types 166 
- [ ] 158 Avoiding nulls: Option type 167 
- [ ] 159 Parsing as a pipeline 168 
- [ ] 160 Coffee break: Parsing with Option 169 
- [ ] 161 Coffee break explained: Parsing with Option 170

### 6 Error handling 173
- [ ] 162 Handling lots of different errors, gracefully 174
- [ ] 163 Is it even possible to handle them all? 175 
- [ ] 164 Sort the list of TV shows by their running time 176 
- [ ] 165 Implementing the sorting requirement 177 
- [ ] 166 Dealing with data coming from the outside world 178 
- [ ] 167 Functional design: Building from small blocks 179 
- [ ] 168 Parsing Strings into immutable objects 180 
- [ ] 169 Parsing a List is just parsing one element 181 
- [ ] 170 Parsing a String into a TvShow 182 
- [ ] 171 What about potential errors? 183 
- [ ] 172 Is returning null a good idea? 184 
- [ ] 173 How do we handle potential errors more gracefully? 185 
- [ ] 174 Implementing a function that returns an Option 186 
- [ ] 175 Option forces us to handle possible errors 187 
- [ ] 176 Building from small blocks 188 
- [ ] 177 Functional design is building from small blocks 189
- [ ] 178 contents xi
- [ ] 179 Writing a small, safe function that returns an Option 190 
- [ ] 180 Functions, values, and expressions 192 
- [ ] 181 Practicing safe functions that return Options 193 
- [ ] 182 How do errors propagate? 194 
- [ ] 183 Values represent errors 195 
- [ ] 184 Option, for comprehensions, and checked exceptions... 196 
- [ ] 185 What about checked exceptions? 197 
- [ ] 186 Conditional recovery 198 
- [ ] 187 Conditional recovery using the imperative style 199 
- [ ] 188 Checked exceptions don’t compose—Options do! 201 
- [ ] 189 How does orElse work? 202 
- [ ] 190 Practicing functional error handling 203 
- [ ] 191 Functions compose, even in the presence of errors 204 
- [ ] 192 Compiler reminds us that errors need to be covered 205 
- [ ] 193 Compilation errors are good for us! 206 
- [ ] 194 Transforming a List of Options into a flat List 207 
- [ ] 195 Let the compiler be our guide... 208 ...but let’s not trust the compiler too much! 209 
- [ ] 196 Coffee break: Error-handling strategies 210 
- [ ] 197 Coffee break explained: Error-handling strategies 211 
- [ ] 198 Two different error-handling strategies 212 
- [ ] 199 All-or-nothing error-handling strategy 213 
- [ ] 200 Folding a List of Options into an Option of a List 214 
- [ ] 201 We now know how to handle multiple possible errors! 215 
- [ ] 202 How to know what failed 216 
- [ ] 203 We need to convey error details in the return value 217 
- [ ] 204 Conveying error details using Either 218 
- [ ] 205 Refactoring to Either 219 
- [ ] 206 Returning an Either instead of an Option 220 
- [ ] 207 Practicing safe functions that return Either 223 
- [ ] 208 What we learned about Option works with Either 224 
- [ ] 209 Coffee break: Error handling using Either 225 
- [ ] 210 Coffee break explained: Error handling using Either 226 
- [ ] 211 Working with Option/Either 227
- [ ] 212 xii contents 

### 7 Requirements as types 229
- [ ] 213 Modeling data to minimize programmers’ mistakes 230 
- [ ] 214 Well-modeled data can’t lie 231 
- [ ] 215 Designing using what we know so far (which is primitive types) 232 
- [ ] 216 Using data modeled as primitive types 233 
- [ ] 217 Coffee break: The pain of primitive types 234 
- [ ] 218 Coffee break explained: The pain of primitive types 235 
- [ ] 219 Problems with the primitive type approach to modeling 236 
- [ ] 220 Using primitive types makes our jobs harder! 237 
- [ ] 221 Newtypes protect against misplaced parameters 238 
- [ ] 222 Using newtypes in data models 239 
- [ ] 223 Practicing newtypes 240 
- [ ] 224 Making sure only valid data combinations are possible 241 
- [ ] 225 Modeling possibility of absence in your data 242 
- [ ] 226 Changes in the model force changes in the logic 243 
- [ ] 227 Using data modeled as Options in your logic 244 
- [ ] 228 Higher-order functions for the win! 245 
- [ ] 229 There is probably a higher-order function for that! 246 
- [ ] 230 Coffee break: forall/exists/contains 247 
- [ ] 231 Coffee break explained: forall/exists/contains 248 
- [ ] 232 Coupling a concept inside a single product type 249 
- [ ] 233 Modeling finite possibilities 250 
- [ ] 234 Using sum types 251 
- [ ] 235 Even better modeling with sum types 252 
- [ ] 236 Using the sum type + product type combo 253 
- [ ] 237 Product types + sum types = algebraic data types (ADTs) 254 
- [ ] 238 Using ADT-based models in behaviors (functions) 255 
- [ ] 239 Destructuring ADTs using pattern matching 256 
- [ ] 240 Duplication and DRY 257 
- [ ] 241 Practicing pattern matching 258 
- [ ] 242 Newtypes, ADTs, and pattern matching in the wild 259 
- [ ] 243 What about inheritance? 260 
- [ ] 244 Coffee break: Functional data design 261 
- [ ] 245 Coffee break explained: Functional data design 262
- [ ] 246 Modeling behaviors 263 
- [ ] 247 Modeling behaviors as data 264 
- [ ] 248 Implementing functions with ADT-based parameters 265 
- [ ] 249 Coffee break: Design and maintainability 266 
- [ ] 250 Coffee break explained: Design and maintainability 267

### 8 IO as values 269
- [ ] 251 Talking to the outside world 270
- [ ] 252 Integrating with an external API 271 
- [ ] 253 Properties of a side-effectful IO action 272 
- [ ] 254 Imperative solution to side-effecting IO code 273 
- [ ] 255 Problems with the imperative approach to IO 274 
- [ ] 256 Can we really do better using FP? 275 
- [ ] 257 Doing IO vs. using IO’s result 276 
- [ ] 258 Handling IO imperatively 277 
- [ ] 259 Computations as IO values 278 
- [ ] 260 IO values 279 
- [ ] 261 IO values in the wild 280 
- [ ] 262 Pushing the impurity out 281 
- [ ] 263 Using values fetched from two IO actions 282 
- [ ] 264 Combining two IO values into a single IO value 283 
- [ ] 265 Practicing creating and combining IO values 284 
- [ ] 266 Disentangling concerns by working with values only 285 
- [ ] 267 The IO type is viral 286 
- [ ] 268 Coffee break: Working with values 287 
- [ ] 269 Coffee break explained: Working with values 288 
- [ ] 270 Toward functional IO 289 
- [ ] 271 What about IO failures? 290 
- [ ] 272 Running a program described by IO may fail! 291 
- [ ] 273 Remember orElse? 292 
- [ ] 274 Lazy and eager evaluation 293 
- [ ] 275 Implementing recovery strategies using IO.orElse 294 
- [ ] 276 Implementing fallbacks using orElse and pure 295
- [ ] 277 contents xiii
- [ ] 278 xiv contents
- [ ] 279 Practicing failure recovery in IO values 296 
- [ ] 280 Where should we handle potential failures? 297 
- [ ] 281 Toward functional IO with failure handling 298 
- [ ] 282 Pure functions don’t lie, even in the unsafe world! 299 
- [ ] 283 Functional architecture 300 
- [ ] 284 Using IO to store data 301 
- [ ] 285 Coffee break: Using IO to store data 304 
- [ ] 286 Coffee break explained: Using IO to store data 305 
- [ ] 287 Treating everything as values 306 
- [ ] 288 Treating retries as values 307 
- [ ] 289 Treating an unknown number of API calls as values 309 
- [ ] 290 Practicing functional signature intuitions 311

### 9 Streams as values 313
- [ ] 291 To infinity and beyond 314
- [ ] 292 Dealing with an unknown number of values 315 
- [ ] 293 Dealing with external impure API calls (again) 316 
- [ ] 294 The functional approach to the design 317 
- [ ] 295 Immutable maps 318 
- [ ] 296 Practicing immutable maps 319 
- [ ] 297 How many IO calls should we make? 320 
- [ ] 298 The bottom-up design 321 
- [ ] 299 Advanced list operations 322 
- [ ] 300 Introducing tuples 323 
- [ ] 301 Zipping and dropping 324 
- [ ] 302 Pattern matching on tuples 325 
- [ ] 303 Coffee break: Working with maps and tuples 326 
- [ ] 304 Coffee break explained: Working with maps and tuples 327 
- [ ] 305 Functional jigsaw puzzle 328 
- [ ] 306 Following types in a bottom-up design 329 
- [ ] 307 Prototyping and dead ends 330 
- [ ] 308 Recursive functions 331 
- [ ] 309 Infinity and laziness 332   
- [ ] 310 Recursive function structure 333 
- [ ] 311 Dealing with an absence in the future (using recursion) 334 
- [ ] 312 Usefulness of infinite recursive calls 335 
- [ ] 313 Coffee break: Recursion and infinity 336 
- [ ] 314 Coffee break explained: Recursion and infinity 337 
- [ ] 315 Creating different IO programs using recursion 338 
- [ ] 316 Using recursion to make an arbitrary number of calls 339 
- [ ] 317 Problems with the recursive version 340 
- [ ] 318 Introducing data streams 341 
- [ ] 319 Streams in imperative languages 342 
- [ ] 320 Values on demand 343 
- [ ] 321 Stream processing, producers, and consumers 344 
- [ ] 322 Streams and IO 345 
- [ ] 323 The functional Stream 346 
- [ ] 324 Streams in FP are values 347 
- [ ] 325 Streams are recursive values 348 
- [ ] 326 Primitive operations and combinators 349 
- [ ] 327 Streams of IO-based values 350 
- [ ] 328 Infinite streams of IO-based values 351 
- [ ] 329 Executing for side effects 352 
- [ ] 330 Practicing stream operations 353 
- [ ] 331 Using streams to our advantage 354 
- [ ] 332 Infinite stream of API calls 355 
- [ ] 333 Handling IO failures in streams 356 
- [ ] 334 Separated concerns 357 
- [ ] 335 Sliding windows 358 
- [ ] 336 Waiting between IO calls 360 
- [ ] 337 Zipping streams 361 
- [ ] 338 Benefits of using the stream-based approach 362

### 10 Concurrent Programs 365 
- [ ] 339 Threads, threads everywhere 366
- [ ] 340 Declarative concurrency 367
- [ ] 341 contents xv
- [ ] 342 xvi contents
- [ ] 343 Sequential vs. concurrent
- [ ] 344 Coffee break: Sequential thinking
- [ ] 345 Coffee break explained: Sequential thinking 370 
- [ ] 346 The need for batching 371 
- [ ] 347 Batching implementation 372 
- [ ] 348 The concurrent world 373 
- [ ] 349 The concurrent state 374 
- [ ] 350 Imperative concurrency 375 
- [ ] 351 Atomic references 377 
- [ ] 352 Introducing Ref 378 
- [ ] 353 Updating Ref values 379 
- [ ] 354 Using Ref values 380 
- [ ] 355 Making it all concurrent 381 
- [ ] 356 parSequence in action 382 
- [ ] 357 Practicing concurrent IOs 384 
- [ ] 358 Modeling concurrency 385 
- [ ] 359 Coding using Refs and fibers 386 
- [ ] 360 IOs that run infinitely 388 
- [ ] 361 Coffee break: Concurrent thinking 389 
- [ ] 362 Coffee break explained: Concurrent thinking 390 
- [ ] 363 The need for asynchronicity 391 
- [ ] 364 Preparing for asynchronous access 392 
- [ ] 365 Designing functional asynchronous programs 393 
- [ ] 366 Managing fibers manually 394 
- [ ] 367 Coding functional asynchronous programs 395

## Part 3 Applied Functional Programming .  .  .  .  .  .  .  .  .  .  .397

### 11 Designing functional programs 399
- [ ] 368 Make it work, make it right, make it fast 400 
- [ ] 369 Modeling using immutable values 401 
- [ ] 370 Business domain modeling and FP 402 
- [ ] 371 Data access modeling 403
- [ ] 372 368 369
- [ ] 373 A bag of functions 404
- [ ] 374 Business logic as a pure function 405 
- [ ] 375 Separating the real data access concern 406 
- [ ] 376 Integrating with APIs using imperative libraries and IO 407 
- [ ] 377 Following the design 410 
- [ ] 378 Implementing input actions as IO values 411 
- [ ] 379 Separating the library IO from other concerns 413 
- [ ] 380 Currying and inversion of control 414 
- [ ] 381 Functions as values 415 
- [ ] 382 Connecting the dots 416 
- [ ] 383 We made it work 417 
- [ ] 384 Making it right 418 
- [ ] 385 Resource leaks 419 
- [ ] 386 Handling resources 420 
- [ ] 387 Using a Resource value 421 
- [ ] 388 We made it right 422 
- [ ] 389 Coffee break: Make it fast 423 
- [ ] 390 Coffee break explained: Make it fast 424

### 12 Testing Functional Programs 427
- [ ] 391 Do you have tests for that? 428 
- [ ] 392 Tests are just functions 429 
- [ ] 393 Choosing functions to test 430 
- [ ] 394 Testing by providing examples 431 
- [ ] 395 Practicing testing by example 432 
- [ ] 396 Generating good examples 433 
- [ ] 397 Generating properties 434 
- [ ] 398 Property-based testing 435 
- [ ] 399 Testing by providing properties 436 
- [ ] 400 Delegating the work by passing functions 437 
- [ ] 401 Understanding failures of property-based tests 438 
- [ ] 402 Wrong test or a bug? 439 
- [ ] 403 Custom generators 440
contents xvii
xviii contents
### Appendix A 481
### Appendix B 477
### index
- [ ] 404 Scala cheat sheet 471 
- [ ] 405 Functional gems 
- [ ] 406 Using custom generators
- [ ] 407 Testing more complicated scenarios in a readable way 442 
- [ ] 408 Finding and fixing bugs in the implementation 443 
- [ ] 409 Coffee break: Property-based tests 444 
- [ ] 410 Coffee break explained: Property-based tests 445 
- [ ] 411 Properties and examples 446 
- [ ] 412 Requirements coverage 447 
- [ ] 413 Testing side-effectful requirements 448 
- [ ] 414 Identifying the right test for the job 449 
- [ ] 415 Data usage tests 450 
- [ ] 416 Practicing stubbing external services using IO 452 
- [ ] 417 Testing and design 453 
- [ ] 418 Service integration tests 454 
- [ ] 419 Local servers as Resources in integration tests 455 
- [ ] 420 Writing isolated integration tests 456 
- [ ] 421 Integration with a service is a single responsibility 457 
- [ ] 422 Coffee break: Writing integration tests 458 
- [ ] 423 Coffee break explained: Writing integration tests 459 
- [ ] 424 Integration tests take more time 460 
- [ ] 425 Property-based integration tests 461 
- [ ] 426 Choosing the right testing approach 462 
- [ ] 427 Test-driven development 463 
- [ ] 428 Writing a test for a feature that doesn’t exist 464 
- [ ] 429 Red-green-refactor 465 
- [ ] 430 Making tests green 466 
- [ ] 431 Adding more red tests 467 
- [ ] 432 The last TDD iteration 468
- [ ] 433 441
