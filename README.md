# nodegit-graphql
`nodegit-grahpql` provides a quick way to spin up
a GraphQL-based web client for git, using
[`nodegit`](http://www.nodegit.org/). The GraphQL interface is a strict
subset of GitHub's graphql API. This could be used to make a local,
project-specific web front end to project's git repository.

## setup (imagined)
* `npm install -g nodegit-graphql`
* open `localhost:5000/graphiql`
* query the local git repository
* profit!

## graphql-hackathon quickstart instructions
Repo for starter kits and samples for the GraphQL Community Hackathon

Prereqs: NodeJS v4+

```
git clone https://github.com/robzhu/graphql-hackathon
cd nodegit-graphql
```

To run the GraphQL server:

```
cd server
npm install && npm start
```
Open http://localhost:5000 in your browser and you should see GraphiQL and be able to explore our example schema and data.
