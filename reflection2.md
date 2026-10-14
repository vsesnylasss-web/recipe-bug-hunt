Exercise 2 - Reflection Questions

1. How many times did you have to check the temperature before Git found the bug?

I checked the temperature 3 times during the bisect process.

2. If you had 100 commits instead of 7, about how many checks would bisect need?

About 7 checks, because Git bisect uses binary search.

3. How is bisect different from manually checking each commit with git checkout?

Git bisect is faster because it automatically narrows down the search instead of checking every commit.

4. When would git bisect be most useful in real projects?

It is useful when a project has many commits and developers need to find which commit introduced a bug.

5. What information do you need to start a bisect session?

I need to know one good commit and one bad commit.
