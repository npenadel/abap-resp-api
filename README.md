# Simple ABAP REST API

Clone or import using [abapGit](https://github.com/larshp/abapGit)

Visit my blog about this repository --> https://medium.com/pacroy/developing-apis-in-abap-just-rest-not-odata-d91cf899f7d3

## Test Instructions

### With Postman

1. Import both JSON files into [Postman](https://www.getpostman.com/)
2. Open _GetToken_ test and go to tab _Authorization_ and set username and password accordingly.
3. Run

### With Newman

```
newman run SimpleRESTTest.postman_collection.json --environment NPL.postman_environment.json --global-var username=<username> --global-var password=<password>
newman
```

Replace `<username>` and `<password>` accordingly.
