# go-projects — Hello World Templates

A set of ready-to-run "Hello World" backend templates for the most popular Go frameworks. Each template is a standalone starting point: **fork the one you want, run it with `gws`, and start building**.

## Available Templates

| Template | Language | Framework |
|----------|----------|-----------|
| [go-chi](./go-chi) | Go | [Chi](https://github.com/go-chi/chi) |
| [go-echo](./go-echo) | Go | [Echo](https://echo.labstack.com/) |
| [go-fiber](./go-fiber) | Go | [Fiber](https://gofiber.io/) |
| [go-generic](./go-generic) | Go | Plain Go |
| [go-gin](./go-gin) | Go | [Gin](https://gin-gonic.com/) |
| [go-grpc](./go-grpc) | Go | [gRPC](https://grpc.io/) |
| [hugo](./hugo) | Go | [Hugo](https://gohugo.io/) |

## Getting Started

### 1. Create a GetWebstack account

Sign up for a free account at [app.getwebstack.com](https://app.getwebstack.com). You'll need it to initialise and manage your projects with the `gws` CLI.

### 2. Pick a template and fork it

Browse the templates above, choose the framework you want to work with, and fork that repository into your own GitHub account.

### 3. Install the GetWebstack CLI

```bash
curl -sSL https://getwebstack.com/install.sh | bash
```

### 4. Log in to GetWebstack

```bash
gws login
```

This authenticates the CLI with your GetWebstack account.

### 5. Initialise the project

Inside the forked project directory, run:

```bash
gws init
```

This discovers the application and generates the necessary configuration files to run it locally.

### 6. Start the application

```bash
gws up
```

This builds the application and starts it in a local Kubernetes cluster. Each template returns a simple `Hello World` response to confirm everything is working.

### 7. Start developing

The templates are intentionally minimal — just enough to get a working server running. Add routes, middleware, database connections, and anything else your project needs.

## Fullstack Templates

Looking for a frontend + backend starting point? Check out the fullstack templates:

| Template | Description |
|----------|-------------|
| [react-express-multi-repo](https://github.com/GetWebstack-public/react-express-multi-repo) | React frontend with an Express backend |

## Other Template Collections

| Collection | Description |
|------------|-------------|
| [.NET](https://github.com/GetWebstack-public/.NET) | Hello World templates for .NET (ASP.NET Core, Blazor, F#) |
| [java](https://github.com/GetWebstack-public/java) | Hello World templates for Java and JVM languages |
| [js-ts-backend](https://github.com/GetWebstack-public/js-ts-backend) | Hello World templates for JavaScript and TypeScript backends |
| [js-ts-frontend](https://github.com/GetWebstack-public/js-ts-frontend) | Hello World templates for JavaScript and TypeScript frontends |
| [php](https://github.com/GetWebstack-public/php) | Hello World templates for PHP backends |
| [python-projects](https://github.com/GetWebstack-public/python-projects) | Hello World templates for Python backends |
