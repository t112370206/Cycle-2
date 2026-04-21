# Variable Definitions

## Proportion Variable
- Variable name: `CurrentCigaretteUse`
- Meaning: whether the student currently uses cigarettes
- Original valid codes:
  - 1 = No current cigarette use
  - 2-7 = Current cigarette use categories
- Recoding rule:
  - success = 1 if original code is 2-7
  - failure = 0 if original code is 1
- Missing / invalid handling:
  - missing values and invalid codes are removed before inference

## Continuous Variable
- Variable name: `HowTallAreYouWithoutShoesInMeters`
- Meaning: self-reported height without shoes in meters
- Valid values:
  - non-missing numeric values
- Missing / invalid handling:
  - missing values are removed before inference
