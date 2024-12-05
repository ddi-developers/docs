# Introduction

This is documentation of code examples and information about DDI Implementations and is a implementation focused compliment to [https://docs.ddialliance.org](https://docs.ddialliance.org)

The goal is to provide a number of markup examples and guides for implementers.

## Hello World

=== "DDI 4.0-beta.2"
    ```xml
    <!--TODO-->
    ```
=== "DDI-L 3.3"
    ```xml
    <?xml version="1.0" encoding="UTF-8"?>
    <ddi:FragmentInstance 
        xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="ddi:instance:3_3 http://ddialliance.org/Specification/DDI-Lifecycle/3.3/XMLSchema/instance.xsd"
        xmlns:xml="http://www.w3.org/XML/1998/namespace"
        xmlns:ddi="ddi:instance:3_3" 
        xmlns:s="ddi:studyunit:3_3" 
        xmlns:r="ddi:reusable:3_3">
        <ddi:Fragment>
            <s:StudyUnit>
                <r:URN>urn:ddi:int.example:46defaec-5542-4e22-a4d9-020629452678:1</r:URN>
                <r:Agency>int.example</r:Agency>
                <r:ID>46defaec-5542-4e22-a4d9-020629452678</r:ID>
                <r:Version>1</r:Version>
                <r:Citation>
                    <r:Title xml:lang="en">Hello World</r:Title>
                </r:Citation>
            </s:StudyUnit>
        </ddi:Fragment>
    </ddi:FragmentInstance>
    ```
=== "DDI-C 2.5"
    ```xml
    <?xml version="1.0" encoding="UTF-8"?>
    <codeBook 
        xmlns="ddi:codebook:2_5" 
        xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
        xmlns:xs="http://www.w3.org/2001/XMLSchema"
        xsi:schemaLocation="ddi:codebook:2_5 http://www.ddialliance.org/Specification/DDI-Codebook/2.5/XMLSchema/codebook.xsd">
        <stdyDscr>
            <citation>
                <titlStmt>
                    <titl>Hello World</titl>
                </titlStmt>
            </citation>
        </stdyDscr>
    </codeBook>
    ```
=== "DDI-CDI 1.0"
    ```xml
    <!--TODO-->
    ```
