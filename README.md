# IPFS Gateway Selector

## About

IPFS Gateway Selector is a serverless service that checks public IPFS gateway status and latency to user browser.

## How To Use

Typically you only need to visit one of the URLs listed in **Try It** section. Input the CID you want to download, or simply copy&paste the link contains the CID, then click "Reload Gateways", it will refresh the download links list with estimated latency of each gateway.

## Integrate With Download

You may integrate this service with your website to provide a `mirrors` feature. By adding a `cid` parameter it will display the download list of this CID on start. For example, use this link to provide a list of mirrors of this service itself, try the [link](https://ipfs.io/ipfs/QmbTf2WJ9SFKqHAScuQ7kCUUwYaje3JQBSf2Hh1MSLvoC1/?cid=QmbTf2WJ9SFKqHAScuQ7kCUUwYaje3JQBSf2Hh1MSLvoC1):
```
https://ipfs.io/ipfs/QmbTf2WJ9SFKqHAScuQ7kCUUwYaje3JQBSf2Hh1MSLvoC1/?cid=QmbTf2WJ9SFKqHAScuQ7kCUUwYaje3JQBSf2Hh1MSLvoC1
```


## Try It
This service should be available on any working gateways, for quick entries please find the links in the latest [release](https://github.com/IOsetting/ipfs-gateway-selector/releases)

## License

The code of this repository is licensed under GPL v3.
