The data is taken from [here](http://web.mta.info/developers/data/nyct/turnstile/). Each week's data is provided as .txt files, which are really just .csv files in text format.

The goal is to clean out the irregularities and errors in data. For example, line names consist of letter combinations (each letter represents the lines which pass throught each station), but sometimes these strings are not ordered, so the same combination may appear different to a sorting algorithm. Another example is turnstiles going backward on their counters, which means a simple day-by-day difference won't work.
