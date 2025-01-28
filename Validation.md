<h2>Validations Demo</h2>

<form action="/dummy">

<label for="first">Enter First Name</label>

<input type="text" name="first" id="first" required />

<p><label for="username">Username</label></p>

<input

type="username"

id="username"

name="username"

minlength="3"

maxlength="20"

required

/>


<p>

<input type="email" required />

<input type="url" />

</p>

<button>Submit</button>

</form>


See the code for validations on Emails and URLs