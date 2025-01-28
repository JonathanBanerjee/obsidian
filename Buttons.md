Has an opening and closing tag.

If you have a button inside a form, the default behaviour is to submit that form. 

<form action="/tacos">

<p>

<label for="username">Enter a username: </label>

<input type="text" placeholder="Username" id="username" />

</p>

<p>

<label for="password">Enter a Password:</label>

<input type="password" placeholder="Password" id="password" />

</p>

<button>The Middle!</button>

<p>

<label for="color">Select a colour:</label>

<input type="color" id="color" />

</p>

<p>

<label for="number">Enter a number:</label>

<input type="number" id="number" />

</p>

  

<button>Submit</button>

<button type="button">Do not Submit</button>

<input type="submit" value="click me" />

</form>