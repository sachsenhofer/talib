# Technical Analysis Library (TA-Lib) Container

This is the home of the Technical Analysis Library (TA-Lib) Container. You can use this repository to start with your trading applications. TA-Lib is already installed in the container.

<br>

## Usage

### Build

```
sudo docker build -t talib:latest .
```

### Run

```
sudo docker run -p 8080:8080 talib:latest
```


### Verify

```
curl localhost:8080/health
```

<br>
<br>

Learn more: [sachsenhofer.io](https://sachsenhofer.io)
