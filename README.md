# Full Stack Java Test

A company needs to implement a software so that its employees can easily handle tasks using a Kanban board. It is a web application - full stack - based on HTML / CSS / JS (for the front-end, client-side) and Java / Spring (for the back-end, server-side). With it, company employees should be able to create tasks, list them, and change their status. The user stories that describe how it works are listed below:

- A user registers and enters the application by means of an e-mail and a password.

- Upon entering, all the tasks are shown, in a status "to do", "in progress", and "done", listed in 3 columns, respectively, and in order of creation date, from the most recent to the oldest.

- At the top there is a "+" button to create a new task. When a user clicks on it, a panel (or modal window) is displayed in which there are 3 fields that define a task: a title, a description, and a status (this is "to do" by default). The panel has a button to accept the information and create the task, and another to cancel the operation. When a task is created, it is displayed in the first position of the column corresponding to its status ("to do" by default).

- If required, the user can click on any previously created task and reopen the previous panel (or modal window) and edit its information, as well as change its status. By accepting the changes, the task is shown updated in the corresponding column (according to its status). If the operation is canceled, the panel simply closes.

Regarding its implementation, the application meets the following requirements:

- It is aligned with good UI / UX practices, and Mobile First (by default, but it must also offer a Desktop layout).

- The web interface (client side) is implemented with Vue CLI (with Vuex for handling actions / behavior), and Sass.

- All the handling of actions is done from the web interface synchronously with the back-end through a RESTful API.

- Authentication / authorization is handled with JSON Web Token (JWT).

- The information of the users and their tasks is stored in a structured database (SQL).

For the implementation the developer uses the following tools:

- Trello, for the division and organization of development tasks (visible through a public link).

- Git, for managing and controlling the code (Git Flow is used as a methodology, aligned with the Trello tasks; one task per branch).

Although it is not mandatory, it would be nice to have:

- The ability to "drag and drop" tasks between columns, and change their status automatically (like Trello does).

- Deploy the application in the cloud (the front-end at surge.sh, and the back-end at heroku.com).

The estimated time for delivery of the implementation is 10 days (if there is any delay, a dialogue could be held).