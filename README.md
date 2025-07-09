# Exercise: Account Registration – React Edition

In this version of the **Account Registration** exercise, you’ll build the same form – but using **React**.

👉 If you haven’t done the original HTML/CSS/JavaScript version yet, or if you want to refresh your memory, you can find it here:
**[Original Account Registration – Vanilla JS version](https://github.com/Lexicon-LTU-2025/exercise-ts-account-registration)**

## Goal

You are going to **rebuild the account registration form** using **React**. The design and functionality remain the same, but now you’re expected to **apply modern React practices**:

- Use **components** to split the form into logical parts (e.g. `InputField`, `Form`, `SubmitButton`).
- **Lift state up** where necessary, and control the form inputs via state.
- Use **event handlers** (e.g. `onChange`, `onSubmit`) appropriately.
- **Use React refs** where helpful (e.g. for focusing or label connections).
- Focus on clean logic, minimal duplication, and reusable parts.

## Instructions

All **requirements from the original exercise still apply**. That means:

- The form must contain five inputs: `name`, `username`, `email`, `password`, and `confirm password`.
- The inputs should be within a `<form>`, and each must have a **connected label**, **without** using the `for` attribute.
- All fields are **required**.
- Passwords must:

  - Be at least 8 characters long.
  - Match each other.
  - Be validated **live**, with appropriate visual feedback.

- The **submit button must be disabled** until passwords are valid.
- On submit, log the values in this structure:

```js
const registrationData = {
  name: 'first name last name',
  username: 'username',
  email: 'email@email.com',
  password: 'password',
};
```

- Style the form cleanly – no need to copy the example image, just make it readable and user-friendly.

## Reminder

This exercise is not just about replicating the form – it's about **thinking like a React developer**:

- Use **controlled components** for your inputs.
- Structure your code for **reusability and clarity**.
- Keep logic **separated from presentation** where possible.

Good luck!
