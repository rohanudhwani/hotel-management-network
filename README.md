# Hotel Management Network

## Overview

This project, created as part of the Computer Networks course at the Indian Institute of Information Technology, Nagpur, is a simulated Hotel Management Network using Cisco Packet Tracer. The network is designed to mimic the infrastructure of a hotel with three floors, each hosting different departments with their respective VLANs.

## Features

- **Multi-Floor Infrastructure:** The hotel network comprises three floors, each equipped with a router, allowing for communication between different departments on each floor.
  
- **VLAN Segmentation:** VLANs are used to segregate network traffic based on departments. Each floor has specific VLANs for different functions such as Reception, Store, Logistics, Finance, HR, Sales, IT, and Admin.

- **Wireless Access Points:** Wireless connectivity is implemented on the first and second floors. The Logistics department on the first floor has a wireless access point supporting devices like laptops, tablets, and smartphones.

- **SSH Remote Login:** The network includes an SSH remote login feature, enabling secure access to any PC or router from another PC.

## Project Structure

The project is organized into three floors, each represented by a router:

- **Floor 1:**
  - VLANs: Reception, Store, Logistics
  - Devices: Switch, Printers, Wireless Access Point (Logistics), Connected Devices (Laptop, Tablet, Smartphone)

- **Floor 2:**
  - VLANs: Finance, HR, Sales
  - Devices: Switch, Access Point (Sales)

- **Floor 3:**
  - VLANs: IT, Admin
  - Devices: Switch

## Installation

To run this project, follow these steps:

1. Download and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).
2. Download the project file from [here](https://github.com/rohanudhwani/hotel-management-network/raw/main/hotel%20management.pkt) and open it in Cisco Packet Tracer.

## Screenshots

![Overall View](/Images/image.png)
*Screenshot of Overall Network*
<br/>
<br/>
![Floor 1](/Images/floor1.png)
*Screenshot of Floor 1*
<br/><br/><br/>
![Floor 2](/Images/floor2.png)
<br/>
*Screenshot of Floor 2*
<br/><br/><br/>
![Floor 3](/Images/floor3.png)
<br/>*Screenshot of Floor 3*
<br/><br/><br/>
![Routers](/Images/routers.png)
<br/>*Screenshot of Routers*

## Contributors

- Rohan Udhwani

## Acknowledgments

- Guidance from my course mentor, Dr. Nishat Ansari Ma'am.

## License

This project is licensed under the [MIT License](LICENSE).

---
