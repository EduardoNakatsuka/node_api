# Setup

Install [Node](https://nodejs.org/en/download/)

Install [Insomnia](https://insomnia.rest/download/)

Clone Project
```bash
git clone git@github.com:EdwardAckerman/node_api.git
```

Enter Project Folder
```bash
cd node_api
```

Install dependencies
```bash
yarn install
```

Run migrations
```bash
yarn knex:migrate
```

Start server
```bash
yarn start
```

Import Insomnia's workspace

Remember to set the **{{host}}** variable in Insomnia: http://localhost:3333/

# About the project

POC using: TypeScript, Express as a Rest API, and Knex.

# Next Steps

1. Add Docker
2. Add Validations
3. Add Tests
4. Add More Features
5. TDD it
