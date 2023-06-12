# Recursive-function exercice

In this exercise we will solve a recursive function and show it in a HTML file

Given this snippet of code:

```
const categories = [
    {
        name: 'category1',
        subcategories: [
            {
                name: 'category2',
                subcategories: []
            },
            {
                name: 'category3',
                subcategories: [
                    {
                        name: 'category4',
                        subcategories: []
                    }
                ]
            }
        ]
    },
    {
        name: 'category5',
        subcategories: []
    }
];
```

The task we have to solve is to Implement this function:

```
const getCategoryPath = (categories, categoryName) => {
    let path;


    return path;
};
```

Expexted outputs should be

```
// OUTPUT SAMPLES
console.log(getCategoryPath(categories, 'category4')); // should output: '/category1/category3/category4'
console.log(getCategoryPath(categories, 'category2')); // should output: '/category1/category2'
console.log(getCategoryPath(categories, 'category5')); // should output: '/category5'
```
