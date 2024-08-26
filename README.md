# Wireshark Profiles Repository

This repository contains a collection of custom profiles for **Wireshark**. They were used in my day to day tasks.These profiles were crafted to facilitate the capture and analysis of network traffic in different environments and specific scenarios.

## Contents


- **802.11**: Profile optimized for analyzing WIFI traffic.
- **AFI_AMI**: Profile created for working with Gigamon solution (AFI/AMI)
- **Bluetooth**: Profile created for bluetooth traffic.
- **CFlow**: Profile created for Netflow traffic.
- **Classic**: Just Classic with a tool bar
- **GTP**: Profile created for working with Gigamon solution (GTP Correlation)
- **RTT**: Profile created for RTT analysis
- **Sequence**: Profile created for TCP sequence analysis


## Installation

To use one of the profiles from this repository:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/repository-name.git
    ```

2. **Copy the Profile to the Wireshark Profiles Directory**:
   - In Wireshark, go to `Help` > `About Wireshark` > `Folders` and locate the `Personal configuration` directory.
   - Copy the desired profile directory to the path shown.

3. **Select the Profile in Wireshark**:
   - Open Wireshark.
   - Go to `Edit` > `Configuration Profiles` and select the desired profile from the list.

## How to Contribute

Contributions are welcome! Follow the steps below to submit a contribution:

1. **Fork the Repository**.
2. **Create a Branch** for your contribution:
    ```bash
    git checkout -b my-contribution
    ```
3. **Add Your Profile** to the appropriate folder in the repository.
4. **Submit a Pull Request** for review.

