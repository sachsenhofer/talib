# Technical Analysis Library (TA-Lib) Container

This is the home of the Technical Analysis Library (TA-Lib) Container. You can use this repository to start with your financial trading applications. TA-Lib is already installed in the container.

<br>

## Usage

### Build

Execute the following command in your terminal:

```
sudo docker build -t talib:latest .
```

### Run

Execute the following command in your terminal:

```
sudo docker run -p 8080:8080 talib:latest
```


### Verify

Execute the following command in your terminal:

```
curl localhost:8080/health
```
