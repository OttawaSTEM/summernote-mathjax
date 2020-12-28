# summernote-mathjax
A summernote plugin that uses [MathJax](https://www.mathjax.org/) to insert rendered math.  

# Working Example
[https://ottawastem.github.io/summernote-mathjax/Example/example.html](https://ottawastem.github.io/summernote-mathjax/Example/example.html)

# Usage
1. Include summernote-mathjax.js:
 
2. add `math` to your toolbar somewhere:
```
 $('#summernote').summernote({
     toolbar: [
         ...
         ['insert', ['pitcure', 'link', 'math']],
     ]
 });
```

# Insert math inline: Can't find do it in one shot, please update me if you know how to do that.
Manualy delete 'display="true"' in "\<maj-container\>"
