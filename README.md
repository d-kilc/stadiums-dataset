# Schema

```
{
  type: "Feature"
  properties: {
    id: string
    name: string
    team: string
    league: "NFL" | "NBA" | "MLB" | "NHL"
    neighborhood?: string
    city: string
    state: string
    country: string
    capacity: number
    openedYear: number
    surfaceType: "grass" | "turf" | "hybrid"
    roofType: "open" | "retractable" | "dome"
    image?: string
    wikipediaUrl?: string
  },
  geometry: {
    type: "Point",
    coordinates: [number, number]
  }
}

```

# Coming Soon

1. Historic stadiums
2. Other leagues