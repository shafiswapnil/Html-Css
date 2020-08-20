# Forms

An HTML form is used to collect user input. The user input is most often sent to a server for processing. - [w3schools](https://www.w3schools.com/html/html_forms.asp)


## To do's

What things you should be careful about and styles you'll be using:

- Use **unordered list (ul)** to separate inputs from each other.
	
	- Styles you'll be adding,

	```
	form ul {
		padding-left: 0;
	}

	form li {
		list-style: none;
		margin-bottom: 20px;
	}
	```

- Use label to define which input is for what.

	- Styles you'll be adding,

	```
	label {
		display: block;
		cursor: pointer;
		color: #292929;
		padding-bottom: 8px;
	}
	```

- Use `id`, `name` attribute in inputs.

- Don't ruin your markup. Like, don't specify width and height for textarea in html. Do it in the CSS.

- **MOST IMPORTANTLY**

	- Be careful when using **checkbox** and **radio** inputs.

	- When, radio and checkboxes are checked, they send information to the server. But if they are not checked, they won't send **any** type of information to the server, which is a real mess. **Use proper error handling of the radio and checkbox inputs in server side langage.**

- Have proper understaing and when to use **GET** and **POST** method as needed.
