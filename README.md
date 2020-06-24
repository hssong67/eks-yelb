This is customized version of mreferre [Yelb app](https://github.com/mreferre/yelb)

The customization is showing the UI POD IP address and name.

Tested on K8S v1.17.4 and GKE 1.14.10

## Deployment steps

```
$ git clone https://github.com/mohanadelamin/yelb.git
$ cd yelb/
$ kubectl create namespace yelb
$ kubectl apply -f yelb.yaml
```

App UI:
![UI](https://raw.githubusercontent.com/mohanadelamin/yelb/master/yelb-ui.png)
