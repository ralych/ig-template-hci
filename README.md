# HCI ig template for IG Publisher 
this is a very basic fhir implementation guide template based on from the
[fhir.base.template](https://github.com/HL7/ig-template-base) for the [IG Publisher](https://wiki.hl7.org/IG_Publisher_Documentation)

## Features
* Custom logos (see below)

## Using the ig template

Refer to the IG template in your implementation guide (ig.ini) with:
```
template = <file-path-to-this-template>
```

* Provide [packages-list.json](https://wiki.hl7.org/index.php?title=FHIR_IG_PackageList_doco) in input/pagecontent directory


## Note on HL7/FHIR Logos
this template does not use the hl7/fhir logo, however you can include them by providing logo.html and fhirlogo.hml in input/includes directory and logos in input/pagecontent/assets/images/, check rules [zulip](https://chat.fhir.org/#narrow/stream/179294-committers.2Fannounce/topic/HL7.20Trademark.20Issues).
