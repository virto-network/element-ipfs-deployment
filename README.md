# element-ipfs-deployment

Small script that downloads the latest version of [element.io](https://element.io), 
adds the custom `config.json` and then deploys it to IPFS using a remote pinning service.

After pinning the files, its CID is used to update the `virto.community` DNS record.

> You should have a configured remote pinning service. (Check `ipfs pin remote service --help`)
