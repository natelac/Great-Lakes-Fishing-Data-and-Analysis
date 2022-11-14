# Great Lakes Fishing Data and Analysis

## Todo

### Now
- Do a first pass on fitting models
- Get historical weather
  - `temp`, `dew`, `humidity`, `precip`, `windgust`, `windspeed`, `winddir`, `pressure`, and `cloudcover` for `starttime`, `endtime`, and `time` for every row
  - Could probably come up with metrics for days preceding fishing days to determine if a big storm has gone through and turned the waters over
- Do better data-cleaning
  - Clean data to be 
- Refit models
- Write story
- Anonymize data
  - Load in words for filtering so that names aren't revealed
  - Load in dictionary for mapping locations to anonymized locations
### Later
- Use `pip freeze` to create a list of dependancies for the `.ipynb` files.
- Compile (here or in a notebook) a list of things that you didn't control for / were iffy on. Also recommend what steps should be taken when constructing a new dataset. 
  - The fisherman is already very good at figuring out what the best days to go fishing are. So the samples will be biased towards days where the fisherman thinks the weather is good for fishing.
