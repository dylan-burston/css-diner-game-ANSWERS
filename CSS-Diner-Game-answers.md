# <div align="center"> CSS-Diner-Game-ANSWERS

Answers to the CSS Diner game at [css-diner-game](https://flukeout.github.io/)

1. Type selector --> plate
2. Type selector --> bento
3. ID selector --> #fancy
4. Descendant selector --> plate apple
5. Combine descendant & ID --> #fancy pickle
6. Class selector --> .small
7. Combine nested classes --> bento .small, plate .small ````or```` orange.small
8. bento orange.small
9. Comma combinators --> plate, bento
10. Universal selector to select everything --> *
11. Combining universal selector --> plate *
12. Adjacent sibling selectors target ***one*** child element next to --> plate + apple
```
the + selects all apple elements that are adjacent to a plate
```
13. General sibling selectors target ***all*** child elements next to --> bento ~ pickle
14. Child selector --> plate > apple 
```
apple is a direct child of plate in this example 
```
15. Pseudo selectors can target based on the ***state*** of an element --> orange:first-child <br> selects the first orange in the list of oranges 
16. Can use a descendant selector --> plate apple, plate pickle ````or```` can use :only-child pseudo selector to make more efficient --> plate apple:only-child, plate pickle:only-child
17. 