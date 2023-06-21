1. Configure ES lint

    - Install eslint package either locally or globally as dev dependency
        ```
        npm install eslint --save-dev
        ```

    - Then create and initialize the `.eslintrc.js` file.
        ```
        eslint --init
        ```
    
    - Create `.env` file and add `ESLINT_NO_DEV_ERRORS=true` so that eslint will not throw errors in the browser or localhost server but only give warnings in terminal.
<br>
<br>

2. Create Git Repo
<br>
<br>

3. Install Dependencies
    
    - Alan-AI
        ```
        npm install @alan-ai/alan-sdk-web
        ```
    
    - Material UI
        ```
        npm install @mui/material @emotion/react @emotion/styled @mui/icons-material @mui/styles
        ```
    
    - Redux
        ```
        npm install @reduxjs/toolkit react-redux
        ```
    
    - axios
        ```
        npm install axios
        ```
    - react-router
        ```
        npm install react-router-dom
        ```
<br>
<br>

4. Add `<CssBaseline />` Component imported from `@mui/material` at the top of the `App` Component.
<br>
<br>

5. Create Components and Configure Routing
    
    - Create `NavBar` and add it to the top of the `App`.

    - Create `Actors`, `MovieInformation`, `Movies`, `Profile` and add routing to them in `App`.