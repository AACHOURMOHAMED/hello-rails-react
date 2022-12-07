
<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#triangular_flag_on_post-deployment)
- [👥 Authors](#authors)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 [hello-rails-react] <a name="about-project"></a>

**[hello-rails-react]** is a simple rails and react app to get started with rails and react.

## 🛠 Built With <a name="built-with"></a>

  - [Ruby](https://www.ruby-lang.org/en/)
  - [Ruby on Rails](https://rubyonrails.org/)
  - [PostgreSQL](https://www.postgresql.org/)
  - [RSpec](https://rspec.info/)

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://rubyonrails.org/">Ruby on Rails</a></li>
    <li><a href="https://www.ruby-lang.org/en/">Ruby</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://render.com/">Render</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

If you dont have Ruby installed on your computer, you can download it from [here](https://www.ruby-lang.org/en/downloads/).

If you dont have Rails installed on your computer, you can download it from [here](https://rubyonrails.org/).

If you dont have PostgreSQL installed on your computer, you can download it from [here](https://www.postgresql.org/download/).

### Prerequisites

- Ruby: v3.1.2
- Rails: v7.0.1
- PostgreSQL: v14.5
- React: v17.0.2

### Setup

If you have installed git you can clone the code to your machine, or download a ZIP of all the files directly.

[Download the ZIP from this location](), or run the following [git](https://git-scm.com/downloads) command to clone the files to your machine:

- [ ] Once the files are on your machine, open the _blog-app_ folder in your code editor.
Run the following command in your terminal to install the required gems and run the application:

- [ ] Open the config/database.yml file in the project directory and change the username and password to your PostgreSQL username and password.
Edit the default section of the file to look like this:
    
```
  default: &default
  adapter: postgresql
  encoding: unicode
  # For details on connection pooling, see Rails configuration guide
  # http://guides.rubyonrails.org/configuring.html#database-pooling
  pool: <%= ENV.fetch("RAILS_MAX_THREADS") { 5 } %>
  username: <your PostgreSQL role username>
  password: <your PostgreSQL role password>

```

### Install

`NOTE:` _You may need to run this command in the project directory to install the required gems and run the application:_

```
bundle install
```

### Usage

To run the project, execute the following command:

1. Create the database with:

```sh
rails db:create
```

2. Run the migrations with:

```sh
rails db:migrate
```

3. Start the development server with:

```sh
rails server
```

4. Open the app in your browser at http://localhost:3000

### Run tests

To run tests, run the following command:

```sh
  bundle exec rspec
```

### Deployment

You can deploy this project using:

1. Deplay to Heroku

```sh
  git push heroku main
```

2. Or deploy to Render

```sh
  git push render main
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Author <a name="authors"></a>

👤 **Aachour mohamed**

- Github [@]AACHOURMOHAMED](https://github.com/Aachourmohamed)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page]().

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

> Write a message to encourage readers to support your project

If you like this project...

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thanks [Gregoire Vella on Behance](https://www.behance.net/gregoirevella) the author of the original design,


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

_NOTE: we recommend using the [MIT license](https://choosealicense.com/licenses/mit/) - you can set it up quickly by [using templates available on GitHub](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository). You can also use [any other license](https://choosealicense.com/licenses/) if you wish._

<p align="right">(<a href="#readme-top">back to top</a>)</p>
=======
# Project Name

Hello Rails From React

# Description the project.

This is a simple web app to test working with rails and react

## Built With

- Languages:
  _**Ruby**_
  _**React**_
  _**Redux**_
  _**Webpack**_
  _**Postgresql**_
- Frameworks: _**Ruby On Rails**_
- Technologies used: _**Visual Studio Code**_

### Requirements

In order to work on this project, you need to have the following dependencies installed:

- [Ruby](https://www.ruby-lang.org/en/)
- [Postgresql](https://www.postgresql.org/)
- [Node.js](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/)
- [Rails](https://rubyonrails.org/)

## Getting Started

### Clone this repository

```bash
$ git clone https://github.com/AACHOURMOHAMED/hello-rails-react
$ cd hello-rails-react
```

### Commands to run

Run

```bash
$ bundle install
```

To get all the gems required for the project

Then, run

```bash
$ npm install
```

To install packages such as style linters

To check linters locally, use

```bash
$ rubocop
$ npx stylelint "**/*.{css,scss}"
```

Once you have the project correctly set up, run

```bash
$ bin/rails db:setup
```

To run all migrations, create the database for testing and for development, and insert some data into the database for you to visualize the changes

Finally, each time you make changes to the project, run

```bash
$ bundle exec rspec /spec
```

In the root folder to check the consistency of the app. Please don't make changes to the tests unless completely necessary, and mention it in your PR description.

Important note: Since this project uses webpack for the bundling, you need to run:

```bash
$ ./bin/dev i am on windows so you've to run yarn build --watch and then start the server
```

For you to see the app being applied in the browser during development

## Author

👤 **AACHOUR MOHAMED**

- GitHub: [@AACHOURMOHAMED](https://github.com/AACHOURMOHAMED)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Microverse
- LazyCoders
- Coding Partners
- Inspiration
- etc

## 📝 License

This project is [MIT](./LICENSE) licensed.
