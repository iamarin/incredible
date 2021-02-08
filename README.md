# incredible

This project is to create a visual application using Dash. We are using information from an
article about it. But we recommend you to visit the main page, located at https://dash.plotly.com/introduction.

## Components

So far we did not see any of the components that dash is made of. First we need to notice that
as Flask, **we need to star the application creating an app object**, we can make it as follows


```
app=dash.Dash()

```

## Dash callbacks

Callback are functions that are automatically called by Dah whenever an input component's property changes.

THe callback uses a decorator before the function of interest. By this, we are telling Dash that whenever the value of the input component changes then update the output component.

Keep in mind that you must use the same `id`you gave Dasg component in the `app.layout`when referring to it as either an input or output.
