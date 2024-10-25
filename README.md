# **Client management with react and hooks**
Once your merge request from the last kata was reviewed, a few improvements were suggested. These are refactorings that will help make the app more scalable.

Use correct node version: **nvm use**

Install dependencies: **npm install**

Run app: **npm run dev**

**Tips:** commented code is the skeleton to complete the exercises.

**Info:** it's not a problem if customers are lost when website is reloaded because in the future an API will be used to get them.

## Exercise 1
First suggestion is about new customer alert. In the future, this alert will be reused on other components. In order to avoid duplicating the useEffect, that handle this alert, in the future, could you refactor it to be a custom hook?

## Exercise 2
Customer Management System is intended to be a large application, so in the future new react components related with customers will be added. Variables customer and setCustomer will be the parameters for these new react components. In order to avoid these variables being passed again and again from parent to children, principal engineer suggested you to create a context.

