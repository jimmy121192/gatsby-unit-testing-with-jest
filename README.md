<p align="center">
  <a href="https://www.gatsbyjs.com">
    <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
  </a>
</p>

## 🚀 GATSBY UNIT TESTING

1.  **Setup Gatsby Starter Template**

    `gatsby new my-gatsby-project https://github.com/gatsbyjs/gatsby-starter-default`

2.  **Install Jest, Babel, other libraries and create config files**

    `npm install --save-dev jest babel-jest react-test-renderer babel-preset-gatsby identity-obj-proxy`

    Copy all the jest config files and paste it in your project directory.

3.  **Running tests**

    In your `package.json`

    ```
    "scripts": {
    "test": "jest"
    }
    ```

4.  **Setup TravisCI**

    Create `.travis.yml`

    In your `.travis.yml`

    ```
    language: node_js
    node_js: 
      - "stable"
    cache:
      directories:
    - "node_modules"
    ```

    Connect your Github repository with your TravisCI account.

## 🎯 References

 <img alt="Gatsby" src="http://alonedreamer.com/jimmymedia/images/travis.png" width="300"/>