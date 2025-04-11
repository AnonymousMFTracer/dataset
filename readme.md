### Dataset
This is an anonymous repository publicly releasing the dataset contributed by the paper *"Shedding Light on Shadows: Automatically Tracing Illicit Money Flows on EVM-Compatible Blockchains,"* submitted to CCS'2025.
The Github account and repository do not contain any author information.

Details of each cybercrime case are shown below. Click on the case name to learn more about the incidents.
Each of the addresses and edges is manually verified. "Money Involved" refers to the amount of verified money stolen from victims in USD.

|                       Cybercrime Case                        |         Time          | Money Involved  | Address | Records |
| :----------------------------------------------------------: | :-------------------: | :-------------: | :-----: | :-------: |
| [TxPhish (54M phishing on vault)](https://x.com/BlockSecTeam/status/1826200855827390652) | Aug. 2024 - Sep. 2024 | \$ $54\mathrm{M}$ |   151   |    292    |
| [LIFI (LI.FI Hack)](https://revoke.cash/exploits/lifi-2024?chainId=1) | Jul. 2024 - Sep. 2024 | \$ $11\mathrm{M}$ |   93    |    135    |
| [Atomic (Atomic Wallet Hack)](https://atomicwallet.io/blog/articles/june-3rd-event-statement) | Jun. 2023 - Jul. 2023 | \$ $10\mathrm{M}$ |   389   |   1080    |
| [HB (Harmony Bridge Hack)](https://x.com/zachxbt/status/1619489550233133056) | Jan. 2023 - Feb. 2023 | \$ $50\mathrm{M}$ |   469   |   3887    |
| [XScam (Discord & X Scam)](https://zachxbt.mirror.xyz/svL1N4xPLX5nXHr6Cw4KLsjRtaYHxm4MAqmFy6zx3cw) | Jun. 2022 - Nov. 2022 | \$ $583\mathrm{k}$ |   837   |   1307    |

There are five directories in this repository, each corresponding to one of the five real-world cybercrime cases.

The CSV file in each directory, sharing the same name, contains the ground truth data $G_\mathrm{g}$. The columns "From" and "To" represent the source and destination addresses of each weighted edge. The amounts of illicit funds transferred, valued in USD, are provided in the "Value_in_USD" column. Each transfer's timestamp and the hash of the corresponding transaction that caused the transfer are also included.

The terminal addresses $V_\mathrm{terminal}$, indicating where the illicit money ultimately flows, are listed in the file named "terminal addresses.csv".
The source addresses $A_\mathrm{vic}$ are listed in the file "source addresses.csv".

### Visualizations and Labels

We have created detailed address labels for the laundering addresses in each case. Readers may refer to the columns "From_label" and "To_label" in each CSV file.

In addition, we have visualize the illicit money flows for each case to provide an intuitive view for further investigation by interested readers. Readers can refer to the ".png" or ".svg" files in the sub-folder named "visual" of each directory to see how criminals transfer illicit funds from victim addresses to terminal addresses.


