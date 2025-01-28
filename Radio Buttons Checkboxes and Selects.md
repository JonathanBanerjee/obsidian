Check boxes:
<h2>More Inputs</h2>

<form action="/birds">

<input type="checkbox" name="agree_tos" id="agree" checked />

<label for="agree">I agree to everything</label>

<button>Submit</button>

</form>


Radios:
The value attribute if very important for radios, so that a value of the data can be sent to the server.

<form action="/birds">
<p>

<label for="s">Small</label>

<input type="radio" name="size" id="s" value="s" />

<label for="m">Medium</label>

<input type="radio" name="size" id="m" value="m" />

<label for="l">Large</label>

<input type="radio" name="size" id="l" value="l" />

</p>

<button>Submit</button>

</form>

Select:
<p>

<label for="meal">Please select an Entree</label>

<select name="meal" id="meal">

<option value="fish">Fish</option>

<option value="veg" selected>Vegetarian</option>

<option value="steak">Steak</option>

</select>

</p>