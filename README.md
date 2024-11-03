# COMPYCLOUD PUBLIC IP ASN BLOCK

We collect a large number of IP numbers every year that violate our rules.

If you ISP provider would like to remove your IP number from the list, use Issues or email us at support at compycloud.com.

We welcome suggestions and requests for improvements.

## How do I use your list in my organization?
Use ASNCOMBINED.txt
```yaml
https://raw.githubusercontent.com/Compycloud/ASN_Block/refs/heads/main/ASNCOMBINED.txt
```
And sync this file every hour.

## pfBlockerNG
```yaml
IPv4 Source Definitions: Auto ON https://raw.githubusercontent.com/Compycloud/ASN_Block/refs/heads/main/ASNCOMBINED.txt CCANS_ASNCOMBINED
Action: Deny Both
Update Frequency: Every hour
Weekly (Day of Week): Monday
Auto-Sort Header field: Enable auto-sort
Enable Logging: Enaled
States Removal: Enabled
```
## Usage
The list is completely free to use in your own project.
