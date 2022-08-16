# Introduction to HTML, continued from class-01

## Why is it important to use semantic elements in HTML?

Firstly, the browser will be able to read semantics well and automatically apply large font size to a 'h1' for example, rather than a 'span'. We also need to use semantics as it is much better for search engine optimisation and screen readers

## Headings

In total there at 6 levels of headings in HTML, these are:

# 'h1' - This is the biggest and is used for top-level headings on a page, preferably only 1x per page.
## 'h2' - This is the second largest and is for sub-headings.
### 'h3' - This is the third biggest and is for sub-sub headings, and it just continues like this...
#### 'h4' - This is the fourth biggest
##### 'h5' - Fifth biggest
###### 'h6'- Sixth biggest (or smallest)

## Superscript and Subscript

Superscript (sup) and Subscript (sub) are two elements in HTML which are used when marking up dates, chemical formulae and mathematical equations so they show the correct meaning.

Example:
```
<p>My birthday is on the 25<sup>th</sup> of May 2001.</p>
<p>Caffeine's chemical formula is C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>.</p>
<p>If x<sup>2</sup> is 9, x must equal 3 or -3.</p>
```
Which will produce this:
![Superscript, Subscript Example](<img width="784" alt="Screenshot 2022-08-16 at 09 50 21" src="https://user-images.githubusercontent.com/103535732/184838704-61d030b4-912f-4c50-8978-5d9a110af50d.png">)
