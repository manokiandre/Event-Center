+---------------------------------------
HTML & CSS Knowledge Check - README
----------------------------------------

Overview:
	This is a basic HTML page that demonstrates core concepts in HTML structure and form design.
	It includes navigation, form inputs, semantic layout, and product selection with checkboxes.

Features:
	- Semantic layout: nav, section, fieldset, table, and form elements used properly
	- Form includes:
		- Text fields (first name, last name, contact number, email)
		- Age input with validation (min=21)
		- Country dropdown
		- Radio buttons for membership type and referral source
		- Comment textarea
		- Disabled field for invite code
	- Product table with checkboxes for adding items to a cart
	- Inline styling: basic color and border radius
	- Placeholder images with alt text

Form Behavior:
	- Method: POST
	- Action: /submit
	- Checkboxes:
		- If checked: sends name=value
		- If unchecked: field is omitted from submission
	- Disabled inputs are not submitted
	- Submit button is required (jokingly marked as such in HTML comment)

Best Practices:
	- Uses 'label for' and matching 'id' for accessibility
	- Fields include 'required' and 'placeholder' for user guidance
	- Logical groupings via fieldset and list structure
	- Tables used for structured product display

Suggestions:
	- Move inline styles to an external CSS file
	- Avoid repeated 'id' values (e.g. multiple 'howFind' IDs)
	- Add 'name' attributes to all form inputs to ensure they submit data
	- Ensure all inputs are wrapped consistently (e.g., inside <li> if list used)
	- Improve form UX with client-side validation or feedback

Images:
	- Uses placeholder image links
	- One image styled with rounded corners (via border-radius)

----------------------------------------
End of README
---------------------------------------+