# ADS-B and AIS Multifeeder Aggregator

This project runs on a Raspberry Pi and aggregates radio signals from both ADS-B (Automatic Dependent Surveillance–Broadcast) and AIS (Automatic Identification System) sources. 
It collects and forwards aircraft and vessel positional data to online aggregators for personal tracking, research, or contribution to public datasets.

## Features

- **ADS-B Signal Reception:** Collects aircraft data using a compatible radio receiver and processes it in real-time.
- **AIS Signal Reception:** Receives vessel tracking information from AIS broadcasts.
- **Data Aggregation:** Combines ADS-B and AIS feeds for streamlined processing.
- **Forwarding to Aggregators:** Pushes data to multiple public aggregators (e.g., ADS-B Exchange, FlightAware, MarineTraffic, or others you configure).
- **Lightweight Setup:** Designed to run efficiently on Raspberry Pi devices.

## Setup & Installation

For detailed instructions on setting up your system, including hardware requirements, software installation, and configuration, 
please refer to the [SDR-Enthusiasts ADS-B Guide](https://sdr-enthusiasts.gitbook.io/ads-b/). This comprehensive guide covers:

- **Receiving ADS-B Data:** Using `adsb-ultrafeeder` with an RTL-SDR dongle.
- **Feeding Data to Online Services:** Configuring feeders for services like ADS-B Exchange, FlightAware, and more.
- **Storing and Visualizing Data:** Utilizing tools like InfluxDB, Prometheus, Grafana, and tar1090.
- **System Preparation:** Installing Docker and setting up your Raspberry Pi environment.

## Acknowledgements

This project leverages and builds upon work from the SDR Enthusiasts community.

Check out their amazing work here: [SDR-Enthusiasts](https://github.com/sdr-enthusiasts)
Connect with them on discord [here](https://discord.gg/sTf9uYF)
I am grateful to the contributors for their open-source work that makes projects like this possible.

## License

This project is released under the MIT License. See the [LICENSE](LICENSE) file for details.

## Enjoy!
