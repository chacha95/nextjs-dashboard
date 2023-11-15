# Nextjs dashboard

## Local Environment

### Installation dependecies

```bash
$ npm i
```

### Development Tools

db migration

```bash
# reset schema
$ npm run seed

# create migration
$ yarn db:makeMigration "MIGRATION MESSAGE"

# apply migration
$ yarn db:migrate
```

### setup infra

```bash
$ docker-compose up -d
```

### Running the app

```bash
# development
$ npm run dev
```
