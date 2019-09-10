In Sass you can define partials

Partials are files with leading _ (underscore)
You can import it to other .scss file(s) and these allow you to seperate your code

eg:

```
_variable.scss

//code goes below:

$primary-color: #272727;
$text-color: #fff;
$accesnt-color: #ff652f;
$font-weights: (
    "regular": 400,
    "medium": 500,
    "bold": 700
);
```