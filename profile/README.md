#### Oregon State University Capstone Project
## Broadband Testing Hardware Research

#### About
This project is a collaboration with the [Precision Ag Connectivity & Accuracy Stakeholder Alliance](https://www.pagcasa.org/pagcasa) (PAgCASA).

PAgCASA is a non-profit organization focused on mapping America's broadband infrastructure for the purposes of helping communities secure access to federal funding for broadband improvements. This is achieved through on-site internet speed testing to prove that customers are receiving service below both the federal requirements and what their internet service provider claims they're serving to that location. PAgCASA and other organizations like them need to purchase and deploy large fleets of testing devices across the country to capture this data.

The goal of this project is to investigate the wide variety of the available testing devices on the market and determine the most effective combinations of hardware and software solutions that can be used to accurately construct a broadband map. By testing multiple devices of various price points along with different testing software, this project aims to find reliable and cost-effective options available to help groups like PAgCASA make informed choices about their options for broadband testing.


#### Hardware

The following devices are used in this project.

[SamKnows Whitebox 7](https://samknows.one/hc/en-gb/articles/360000451757-What-is-the-Whitebox-) - The WhiteBox is a proprietary solution with its own internet speed tests and online data visualization.


[Dell EMC VEP1425](https://www.delltechnologies.com/asset/en-my/products/networking/technical-support/dell_emc_networking_specsheet_vep1405.pdf) - The VEP1425 is a part of a series of network infrastructure devices. 


[Lanner NCA-1513](https://www.lannerinc.com/products/telecom-datacenter-appliances/vcpe-ucpe-platforms/nca-1513) - Like the VEP1425, this product is also designed as a network infrastructure device.


[Raspberry Pi 4](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/) - The cheapest solution and common for internet speed testing solutions. 


#### Software


[Murakami](https://github.com/m-lab/murakami)

Developed by Measurement Lab (M-Lab), which is made up of teams from Code for Science & Society and Google Inc.

Designed to run on a variety of hardware and test at random times throughout the day. 

Runs the NDT-5, NDT-7 and Ookla speedtests.

We used Murakami for random tests in a 24 hour period. See [here](https://github.com/broadband-testing-capstone/murakami-config) for setup.



[Netrics](https://github.com/internet-equity/nm-exp-active-netrics)

Developed by The University of Chicago Data Science Institute's Internet Equity Initiative.

Designed to run on single board computers like the Raspberry Pi and highly configurable with built in scheduling options.

Runs the NDT-7 and Ookla speedtests, but can be extended to run a variety of extra tests.

We use Netrics to run tests daily during set hours. See [here](https://github.com/broadband-testing-capstone/Netrics-GCP-support) for our respository that adds Google Cloud Platform support. 


#### Data Availability

TBA.


#### Future Work

Expanding number of devices. Making Netrics deployable with Docker. Upgrading Netrics-GCP-Support to Netrics V2. 

