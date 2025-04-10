# How to setup Walrus Site

### Prerequisites

1. Install Rust [[1]](https://www.rust-lang.org/tools/install)
2. Install `sui` [[2]](https://docs.sui.io/guides/developer/getting-started/sui-install),[[3]](https://docs.sui.io/guides/developer/getting-started/connect)
3. Install `walrus` [[4]](https://docs.wal.app/usage/setup.html)
4. Install `site-builder` [[5]](https://docs.wal.app/walrus-sites/tutorial-install.html),[[6]](https://github.com/MystenLabs/walrus-sites/blob/mainnet/sites-config.yaml)

### Commands

1. Publish website (first time)
```
site-builder publish --site-name 'Website Name' --epochs max [website-dir]
```

2. Update website
```
site-builder update --epochs max [website-dir] [object-id]
```

* Publish website return `object-id`
* Require some WAL and SUI

### Sui Name Service

1. Open [Sui Name Service](https://suins.io/account/my-names#your_name)
2. Click 3 dots -> Link to Walrus Site
3. Enter `object-id` -> Apply
4. Final URL is `https://<your-suins>.wal.app` 🎉

### References

* https://docs.wal.app/walrus-sites/intro.html
