# dymo-drivers-550
Drivers for DYMO Label writer 550 or higher

Run the following commands to install the drivers:

```
echo "deb [trusted=yes] https://zeedan345.github.io/dymo-drivers-550/debs ./" | sudo tee /etc/apt/sources.list.d/dymo-drivers-550.list
sudo apt-get update
sudo apt-get install printer-driver-dymo
```
