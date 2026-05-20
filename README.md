

Name: Iban Rosales



1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed.
This is the correct option, because running tests automatically whenever someone pushes the code helps mantain order and funcuionality when working in teams. This allows the main branch to have the bare minimum quality and is a core aspect of CI. 


2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No. Testing to check if a function is returning correct is done through unit tests. E2E testes user experience and other complex systems that can't be done through unit tests. 

3) What is the difference between navigation and snapshot mode?

The difference is that Navigation assesses the performance of the website by first refreshing the page and loading it, while Snapshot analyzes the current page it is in.

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

1. Add a language attribute to the html tag. ```<html> element does not have a [lang] attribute```
2. Include a meta description to summarize page content ```Document does not have a meta description```
3. Optimize the network dependency tree, to improve page load speed. ```Network dependency tree```