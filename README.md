# cfn-dns-fastmail
CloudFormation script to setup fastmail records for a given Route53 Zone. The template creates all the standard FastMail DNS entries for the domain.

## Parameters

### ZoneId
The Route53 Zone to write CAA records to

### DomainName
The domain name for the zone
