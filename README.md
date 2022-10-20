# FizzBuzz assignment

We want to write a Java program that prints the numbers from 1 to 100 to the "standard" output stream and follows these rules.

- For multiples of 3 it prints _Fizz_ instead of the number.
- For multiples of 5 it prints _Buzz_ instead of the number.
- For numbers which are multiples of both 3 and 5 it prints _FizzBuzz_.

## Extended version

We want our Java program to print numbers from 1 to 105 and apply these additional rules.

- For multiples of 7 it prints _Bang_ instead of the number.
- For numbers which are multiples of both 3 and 7 it prints _FizzBang_.
- For numbers which are multiples of both 5 and 7 it prints _BuzzBang_.
- For numbers which are multiples of 3, 5 and 7 it prints _FizzBuzzBang_.

## Architecture

- This application was initially designed as standalone jar file, thereafter transformed to a spring boot application and ultimately became a web application i.e. war file.
- The code leverages the Java 8 lambda and streams support to solve the FizzBuzz problem.
- Continous Integration is achieved via the CloudBees-CloudFoundry Integration service wherein a git push to the repo. results in a build being triggered on CloudBees and a deployment to CloudFoundry if the build is stable.

## Notes

- This assignment is a variant of the [Fizz Buzz Test](http://wiki.c2.com/?FizzBuzzTest).
- Feel free to change the existing code.
- You just have spent 2 or more precious minutes reading this description which gives you nothing. Ha ha. Just go to the code.
