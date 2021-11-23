# Lum Network - Public Assets

Public assets from the Lum Network ecosystem.

Feel free to use those assets for your own tools, it is used for the following official resources:
- Lum Network Explorer [https://explorer.lum.network](https://explorer.lum.network)
- Lum Network Wallet [https://wallet.lum.network](https://wallet.lum.network)

## Assets Requirements

- file extension: `.png`
- file name: should be your `valoper_address.png` 
- file directory: assets are stored per network `chain-id`

## Add validator logo
*This is the exact same process used for [Mintscan](https://www.mintscan.io/)*

1. Fork this repo to your own github account
2. Clone fork and create new branch
    ```sh
    git clone git@github.com:YOUR_ACCOUNT/public-assets.git
    cd public-assets
    git branch <branch_name>
    git checkout <branch_name>
    ```
3. Add your image (.png) file to appropriate directory
4. Commit and push to your fork

    ```sh
    git add -A
    git commit -m “Add <VALIDATOR MONIKER> logo”
    git push origin <branch_name>
    ```
5. From your repository, make pull reuqest (PR)
