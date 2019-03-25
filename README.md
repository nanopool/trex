# trex
T-Rex NVIDIA GPU miner with web control monitoring page.
Original repo:
https://github.com/trexminer/T-Rex
# Usage
## Windows
t-rex.exe -a x16r -o stratum+tcp://rvn-eu1.nanopool.org:12222 -u YOUR_ADDRESS.YOUR_WORKER_NAME/YOUR_EMAIL -o stratum+tcp://rvn-eu2.nanopool.org:12222 -u YOUR_ADDRESS.YOUR_WORKER_NAME/YOUR_EMAIL -p x -l log.txt

## Linux
./t-rex -a x16r -o stratum+tcp://rvn-eu1.nanopool.org:12222 -u YOUR_ADDRESS.YOUR_WORKER_NAME/YOUR_EMAIL -o stratum+tcp://rvn-eu2.nanopool.org:12222 -u YOUR_ADDRESS.YOUR_WORKER_NAME/YOUR_EMAIL -p x -l log.txt

# bitcointalk link
https://bitcointalk.org/index.php?topic=4432704.0

# Dev fee
Dev fee is set to 1%. When the miner starts and stops mining dev fee it reports it to the console output.

# More info in t-rex-help.txt

