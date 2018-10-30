# Defining Methods

Methods allow you to smoothly display code examples in different languages.

{% method %}
## My first method

My first method exposes how to print a message in JavaScript and Go.

{% sample lang="Sections" %}
Here is how to print a message to `stdout` using JavaScript.

```Sections
console.log('My first method');
```

{% sample lang="ThemeSettings" %}
Here is how to print a message to `stdout` using Go.

```ThemeSettings
fmt.Println("My first method")
```

{% common %}
Whatever language you are using, the result will be the same.

```bash
$ My first method
```
{% endmethod %}


test