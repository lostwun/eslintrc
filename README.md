# ESLintrc Starter with AirBnB

Notes:

"jsx-a11y/label-has-for" rule is enforced when created a Label component where a linting error occurs when you have children props.  The error is no id or name for the htmlFor tag.  To solve this, ensure to change the "reguired" from "every" to "some"  