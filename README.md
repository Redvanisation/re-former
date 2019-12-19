# Re-Former

This repository is meant to have a Form made "The rails way" 

## Getting started

Clone the repository with:

```bash
git clone https://github.com/Oitur/re-former
```

Then change to the repository directory, with

```bash
 cd re-former/
```
Use the Rails specific Bash command
```bash
bundle install --without production
```
to install missing gems and packages needed -as specified inside the gemfile and yarn.lock. Afterwards, run the database migration with:

```bash
rails db:migrate
```

If you followed the steps correctly, you should be able to run the Rails server with the command:
```bash
rails server
```
The system will be served on **localhost:3000/**, but you won't be able to interact with it through your browser. 
In order to interact with the database, you'll need to use the rails console, with:
```bash
rails console
```
## Users, Posts and comments


## Dependencies

This project uses 
- Ruby v2.6.3
- Ruby on Rails v6.0.1

For its building. Other dependencies are listed in the Gemfile, located inside the root directory.  

### Authors

- Roberto Erick Nava | [Github](https://github.com/Oitur/re-former)
- Daniel Chincoya    | [@chincoya7](https://twitter.com/chincoya7)