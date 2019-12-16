# Landing pages
It is recommended that institutional instrument providers provide a stand alone landing page (web page) for each instrument PID to resolve to. The URL address is used to populate the LandingPage property of the PIDINST schema for PID providers [(public schema on github)](https://github.com/rdawg-pidinst/schema/blob/master/schema.rst) .

# Metadata

It is recommended that instrument providers use enough information (metadata) on landing pages to unambiguously identify the instrument. Ideally, landing pages should include the metadata specified in the schema for PID providers. Below (Table X.X and X.X) are recommendations for additional, more descriptive metadata. Together, they are designed to compliment the administration and discovery of instruments; to enable users to put data into context; and to automate instrument metadata into data workflows. 


| Metadata type | Comments |
|-----|-----|
|Model version|A variant of an instrument model. While the design of an instrument remains largely the same, variants are available with minor changes to suit different applications. For example, an instrument may be available with different housing material from the standard design, allowing the instrument to be used in more dynamic environments such as extreme pressures or weather conditions.|
|Documents| Descriptive or supporting documentation such as manuals, data sheets, scientific references etc.
|Identifications||
|Classifications|Properties that categorise instruments. In addition to instrument type, these properties can describe aspects such as the intended applications, instrument categories, operating principles, whether the instrument is a compound instrument or a component etc.|
|History (see table X.X)|A history of events, operations or changes during the lifetime of an instrument. This kind of metadata should be associated to dates and ideally accompanied by comments.|
|Calibration|Many instruments are calibrated to convert raw outputs to meaningful units or to correct for data uncertainty. It is highly recommended to store the calibration date and type. It may also be useful to store the coefficients, algorithm used and calibration certificates|
|Capabilities|Capabilities are properties that further quantify or qualify an instrument’s outputs (e.g. detection limits, accuracy, precision, operating ranges etc.).|
|Characteristics|Properties that describe features and qualities belonging to an instrument. (e.g. weight, size, housing material, components, firmware etc.).|
|Servicing|Descriptions of maintenance procedures carried out on the instrument.|
|Funding references|Identifiers or names of funding resources|
|Geolocation|Location of the instrument. The type (e.g. point, box and polygon etc.) and geodetic datum.|
|Location name|Common name for the spatial location of the instrument e.g. an observational sampling station, a laboratory etc.|
|Mounting platform|Platform that the instrument is mounted upon. The position of the instrument on the platform and its reference frame can also be reported.|
|Position|The location of an object relative to an external coordinate system. It is typically expressed by relating the object to an external reference coordinate system. |
|Orientation|The rotational relationship of an object relative to an external coordinate system. Typically expressed by relating the rotation of an object’s local coordinate axes relative to those axes of an external reference coordinate system|
|Ownership dates|Ownership start and end dates|

# Content format
links to XML/JSON metadata content

#Using common vocabularies
Common vocabularies consist of lists of standardised terms and can cover a broad spectrum of disciplines. Using standardised sets of terms solves the problem of ambiguities associated with metadata markup and also enables records to be shared and interpreted by computers.

