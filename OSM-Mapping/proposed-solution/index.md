# Proposed Solution

**OSM School Information Mapping Process**

For the mapping OSM data and integrating it with project connect, we are building a back-end mapping application using NodeJS and Express framework.

The application uses OverpassAPI as a data source and cleans the data as per project connect database requirements and saves it to the database.

The mapping application runs as a background and grab OSM data, clean the data, and exposes new API endpoints.

```javascript
[out:json][timeout:2500];{{geocodeArea:brazil}}->.searchArea;(node"amenity"="school";);out body;>;out;

```

![Welcome to https://projectconnect.unicef.org/map](https://trello-attachments.s3.amazonaws.com/60898319160c781861aee8e6/863x910/a74d4531b21185ff1da147387f1948f2/image.png)
