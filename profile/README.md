#### About
This project is in collaboration with the [Precision Ag Connectivity & Accuracy Stakeholder Alliance](https://www.pagcasa.org/pagcasa) (PAgCASA).


The purpose of this project is to find an effective combination of hardware and software solutions to accurately construct a broadband map. This project uses a multitude of devices at various price points as well as different internet speed tests to create a dataset. These devices are meant to be deployed in people's residences to collect data.


#### Hardware

The following devices are used in this project.

[SamKnows Whitebox](https://samknows.one/hc/en-gb/articles/360000451757-What-is-the-Whitebox-) - The WhiteBox is a proprietery solution with its own internet speed tests.


[Dell EMC VEP1425](https://www.delltechnologies.com/asset/en-my/products/networking/technical-support/dell_emc_networking_specsheet_vep1405.pdf) - The VEP1425 is a part of a series of network infrastructure devices. 


[Lanner NCA-1513](https://www.lannerinc.com/products/telecom-datacenter-appliances/vcpe-ucpe-platforms/nca-1513) - Like the VEP1425, this product is also designed as a network infrastructure device.


[Raspberry Pi 4](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/) - The cheapest solution and common for internet speed testing solutions. 


#### Software


[Murakami](https://github.com/m-lab/murakami)

Developed by Measurement Lab (M-Lab), which is made up of teams from Code for Science & Society and Google Inc.

Designed to run on a variety of hardware and test at random times throughout the day. 

Runs the NDT-5, NDT-7 and Ookla speedtests.

We Murakami for random tests in a 24 hour period. 



[Netrics](https://github.com/internet-equity/nm-exp-active-netrics)

Developed by The University of Chicago Data Science Institute's Internet Equity Initiative.

Designed to run on single board computers like the Raspberry Pi and highly configurable with built in scheduling options.

Runs the NDT-7 and Ookla speedtests, but can be extended to run a variety of extra tests.

We use Netrics to run tests daily during set hours. See [here](https://github.com/broadband-testing-capstone/Netrics-GCP-support) for our respository that adds Google Cloud Platform support. 


#### Data Availability

TBA.


