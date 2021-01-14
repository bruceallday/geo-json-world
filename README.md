# GEO-JSON-world :earth_africa:

An open GEO-JSON object with vector maps for every country.

```javascript
const getData = async () => {
  const result = await fetch(
    https://bpouncey.github.io/geo-json-world/custom.geo.json
  )
  const data = await result.json()
  return data
}
const data = getData()
console.log({data})
```
