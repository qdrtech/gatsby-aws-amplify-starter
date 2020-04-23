<a href="http://qdrtech.com">
    <h1 class="text-center">#qdr_tech</h1>
</a>
<h1 align="center">
  Gatsby AWS Amplify Starter Project
</h1>

This project ships with Gatsby + AWS Amplify configuration files you will need to get up and running at light speed. 

## 🚀 Start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the default starter.

    ```shell
    # create a new Gatsby site using the default starter
    gatsby new new-gatsby-site https://github.com/qdradford/gatsby-starter-aws-amplify
    ```

1.  **Install node_modules.**

    Navigate into your new site’s directory and install node_modules.

    ```shell
    cd new-gatsby-site/
    yarn
    # or
    npm install
    ```

1.  **Install and Configure AWS Amplify CLI**

    Insatll AWS Amplify CLI and Configure.

    ```shell
    npm install -g @aws-amplify/cli
    amplify configure
    ```

1.  **Iniitalize AWS Amplify project**

    Initialize Project with AWS Amplify.

    ```shell
    amplify init
    ```    

1.  **Push Amplify Project**

    Create reources in AWS for Amplify project

    ```shell
    amplify push
    ``` 

1.  **Start Developing**

    Start gatsby development server.

    ```shell
    gatsby develop
    ```           

1.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!

    _Note: You'll also see a second link: _`http://localhost:8000/___graphql`_. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql)._

    Open the `new-gatsby-site` directory in your code editor of choice and edit `src/pages/index.js`. Save your changes and the browser will update in real time!

# Having Issues ?

## 🎓 Visit Tutorial

Looking for more guidance? Full tutorial on how to setup a project here [on the website (#qdr_tech)](http://qdrtech.com/blog/gatsby-react-aws-amplify). 
