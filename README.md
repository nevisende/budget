![](https://img.shields.io/badge/Microverse-blueviolet)

# Budget

> Budget is a mobile web application that allows you to manage your budget: you have a list of transactions associated with a category, so that you can see how much money you spent and on what.

# Getting Started

_To get a local copy up and running follow these simple steps._

1. Clone the repo
   ```sh
   git clone https://github.com/nevisende/budget.git
   ```
2. Goto project directory
   ```sh
   cd budget
   ```

3. Configure `database.yml` in the config folder according to your postgreSQL configuration
4. Run app
   ```sh
   rails server.
   ```
   or
   ```sh
   rails s 
   ```

# This project was built with

- Ruby on Rails

- PostgreSQL

- Bootstrap CSS Framework


# Testing

`bundle exec rspec` will run all the tests....

Also, you can run `bundle exec rspec spec/` to run specific tests.

You can also run `RAILS_ENV=test rspec spec/` to run the tests in test mode.

# Authors

👤 **Furkan Denizhan**

- GitHub: [@nevisende](https://github.com/nevisende)
- Twitter: [@nevisen_de](https://twitter.com/nevisen_de) 
- LinkedIn: [@furkan-denizhan](https://www.linkedin.com/in/furkan-denizhan)

# 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page]

# Show your support

Give a ⭐️ if you like this project!

# Acknowledgement

- Hat tip to anyone whose code was a source of inspiration.
- A big thanks to [@microverseinc](https://github.com/microverseinc).
- The design template provider [Gregoire Vella on Behance](https://www.behance.net/gregoirevella).

## Errors

If you encounter any errors, run the following commands.

- Run `rails db:drop db:create db:migrate` to drop, create and migrate a new database.

- Run `rubocop && rubocop -A` to check for and fix code errors.

# 📝 License

This project is [MIT](./MIT.md) licensed.
