Document all external ports, if you can open your desktop also identify all internal connectors. Please take 6-10 labeled photos (ports + any internal components you can safely access) A one page "connector map" (diagram/table) that matches port/connector -> purpose -> common issue (ex: USB C data + power + video sometimes: common issue: wrong cable (Thunderbolt))

If you have a laptop:

Use system tools to identify motherboard / platform details

Collect screenshots: 
System Information (Model/Bios), 
Device Manager (Network adapters, Display adapters), 
Storage type (disk drives / task manager) (HDD/SATA SSD, NVMe SSD (Capacity vs storage left))

OS Name
In general (specs)
Manufacturer and Model of Device
CPU
Cores + threads
RAM Amount
RAM Speed 
On board or dedicated GPU (Model?)

We will be doing activities today! and adding to our GitHub!

# My PC Build Documentation Assignment*tbd

## My PC Snapshot  

[screenshot* PowerShell?]
**OS**  
<img width="301" height="19" alt="OS" src="https://github.com/user-attachments/assets/83c986ea-2e12-4f79-88e6-9d57b89ec159" />
```
Windows 10 Home
10.0.19045
64-Bit
```
**CPU**  
<img width="269" height="40" alt="CPU" src="https://github.com/user-attachments/assets/9e2c9191-5e48-48f1-a83b-ffc080662218" />
```
Intel Core i7 - 9700k @ 3.60GHz
8Cores 8Threads
```
**RAM**  
<img width="409" height="35" alt="RAM" src="https://github.com/user-attachments/assets/18c89271-a4d3-40ae-843d-ebc574910aca" />
```
2x DDR4 2666 8GB
```
**Storage**  
<img width="219" height="91" alt="Disk" src="https://github.com/user-attachments/assets/db5ee8ff-f86d-42c6-a7ed-774acacacf83" />

```
Crucial CT525MX300 SSD 500GB
Micron 2200S NVMe 1TB
Samsung 860 QV0 SSD 1TB
Micron M600 SSD 1TB
```

**GPU**  
<img width="193" height="42" alt="GPU" src="https://github.com/user-attachments/assets/84956708-f13c-4639-a253-281712351ddb" />
```
NVIDIA GeForce RTX 3060
```

### How To:
Use PowerShell to retrieve this information:
- OS name, version, 32/62 bit
- CPU model & Cores/threads
- RAM Modules Size + Speed
- Storage Model + Type (NVMe/SATA) + Media Type + Size
- GPU

## Example
**Find out your current TimeZone**
```powershell
Get-TimeZone
```

