# Only Transmission

## Running

### Install dependencies

Execute the following command:

```sh
    yarn 
```

### Configure the application

Create a `.env` file on project's root getting as base the file `.env.example`.

### Run the application

Execute the following command:

```sh
    yarn start
```

## Creating resources

### Creating an user

```sh
curl --request POST \
  --url http://localhost:3333/auth/register \
  --header 'Content-Type: application/json' \
  --data '{
	"login": "matheuscruz.dev@gmail.com",
	"password": "12345678"
}'
```

### Creating a transmission