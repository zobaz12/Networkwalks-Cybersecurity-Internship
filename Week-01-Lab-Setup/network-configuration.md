# Network Configuration - Week 01

## Network Architecture

The lab uses a NAT Network in Oracle VirtualBox
to provide internet connectivity to the Kali Linux VM.

## Network Parameters

| Parameter | Value |
|---|---|
| Network Type | NAT Network |
| Network Address | 10.0.0.0 |
| Subnet Mask | 255.255.255.0 |
| CIDR | /24 |
| Kali IP Address | 10.0.0.2 |
| Default Gateway | 10.0.0.1 |

## Kali Linux Network Verification

The following commands were used to inspect
and verify network configuration:

### Display IP Addresses

```bash
ip -br addr
```
### Display Routing Table
```bash
ip route
```
### Test Internet Connectivity
```bash
ping -c 4 10.0.0.1
```
### Test DNS Resolution
```bash
ping -c 4 google.com
```

## Result

The required network configuration was completed and internet connectivity was verified.
Screenshots are available in the screenshots directory.
