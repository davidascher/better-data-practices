# Data Probe

## Staying Lean

### What data is collected

Example: Crash reports

### Why do we collect and keep this data? 

Example: "To better understand why our product crashes."

### Do we collect any identifiers?

Example: We collect IP address. We don't collect any other specific identifier.

### When do you anonymize or aggregate the data?

Example: When collecting data, we do a geo-IP lookup, translating the IP address into a country code, then discard the IP address. This keeps the value that we see in the data but removes the IP address which could have other information which we've determined we don't need.

### How long do you keep this data?

Example: We delete the country code and the rest of the crash log after 180 days.

## Secure

### Where do you store the data? (e.g. company company computers, cloud servers, etc.)

Example: The data is stored on our AWS instance.

### How do you secure the data? Is it encrypted?

Example: Data is encrypted as we collect it. Data is not encryted once its on a service (we should fix that).

### Who inside and outside your organization has access to the data?

Example: Staff have access to the data through a login. The data is not available outside our org.

## Engage

### Does the user understand the data collection?

Example: Yes, through our privacy notice.

### Is the user provided an opportunity to control the collection?

Example: Yes - crash reports are optional.
