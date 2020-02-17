
# Creating a form with HTML5 and CSS

For creating a form, we are going to need HTML5 inputs and CSS for styling it up a bit.

## Types of input

An input type is selected with the input attribute called `type`. There are many types of inputs e.g

For text type:
```
<input type="text" name="name" required>
```
The `required` attribute has been used to handle errors incase the user submits the form while the inout field is empty.

For email type:
```
<input type="email" name="email" required>
```

For number type:
```
<input type="number" name="number" required>
```

For radio type:
```
<input type="radio" name="radio" required>
```
When using radio buttons, you can group them using the `name` attribute if you want the user to select only one radio button from a group of them e.g
```
<input type="radio" name="generations" required>First
<input type="radio" name="generations" required>Second
<input type="radio" name="generations" required>Third
```
You can set the name attribute to whatever name you wish.

For checkbox type:
```
<input type="checkbox" name="checkbox" required>
```

If you want a user to be able to select an option from a group of options, use a select tag
```
<select name="dropdown" id="dropdown" required>
    <option value="really useful">Really useful</option>
    <option value="useful">Useful</option>
    <option value="a bit useful">A bit useful</option>
    <option value="not useful at all">Not useful at all</option>
</select>
```

For creating a textarea
```
<textarea placeholder="Please send us a feedback..." name="feedback" cols="25" rows="7" required></textarea>
```
You can set the rows and columns attributes to your custom preference. They determin the height and width of the textarea.

For creating a submit input
```
<input type="submit" value="Submit">
```
You can set the value attribute to whatever you please

And finally, you can wrap all this tags within a form tag
```
<form>
	...
</form>
```