# Pokemon API

## Object structure for alphabetical order

```json
{
    "Character":
    {
        "nDex":
        {
            "nDexID": "",
            "nDex": "",
            "name": "",
            "pageLink: ""
        }
    }
}
```

## Object structure for numerical order

```json
{
    "nDexID": 
    {
        "nDexID": "",
        "nDex": "",
        "name": "",
        "pageLink: ""
    }
}
```

## JSON Format

```json
{
    "Pokemon Image Link": "",
    "Types": {
        "Pokemon Form Name": ["Type of that form"]
    },
    "Abilities": {
        "Ability": "Pokemon Form"
    },
    "Gender Ratio": {
        "Male": "",
        "Female": "",
        "Gender Unknown": "???"
    },
    "Catch Rate": {
        "Rate": "",
        "Additional Notes": ""
    },
    "Breeding": {
        "Hatch Times": "",
        "Egg Group": "",
        "Additional Notes": ""
    },
    "Experience Yield": {
        "Exp": "Generation / Generation Range",
    },
    "Leveling": "",
    "Shape": {
        "Body Type": "",
        "Additional Notes": ""
    },
    "Color": {
        "Color": "",
        "Additional Notes": ""
    },
    "Base Friendship": "",
    "External Links": {
        "Generation Links": {
            "Generation": "Link for that generation"
        },
        "Artwork Archives": ""
    }
}
```
