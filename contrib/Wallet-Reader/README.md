Use this to import your wallet.dat from eBoost into Alaris to receive your airdrop tokens!

**Usage**

Edit the config.py file acccordingly then follow the steps below.

``` bash
sudo apt-get install python-virtualenv
virtualenv ~/wallet-reader-virt
source ~/wallet-reader-virt/bin/activate
pip install -r requirements.txt
python pywallet.py --exporttodaemon
```

**Manual Airdrop Redeeming**

If you can't get the automated reader to work

1. Start eBoost
2. Open Debug Window
3. Click Console Tab
4. Start Alaris
5. Open Debug Window
6. Click Console Tab
7. In eBoost Console Enter `dumpprivkey address` for each address to redeem
8. In Alaris Console Enter `importprivkey key` with each key from the output of 7
