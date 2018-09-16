# Section 2 Notes
1.6
elements selectors 
h1 {
    color: red; 
}

class selectors
.name {
    color:red
}

universal selectors  (notes rarely use)
* {
    color:red 
}

id selectros 
# name {
 color:red
}

attributes selectors (button )
[disables] {
    color: red;
}
<!-- ------------------------------------------------- -->
1.8
Inheritance

font-family : inherit;

combinator
 any selector plus element selectors.

the more specifiy 

<!-- ------------------------------------------------- -->
2.0
theory time - combinators
list of combinators
- adjacent sibling
    div +p {
        color:Red
    }
elements share the same parents
second element comes immediately after first element

- general sibling
    div ~ p {
        color:red;
    }
Elements share the same parent
second element comes after first element

- child
div > p {

}

second element is a direct child of first element

- descendant
    div p {

    }
    second element is a descendant of the first element.

