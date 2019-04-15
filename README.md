# Technical assessment

This small set of exercises is intended to test some basic habilities as a software developer.

## Exercise 1
 
Create a fork of this repository in Github. You should answer the questions below directly in this text file and commit the answers in the forked repository.

## Exercise 2

Given the following piece of code, written in Javascript:
```
async function routine(value) {
  const items = await dataService.fetchAllItems();
  const filtered = items.filter(i => i.value === value);
  return filtered;
}
```

Answer the following questions:
1. What is this routine returning?
2. What type of return value can be expected (string, number, array, object)? 
3. What happens if the method *dataService.fetchAllItems()* returns null?
4. Why do we use the keyword "await" at the first line of the code?

## Exercise 3

Change the method of Exercise 2 to return an empty array if the method *dataService.fetchAllItems()* returns null.

## Exercise 4

Create a single HTML file, including the necessary CSS inside the <style> tags, representing the following webpage:
![Webpage](https://raw.githubusercontent.com/algebrik/web-basic-assessment/master/html-mockup.png)

## Exercise 5

Commit your solution at the repository you forked on Exercise 1 and make a pull request to the original repository of this test.
