# React Application README

## Project Structuring
![alt text](https://github.com/denniscual/react-app-readme/blob/master/project-structure.png "Logo Title Text 1")

### Directories

In structuring a project, we need to create 2 directories inside the `src` dir which lives the React Components. 
The **Common** and **Features**.

#### Common
- The presentational logic of the Components resided in here are small. 
- These Components are often used in composing **Featured** Components.
- E.g Button, Label, and Modal.

#### Features
- The presentational logic are big.
- Components resided in here are not often used in composing other **Featured** Components.
- E.g UserList and LoginPage.

### Naming Components
To be able to create a semantically name for Components, we need to name the Components based on its responsiblities
and how your team use the Components. Like `Button`, `Label`, `UserList`, and etc. 

#### Importing Components
In naming an imported Components, it's awesome to prepend the name of the **directory** to the **Component** name. For 
an instance, we have `User` directory and inside it has `List` Component. If we gonna import this Component
into different module, it's awesome habit to prepend the `User` into `List`. So the result, `UserList` imported component
name. **Note:** If you use this convention, make sure that you gonna use this in whole project to preserve consistency.  

![alt text](https://github.com/denniscual/react-app-readme/blob/master/imported-component.png "Logo Title Text 1")

