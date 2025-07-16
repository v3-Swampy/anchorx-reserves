# anchorx-reserves
anchorx official website data

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
