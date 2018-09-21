# List of known Transport Canada APIs 

#### A list of all known APIs as per our 2018-09-18 meeting. 

| API Name               | Status | Protocol | Publisher              | Used by         | URL           | Authentication    | Maintained By                         |
|------------------------|--------|----------|------------------------|-----------------|---------------|-------------------|---------------------------------------|
| Twilio SMS API         | PROD   | N/A      | Twilio                 | 2FA application |               |                   | Twilio                                |
| RAIS                   | PROD   | SOAP     | Information Management | Multiple        |               | AD                | Internal Services, Solutions Center   |
| TCDirectory            | PROD   | ?        | ?                      | Multiple        |               | None              | Internal Services, Solutions Center   |
| Geoserver              | PROD   | ?        | Programs?              | ?               |               | ?                 | Programs Portofolio, Solutions Center |
| TCVirusScanner         | PROD   | SOAP     | Digital Services       | Multiple        |               | None              | Internal Services, Solutions Center   |
| Dynamics 365           | PROD   | OData    | SCMS                   | None            |               | ADFS, maybe OAuth | Digital Services                      |
| myTC Account           | DEV    | ?        | Digital Services       | None            |               | API Token         | Digital Delivery                      |
| myTC Service Requests  | DEV    | ?        | Digital Services       | None            |               | API Token         | Digital Delivery                      |
| COREDATA               | DEV    | ?        | Information Management | None            |               | API Token         | Digital Delivery                      |
| Business Number        | PROD   | JSON     | Digital Services       | TDG Apps (TBD)  |               | API Token         | Surface Portfolio, Solutions Center   |
| ALPS (Routing Symbols) | PROD   | ?        | ?                      | ?               |               | ?                 | Internal Services, Solutions Center   |
| Exchange API           | PROD   | ?        | Microsoft              | TCDirectory     |               | ?                 | Microsoft                             |
| Forms Catalog          | PROD   | SOAP     | Information Management |                 |               | ?                 | Internal Services, Solutions Center   |
| SM-GS Web Services     | PROD   | ?        | IT Service Management  | ?               |               | ?                 | Internal Services, Solutions Center   |
| Address Validator      | PROD   | ?        | Digital Services       | TCDirectory     |               | ?                 | Internal Services, Solutions Center   |
| Security Screening     | DEV    | ?        | ?                      | ?               |               | ?                 | Internal Services, Solutions Center   |
| Marine Vessel API      | PROD   | REST     | Marine Safety          | MVR             |               | None              | Marine Portfolio, Solutions Center    |
| COPS                   | PROD   | REST     | Finance                | Multiple        |               |                   | Internal Services, Solutions Center   |
| data.tc.gc.ca          | PROD   | REST-ish | Digital Services       | Public          | data.tc.gc.ca | None              | Internal Services, Solutions Center   |