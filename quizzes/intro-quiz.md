# Introduction to Kotlin 

#### Q1. What is a program?

- [ ] A specific task
- [ ] A tool that helps you write Kotlin code
- [x] A series of instructions that a computer system executes to accomplish some action
- [ ] A defined set of instructions that tells your computer to print "Happy Birthday!"

#### Q2. Which keyword do you use to define a function in Kotlin?

- [x] `fun`
- [ ] `func`
- [ ] `function`
- [ ] `newFunction`
- [ ] `main`

#### Q3. Which of the following do you need to create a Kotlin program that prints a line of text?
Choose as many answers as you see fit.

- [ ] comment describing what your program does
- [x] a `main()` function
- [x] curly braces `{}` around the instructions to the system
- [x] a call to `print()` or `println()`
- [x] a piece of text surrounded by quotation marks

#### Q4. What do you expect this Kotlin code to do?

```
fun main(args: Array<String>) {
  println("Hello, world!")
  println("It's a sunny and warm day!")
}
```

- [ ] Print one line of text
- [x] Print two lines of text
- [ ] Print three lines of text
- [ ] Print two lines of text separate by a blank line

#### Q5. How would you modify this `main()` function so that it prints a 6-layer cake for someone's 4th birthday?

```
fun main() {
  val age = 24
  val layers = 5
  printCakeCandles(age)
  printCakeTop(age)
  printCakeBottom(age, layers)
}
```

- [ ] Set val age to `6`, set val layers to `4`
- [ ] Set val age to `"4"`, set val layers to `"6"`
- [x] Set val age to `4`, set val layers to `6`
- [ ] Leave the code as-is

#### Q6. Which of these options correctly calls the function, below, and passes it vaild input agruments?

```
fun createMessage(name: String, location: String, age: Int) {
  println("My name is ${name}. I am from ${location}, and I am ${age} years old.")
}
```

- [x] `createMessage("Amy", "Australia", 20)`
- [ ] `createMessage("Evan", England, 9)`
- [ ] `createMessage("Tom", "Thailand", "40")`
- [ ] `createMessage(Heather, "Haiti", 7)`
