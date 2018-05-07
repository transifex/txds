# Experience

As UX team we choose simple over complex and prefer to be explicit than implicit, even if it
feels obvious. We try to communicate and build our products in clear, simple ways instead of being clever. Following are some specs and rules about certain components and interactions.




## Dropdown menus
Dropdown menus display options for list items, and they immediately commit choices upon selection. Dropdown options can be single and multi-level with the difference that for the latter a visual cue is needed such as an right arrow. For selected options a checked mark should be added.

#### Click mechanics:
- Choosing an option immediately commits the option and closes the menu
- Clicking outside of the dialog, or pressing ESC, cancels the action and closes the dialog

#### Content
Dropdown menu content typically consists of text and/or UI control elements. It is focused on a specific task, such as choosing a setting or option.

#### Actions
Dropdowns should not include more than two actions. A third action, such as “Learn more,” navigates away from the dialog, potentially leaving the task unfinished.

Avoid using a “Learn more” action to access help documentation; in-line expansion within the dialog should be used instead. If more extensive information is needed, provide it prior to entering the dropdown.


---


## Help text
To assist user and provide context and clarity about a field’s input you can use help text. 

#### Usage
As with all form content, help text should be succinct and easy to read. 

For brief explanations (shorter than a sentence), place the text underneath the field.
If the explanation is lengthy, use in-line expansion. 

Help text should not be correlated with placeholder, label or tip patterns/compoenents and should be used differently and per use case.

You can also use placeholder text to provide an example of the type of input required. For example, in a Name field, show a name in the correct format.


#### Do / Don’t
- Help text should be placed below the text field
- Don't use Learn more & navigate away from the dialog
- Left justified 
- On a single line if possible, or with text wrapping (if multiple lines)
- Use in-line expansion within the dialog for lengthy help text

