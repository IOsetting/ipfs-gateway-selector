# IPFS Gateway Selector


## About

IPFS Gateway Selector is a serverless service that checks public IPFS gateway status and latency to user browser.


## How To Use

You only need to visit one of the URLs listed in **Try It** section in your browser. Input the CID you want to download, or simply copy&paste the link contains the CID, then click "Reload Gateways", it will refresh the download links list with estimated latency of each gateway.


## Integrate With Download

You may integrate this service with your website to provide a `mirrors` feature. By adding a `cid` parameter it will display the download list of this CID on start. For example, use this link to provide a list of mirrors of this lovely cat image from [IPFS docs](https://docs.ipfs.io/concepts/content-addressing/), try the link:  

https://ipfs.io/ipns/ipnso.com/?cid=bafybeigdyrzt5sfp7udm7hu76uh7y26nf3efuylqabf3oclgtqy55fbzdi


## Try It

This service should be available on any working gateways
* [ipfs.io](https://ipfs.io/ipns/ipnso.com)
* [gateway.ipfs.io](https://gateway.ipfs.io/ipns/ipnso.com)
* [gateway.originprotocol.com](https://gateway.originprotocol.com/ipns/ipnso.com)
* [ipfs.greyh.at](https://ipfs.greyh.at/ipns/ipnso.com)
* [ipfs.drink.cafe](https://ipfs.drink.cafe/ipns/ipnso.com)
* [jorropo.net](https://jorropo.net/ipns/ipnso.com/)
* [ipfs.best-practice.se](https://ipfs.best-practice.se/ipns/ipnso.com/)
* many more gateways ...


## License

The code of this repository is licensed under GPL v3.
