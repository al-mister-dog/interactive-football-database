# interactive-football-database-mysql
This football database allows you to query data very simply.
Imagine you wanted to know the highest paid brazilian footballer for Arsenal.
On the table, click arsenal, which whittles the list down to Arsenal players.
Then click brazil, which whittles the list down further.
Then sort by value and voila...

You can get interactive league stats, for example where are Tottenham placed in the league in terms of goals conceded?

This database is compatible with sql and mongodb node stacks, which I have also designed to compare differences in flexibility and optimization. I am working towards making a completely stateless server and table-generator-client in order to make complex data queries simple and intuitive.

The stats page makes use of more complex data queries on the back end, using aggregation, nested query statements and multiple joins. If you are an SQL or mongoDb user, the server side code dealing with these queries might be of interest, if you want to see how ORM and ODM queries compare.
[MySql/Node server](https://github.com/al-mister-dog/football-database-mysql)
## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
