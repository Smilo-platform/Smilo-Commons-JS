# Smilo-Commons-JS

The Smilo Commons Javascript library exposes commonly used Smilo functionality for integration in other projects.

## Building

This chapter shows how to build this library from source.

All build output is directed to the `dist` directory.

### Build dependencies

To build from source the following dependencies must be installed on your system.

- NodeJS (at least version 8.11.x)
- NPM (at least version 5.6.0)

### Development build

To create a development build run the following command in the root of the project:

```
npm run build
```

You can also start the build with a watch enabled. This will recompile the project once a source file change is detected:

```
npm run build-watch
```

### Production build

To create a production build run the following command in the root of the project:

```
npm run build-prod
```

## Testing

We use Jasmine to unit test this project. To run all tests run the following command in the root of the project:

```
npm run test
```
