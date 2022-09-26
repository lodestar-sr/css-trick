# CSS Task



### Replace the logo.

There are 2 ways to move logo to the left side of form fields.

One way is to use **grid**, but this isn't suitable for forms with dynamic number of fields.

So I used current method which makes **img** element as **absolute**.

This method will be worked properly even if the number of form fields are changed.



### Swap field order.

I used **order** property to change the position of DOM.

And I used **label[for="?"]** selector to select the target form field and this is good for dynamic form.



### Hide the account field from the user.

I set **display** property of account field as **none**.

The account field has been hidden but its value will be submitted in the form.