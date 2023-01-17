================
 - [Overview](#overview)
 - [Methodology](#method)
 - [Limitations](#limit)
 - [License](#license)

## Overview
### Eviction numbers are climbing back toward pre-pandemic highs

After falling to an unprecedented low during the pandemic, eviction numbers are creeping back toward 2019 rates in Maryland, according to data from the Maryland Judiciary.

With eviction bans having long expired, [rental assistance running low](https://www.thebaltimorebanner.com/community/housing/housing-evictions-maryland-aid-R3GVJTCZJVBRTLN73T4NSASPAI/), courts back up and running at full speed, and [rents sky-high](https://www.thebaltimorebanner.com/community/housing/rent-hikes-in-baltimore-leave-tenants-struggling-JXEOS3DEZNEAJJHS4Z2YI45ZCM/), 2022 saw a rapid uptick in evictions statewide — especially in the summer.

Between August and September 2022, 13 jurisdictions, including Baltimore, recorded an eviction tally in at least one month that exceeded the number of evictions for that month in 2019, the last year before the COVID-19 pandemic was declared.

Read The Baltimore Banner's story [Eviction numbers are climbing back toward pre-pandemic highs in parts of Maryland]().

<a id="method"></a>

## Methodology
### How we analyzed Maryland Judiciary court data

The Baltimore Banner converted PDFs of aggregate Maryland Judiciary Case Activity Reports into CSVs using [Tabula](https://tabula.technology/). The raw exports of this conversion are read into the fact check file and cleaned using code. Instances where outputs includes one more or one fewer column were fixed by hand in Excel. The accuracy of the CSVs was checked by summing the totals of each county and checking them against totals in the original PDFs. The totals for May 2021 were incorrect on the PDF. The page omits Howard County in the Grand Total. Both files are stored in this repository.

Complete data was only available from July 2019 to September 2022. A PDF from the first 6 months of 2019 was made available to The Banner but it does not match the other months in every way and was omitted from the analysis.

Baltimore City eviction counts for the end of 2022 were reported in the story but not a part of this analysis.

<a id="limit"></a>
## Limitations
### Some of the 13 Maryland counties that had a increase in a month in 2022 compared to that same month in 2019 saw a very small increase

The point of this data finding is to show how widespread the statewide trend is. Of those 13 counties, 6 counties had 7 or fewer evictions in the 2022 month we count as being higher than the corresponding 2019 month. We included them because they are still indicative of the statewide trend even in cases where the month that increased changed from 0 in 2019 to 1 in 2022. Those 6 counties are:
  
  * Caroline County was higher in 2022 than 2019 in July, August and September. Across the quarter, there were 10 evictions in 2022 compared to 2 in 2019. This county actually has the highest percentage increase of any Maryland county.
  
  * Kent and Talbot counties each had only 1 eviction in the given month where they had 0 in 2019. For the third quarter of 2022, each had 1 less than they did in 2019, which means they closely match the statewide rate of evictions compared to 2019 of 30%.
  
  * Carroll, Queen Anne’s and St. Mary’s counties are also down in the third quarter compared to 2019 by about the same percentage or less than the state average, but each has a month where they were higher in 2022. Carroll had 7 compared to 4 in July. Queen Anne’s had 5 compared to 1 in August. St. Mary’s had 7 compared to 3 in 2019. Across the entire third quarter in 2022, evictions are much closer to pre-pandemic levels in Queen Anne’s (only down 10%) and St. Mary’s (down 17.9%). They are slightly lower in Carroll (42.9% lower).


<a id="license"></a>

## License

Copyright 2022, The Venetoulis Institute for Local Journalism

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
