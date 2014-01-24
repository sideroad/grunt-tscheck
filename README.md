grunt-tscheck
=============

Be safe your web application thread

# Sample Configuration

```
{
  tscheck: {
    options: {
      urls: [
        "http://google.com/?q=a",
        "http://google.com/?q=b"
      ],
      ignoreSelector: [
        "div.random",
        "p.time",
        "div.advertise"
      ],
      interval: 0, //Interval of requests(msec)
      firstInterval: 1000, //Interval of getting base contents(msec)
      requests: 100, // How many send requests per URL
    },
    results: "test.log"
  }
}
```

# 
