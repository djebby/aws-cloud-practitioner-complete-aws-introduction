
### Route53 allow us to register and manage domains.
  - "Hosted Zone" in route53 is a group of DNS records (routing configuration for a domain name).

### Managed CDN (content delivery network): uses aws edge locations.

### to speed up delivery of content aws offer:
  - Local Zones: smaller aws regions close to big metropolitan areas.
  - Outposts: aws infrastructure that can be ordered and added to our data centers.
  - Wavelength Zones: aws services embedded into 5G networks.

### more improving speed of data transfers services:
  - Global Accelerator: imporve availability and performance for the applicaitons.
  - S3 Transfer Acceleration: [documentation](https://aws.amazon.com/s3/transfer-acceleration/)

### AWS Certificate Manager (ACM) => managed SSL Certificates
  step-1: request new ssl certificates, issued by aws, FREE to use for aws services.
  step-2: use ssl certificates with a variety of aws services.