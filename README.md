# JprqOwn CLI

JprqOwn CLI is a command-line tool that allows you to expose your local HTTP server to the internet easily and securely.

## How to Use JprqOwn CLI

### Expose a Local Port

To expose a local HTTP server running on a specific port, use the following command:

```bash
JprqOwn.exe http <port you wanna expose>
```
Example:
```bash
JprqOwn.exe http 8080
```
This will expose your local server running on port 8080 to the internet.

Expose a Local Port with a Custom Subdomain
To expose your local HTTP server with a specific subdomain, use the following command:

bash
```bash
JprqOwn.exe http <port you wanna expose> <subdomain you want>
```
Example:
```bash
JprqOwn.exe http 8080 mysubdomain
```
This will expose your local server running on port 8080 with the subdomain mysubdomain.

