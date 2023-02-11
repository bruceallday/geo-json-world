# GEO-JSON-world :earth_africa:

An open GEO-JSON object with vector maps for every country.

```javascript
const getData = async () => {
  const result = await fetch(
    "https://raw.githubusercontent.com/bruceallday/geo-json-world/master/custom.geo.json"
  )
  const data = await result.json()
  return data
}
const data = getData()
console.log({data})
```
