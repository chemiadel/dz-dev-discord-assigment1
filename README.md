## React/TypeScript/Redux Assigment

# About

This assignment is about to front-end application based on API using ReactJS.

# APPLICATION ARCHITECTURE

- Login page


![login](https://i.imgur.com/J9Vp9Qn.png)

- Main page


![Imgur](https://i.imgur.com/gWhPbVY.png)

- Add Page


![Imgur](https://i.imgur.com/SXpZ6Dx.png)

- Edit Page


![Imgur](https://i.imgur.com/tJqZsXK.png)

- Delete Modal


![Imgur](https://i.imgur.com/jXANcUV.png)

# WORK FLOW
- User Sign in using


  -- endpoint `POST` **https://dz-dev-discord-assigment1-api.herokuapp.com/login**
  
  
  "email": "johndoe66@gmail.com"
  
  "password": "somePassword"
  
 
- Getting token from Login step Fetch data from API then store in state in Redux specifially or React Context


  -- endpoint `GET` **https://dz-dev-discord-assigment1-api.herokuapp.com/data**
  
  
- After saving it in the global context we need to have ability to make changes on this data.


    -- Show data in **Table**
    
    -- Adding new user to the state (data fetched from API and stored)
    
    -- Editting a specific user from the table
    
    -- Modal to delete the row from state

# REQUIRMENTS

- Using Create React App `https://create-react-app.dev/`
- 
- Redux toolkits OR React Context `https://redux-toolkit.js.org/` || `https://reactjs.org/docs/context.html`
- 
- Routing using React-Route `https://reactrouter.com/docs/en/v6/getting-started/tutorial`
