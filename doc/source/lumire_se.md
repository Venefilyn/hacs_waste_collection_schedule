# Lumire

Support for schedules provided by [lumire.se](https://www.lumire.se/).

## Configuration via configuration.yaml

```yaml
waste_collection_schedule:
  sources:
    - name: lumire_se
      args:
        street_address: STREET ADDRESS
```

### Configuration Variables

**street_address**  
*(string) (required)*


### How to get the street address

1. Go to <https://www.lumire.se/#anch-sokmodul> and search your address below "När har jag tömning?".
2. Use exactly the address that is displayed in the search result.

## Example

```yaml
waste_collection_schedule:
  sources:
   - name: lumire_se
      args:
        street_address: STORGATAN 8, LULEÅ
```