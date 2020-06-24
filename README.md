This is customized version of mreferre [Yelb app](https://github.com/mreferre/yelb)

The customization is showing the UI POD IP address and name.

Tested on OCP 4.4

## Deployment steps

```
$ git clone https://github.com/mohanadelamin/yelb.git
$ cd yelb/
$ kubectl create namespace yelb
$ kubectl apply -f yelb.yaml
```

App UI:
![UI](https://raw.githubusercontent.com/mohanadelamin/yelb/master/yelb-ui.png)
