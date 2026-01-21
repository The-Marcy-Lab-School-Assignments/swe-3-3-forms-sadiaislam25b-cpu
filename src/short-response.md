# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: Accessibility

What is accessibility and why does it matter? Name at least two ways that labels make our form inputs more accessible?

**Your Answer:**
Accessibility means designing websites so that everyone, including people with disabilities, can use and understand them. It matters because it ensures all users can interact with your content, improves usability, and is often required by law. Labels make form inputs more accessible by clearly describing what each input is for, so screen readers can read them aloud, and by increasing the clickable area when users click on the text to select the input.

## Question 2: The `name` vs `id` Attribute

`for`, `name` and `id` are attributes we put on form labels and inputs, but they serve different purposes. Explain what each attribute is used for.

**Your Answer:**
The id attribute gives a unique identifier to a specific element on the page, which allows a <label> to link to that element using the for attribute. The for attribute on a <label> tells the browser which input the label describes, making it easier to click the label to focus the input and improving accessibility. The name attribute is used to group and identify form data when it is submitted, so the server knows which values belong to which input.

## Question 3: Input Types

Why do we use specific input types like `type="email"` or `type="number"` instead of just using `type="text"` for everything? What advantages do they provide?

**Your Answer:**
We use specific input types like type="email" or type="number" because they tell the browser what kind of data is expected. This allows the browser to provide built-in features, like showing a numeric keypad on mobile for numbers or validating that an email is in the correct format. Using the correct input types improves user experience, reduces errors, and helps with accessibility.

## Question 4: Form Submission

Form data is typically sent to a server (a computer that receives the data and does something with it). Provide an example of a real web application that uses a form and, to the best of your ability, explain what the application does with that form data.

**Your Answer:**
A real example is the signup form on Gmail. When a user fills out their name, email, and password, Gmail’s server receives that form data to create a new account. The server checks the information for errors, stores the user’s account securely in a database, and then allows the user to log in and access their emai