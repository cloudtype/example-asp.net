# example - ASP.net
## Prerequisite

[Download .NET & Install](https://dotnet.microsoft.com/download)

## Run

```sh
$ dotnet run
```

http://localhost:5000

## Build

```sh
$ dotnet build
```

## Build Image & Run

```sh
$ docker build -t aspnetapp .
$ docker run -d -p 5000:80 --name aspnetapp aspnetapp
```

