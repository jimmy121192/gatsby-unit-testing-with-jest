<p align="center">
  <a href="https://travis-ci.com/">
    <img alt="Gatsby" src="https://travis-ci.org/images/logos/TravisCI-Mascot-1.png" width="100" />
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

## 🚀 E2E TESTING



## 🎯 REFERENCES

[![Build Status](https://travis-ci.com/jimmy121192/gatsby-unit-testing-with-jest.svg?branch=master)](https://travis-ci.com/jimmy121192/gatsby-unit-testing-with-jest)