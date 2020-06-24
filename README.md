This is customized version of mreferre [Yelb app](https://github.com/mreferre/yelb)

The customization is showing the UI POD IP address and name.

Tested on OCP 4.4

## Deployment steps

```
$ git clone https://github.com/mohanadelamin/yelb-os.git
$ cd yelb-os
$ oc new-project yelb
$ oc apply -f yelb.yaml
$ oc expose svc yelb-ui -n yelb
```

App UI:
![UI](https://raw.githubusercontent.com/mohanadelamin/yelb/master/yelb.png)
