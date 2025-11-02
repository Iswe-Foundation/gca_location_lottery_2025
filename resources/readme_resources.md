# List of resources for the location lottery

## `regions_countries_list_with_pop.csv`
Used to match up countries with UN regions and constituent regions with 'parent' countries (e.g. Isle of Man (IMN) is part of the United Kingdom (GBR)).
This list was created in the spirit of being as politically neutral as possible.

## `boosted_data_boost_method_just_boost_the_first_bin_num_bins_4_bins_boosted_by1.5.csv`
This is an example of an output from `nd_gain_operations.py` which you can use in the main lottery code. Or you can make your own.

## `sids_countries_and_codes`
A simple list of Small Island Developing States and their three-letter ISO codes.
This could be used for any list of countries which you wanted to give a better chance of making it into the initial selection if `ENABLE_SIDS_GUARANTEE = True` in `GCA_2526_Civic_Assembly_location_lottery.py`.
