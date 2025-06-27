# f5_cloud_ips_domains

This should cheek for changes to the F5 cloud IPs and domains.
If changes are found it should alert me due to the Github action pushing a change to the txt file.

If a change is found go to https://docs.cloud.f5.com/docs-v2/platform/reference/network-cloud-ref and validate the information under **Public IPv4 Subnet Ranges for F5 Regional Edges** - Americas

Check it against the Americas.txt file here and if there are changes to it, adjust the the firewall rules accordingly.
