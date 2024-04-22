# Hotel Hub Legacy

Questa è la vecchia versione della repository [Hotel Hub](https://github.com/gherardi/hotel-hub), questa versione era progettata per essere SSR (Server Side Rendering).

Questo progetto crea un web server express e serve dei file pug renderizzati in html, il web server inoltre espone delle api rest a cui il client fa richiesta per renderizzare correttamente la pagina.
## Features

- Salvataggio dati su database MySQL
- Login e registrazione tramite sessione
- Recupero password tramite email con [sendgrid](https://sendgrid.com/en-us)
## Tech Stack

**Client:** HTML, TailwindCSS, Javascript

**Server:** Node.js, Express, Pug, MySQL

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`SENDGRID_API_KEY`

## Run Locally

Clone the project

```bash
  git clone https://github.com/gherardi/hotel-hub-legacy
```

Go to the project directory

```bash
  cd hotel-hub-legacy
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```

## Deployment

To deploy this project run

```bash
  npm run build
```

