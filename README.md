# ddc-postfilter_score

This filter calculates score of candidates and sort by it. The score is
calculated based on 
- source order
- matching score 
- locality score.

Note that this filter is intended to use as ddc-option-postFilters.
This filter also add highlights to matched characters unless you disable it by
option.
