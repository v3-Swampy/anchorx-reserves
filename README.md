# anchorx-reserves
anchorx official website data

# data file
1. data.json —— the data in this file is for the Transparency tab on the official website

2. data_kz.json —— the data in this file is for the AnchorX.KZ tab on the official website

# data example
```
{
  "circulationAmount": "20.0", // AxCNH in circulation, unit is [M]
  "reservesAmount": "20.0", // AxCNH reserves, unit is [M]
  "date": "22-02-2024", // date of data
  "reports": [ // year reports
    {
      "year": 2024, // which year
      "reports": [ // month reports, display <coming soon> while this reports is empty
        {
          "month": "Feb", // which month
          "fileUrl": "xxxxxx" // report download url
        }
      ]
    },
    {
      "year": 2023,
      "reports": [
        {
          "month": "Feb",
          "fileUrl": "xxxxxx"
        }
      ]
    }
  ]
}
```
