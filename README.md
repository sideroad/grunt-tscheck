grunt-tscheck
=============

Make sure your web application which is thread safe program

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
        "p.time"
      ]
    },
    results: "test.log"
  }
}
```
