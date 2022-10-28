# Lab Report 3 - Week 5

## ``less``
Option: ``-E``
Description: Exits the file as the cursor finishes reading (reaches the end of the line of the file).
```bash
less -E ./technical/911report/chapter-1.txt
```
![Part 1 Example 1](./screenshots/lab-5/part-1-example-1.png)
(When I move my cursor to reach the end of the file, the reader exits automatically)

Option: ``-p``
Description: Makes reader to start at a specific location of the file that starts with the first occurrence that matches such pattern.
```bash
less -p "failure" ./technical/911report/chapter-1.txt
``` 
![Part 1 Example 2](./screenshots/lab-5/part-1-example-2.png)

Option: ``-i``
Description: Makes the file name matching ignores the case (case-insensitive).
```bash
less -i ./technical/911report/CHAPTER-1.txt
```
![Part 1 Example 3](./screenshots/lab-5/part-1-example-3.png)
