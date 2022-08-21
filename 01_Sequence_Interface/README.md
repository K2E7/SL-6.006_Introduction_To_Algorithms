Sequences maintain a collection of items in an ***extrinsic*** order, where each item stored has a ***rank*** in the sequence including a first item and a last item.  


|        |      ||
| ------------- |:-------------|:-----|
| **CONTAINER**     | `build(X)`<br>`len()`     | given an iterable `X`, build sequence from items in `X`<br>return the number of stored items <br> |
| **STATIC**      | `iter_seq()`<br>`get_at(i)`<br>`set_at(i, x)` | return the stored items one-by-one in sequence order<br>return the *i<sup>*th*</sup>* item<br> replace the *i<sup>*th*</sup>* item with *x* |
| **DYNAMIC** | `insert_at(i, x)`<br>`delete_at(i, x)`<br>`insert_first(x)`<br>`delete_first()`<br>`insert_last(x)`<br>`delete_last()`    | add *x* as the *i<sup>th*</sup> item<br> remove and return the *i<sup>*th*</sup>* item <br> add *x* as the first item <br> remove and return first item <br> add *x* as the last item <br> remove and return the last item|


