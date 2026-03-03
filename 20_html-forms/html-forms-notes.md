<!-- +++++++++++++++ HTML Forms +++++++++++++++ -->
=> An HTML <form> is used to collect data from the user.
Example:- sign up / login / help request / contact me form

<!-- +++++++++++++++ The HTML <form> Elements +++++++++++++++ -->
<label>: Names form elements; for=" " matches input id=" " for focus and accessibility.
<select> → Drop-down list; <option> defines choices.
<textarea> → Multi-line text input; rows for height, cols for width.
<fieldset> → Groups related form elements.
<legend> → Caption for <fieldset>.
<datalist> → Provides input suggestions; linked via list attribute. Dropdown appears when user types; list value must match <datalist>’s id.
<input type="submit"> → Sends form data to server via action and method.

<!-- +++++++++++++++ The HTML <form> Attributes +++++++++++++++ -->
1. name → Identifies input; pairs with value to send data to server.
2. action → URL or file where form data is sent.
3. method → get (URL) or post (HTTP body secure).
Note:- NEVER use GET to send sensitive data! (the submitted form data is visible in the URL!)

<!-- +++++++++++++++ HTML Input Types +++++++++++++++ -->
<input type="text"> → single-line text field
<input type="radio"> → select one option from a group use the same name to group options
<input type="checkbox"> → select multiple options
<input type="email"> → email address
<input type="password"> hidden text for passwords
<input type="tel"> → telephone number
<input type="number"> numeric input
<input type="date"> → date input
<input type="datetime-local"> → date & time (no timezone)
<input type="month"> → select month & year
<input type="week"> → select week & year
<input type="time"> → select time (no timezone)
<input type="file"> → file upload (use accept attribute to allow specific formats) Example:- <input type="file" accept=".pdf,.doc,.image/">
<input type="url"> → URL address
<input type="color"> → color picker
<input type="range"> → slider for numeric range (default 0–100)
<input type="hidden"> → hidden field for data storage
<input type="image"> → image as submit button
<input type="search"> → search box
<input type="button"> defines a button
<input type="reset"> → resets form values
<input type="submit"> → submits form data

<!-- +++++++++++++++ The HTML Input Attributes +++++++++++++++ -->
1. value → sets an initial value for the input field.
2. placeholder → shows a hint inside the input box (disappears when typing).
3. required → makes the field mandatory for form submission.