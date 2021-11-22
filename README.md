# gun-map

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Development

Run on development mode with:

```bash
# Install dependencies
yarn

# Start the development server
yarn start
```

This will start the client development server on `http://localhost:3000`

## Docker

### Using the image from Dockerhub

```bash
# Run image on background (remove -d to not run on background)
docker run -p 3000:80 -d jmacazana/gun-map
```

### Building from scratch

```bash
# Build image
docker build . -t gun-map

# Run image on background (remove -d to not run on background)
docker run -p 3000:80 -d gun-map
```
