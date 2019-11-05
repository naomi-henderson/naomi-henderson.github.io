---
layout: page
title: Notes on mary.ldeo.columbia.edu CMIP6
description: 
---

The monthly CMIP6 data on our local `mary` machine.

Basic page describing usage (http://mary.ldeo.columbia.edu:8080/CMIP6)

----------
**servers**
- Apache HTTP  (http://mary.ldeo.columbia.edu/CMIP6)    
- ingrid (http://mary.ldeo.columbia.edu:81/CMIP6)
- Hyrax OPeNDAP server (http://mary.ldeo.columbia.edu:8080/opendap/CMIP6)  

----------
**clients**
- Directly on mary  
 - unix scripts on mary (python, ingrid, ...)
- Not on mary
  - any opendap-enabled client (python/jupyter, matlab, ingrid, ncview, grads, ...)
  - wget, curl

----------
**catalogs**
 - Non-opendap catalog:  (useful when working on mary)
    - http://mary.ldeo.columbia.edu/catalogs/mary_cmip6.csv
    - `intake-esm` collection specification file: http://mary.ldeo.columbia.edu/catalogs/mary_cmip6.json
 - Opendap catalog: (useful when not working on mary) 
    - http://mary.ldeo.columbia.edu/catalogs/hyrax_cmip6.csv
    - `intake-esm` collection specification file: http://mary.ldeo.columbia.edu/catalogs/hyrax_cmip6.json

---------
**notes**
- if hyrax stops:
```
systemctl restart tomcat
/etc/init.d/besd start
```

