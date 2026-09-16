# WorldPop Population Data

## Data provider

WorldPop

## Dataset

Nigeria Population v3.0

## Population data files

File | Geographic level | Records Main | fields

states_pop_total_scaled.xlsx | State | 37 | statename, population |
lga_pop_total_scaled.xlsx | LGA | 774 | lganame, statename, population
national_pop_total_scaled.xlsx | National | 1 | Name, population

## Intended use

The state-level population data will be joined to the Nigeria ADM1
boundary layer to produce a state-level population distribution map.

The LGA-level data will be retained for possible future detailed analysis.
The national-level file will be used as a national population reference.

## Important notes

- The state population file contains 37 records, including the Federal
  Capital Territory.
- The LGA population file contains 774 records.
- The population field will be inspected and validated before analysis.
- The original files in `data/raw` will not be edited.
