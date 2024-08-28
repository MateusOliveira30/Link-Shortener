# Link Shortener API

### Description

This project is a link shortening API developed in Go. The API allows users to convert long URLs into short, easy-to-share URLs. Additionally, it supports automatic redirection when accessing the shortened URLs.

### Features

**1. Shorten URL:** Submit a long URL and receive a shortened URL.

**2. Redirection:** Access a shortened URL to redirect to the original URL.


### Requirements

Go 1.20+

### Installation

1. Clone the repository:

```
git clone https://github.com/MateusOliveira30/link-shortener.git
cd link-shortener
```

2. Install dependencies:

```
go mod tidy
```
3. Run the application:

```
go run main.go
```

3. Access the API at http://localhost:8080.

### Endpoints

POST /api/shorten

Shorten a long URL.

GET /{code}

Redirects to the original URL.

### Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

### License

This project is licensed under the MIT License. See the LICENSE file for more details.
