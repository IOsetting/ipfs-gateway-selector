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
This service should be available on any working gateways, for current release please visit with CID `QmbTf2WJ9SFKqHAScuQ7kCUUwYaje3JQBSf2Hh1MSLvoC1`
* [ipfs.io](https://ipfs.io/ipfs/QmbTf2WJ9SFKqHAScuQ7kCUUwYaje3JQBSf2Hh1MSLvoC1)
* [gateway.ipfs.io](https://gateway.ipfs.io/ipfs/QmbTf2WJ9SFKqHAScuQ7kCUUwYaje3JQBSf2Hh1MSLvoC1)
* [ninetailed.ninja](https://ninetailed.ninja/ipfs/QmbTf2WJ9SFKqHAScuQ7kCUUwYaje3JQBSf2Hh1MSLvoC1)
* [ipfs.eternum.io](https://ipfs.eternum.io/ipfs/QmbTf2WJ9SFKqHAScuQ7kCUUwYaje3JQBSf2Hh1MSLvoC1)
* [ipfs.overpi.com](https://ipfs.overpi.com/ipfs/QmbTf2WJ9SFKqHAScuQ7kCUUwYaje3JQBSf2Hh1MSLvoC1)
* [ipfs.ink](https://ipfs.ink/ipfs/QmbTf2WJ9SFKqHAScuQ7kCUUwYaje3JQBSf2Hh1MSLvoC1)
* [gateway.originprotocol.com](https://gateway.originprotocol.com/ipfs/QmbTf2WJ9SFKqHAScuQ7kCUUwYaje3JQBSf2Hh1MSLvoC1)
* many more gateways ...

## License

The code of this repository is licensed under GPL v3.
