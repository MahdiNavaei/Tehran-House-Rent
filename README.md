# Tehran-House-Rent

Housing in Tehran varies from palaces and penthouses in Fereshteh st to modern apartment buildings in the north of Tehran to the accumulation of huts in the southeastern zone of the city.
According to the Guardian "finding a flat in Tehran is as hard as in London and NYC'.
Due to the tremendous inflation rate in Iran, finding a suitable home has become a dream for many Persian families.
like many other big cities, people generally rent apartments by paying both a monthly rent as well as a security deposit. Some landlords prefer to get most if not all of the money upfront. For every 30,000 tomans of monthly rent in Tehran, a 1 million toman - or 10 million rials - security deposit is generally required [$300 US].

Neighborhood is key
In Tehran, there is a widely held belief that substantive differences exist between those who live in the north and south. Many see this issue as a historical one. In the following dataset both region and district, columns refer to a location. Tehran has 22 districts and each district consist of some region.

How the data has been collected?

The data has been collected from multi-sources. Using python packages for scrapping, four of the main platform for renting advertisements were used to gather the data. 230K unique ad was collected and those with null value on rent or deposit were filtered.

What are the columns?

deposit (in million tomans): refers to the money that renters pay before moving to the house and reclaiming it after the Evacuation from it. Due to high inflation in IRR(Iranian Rial currency), this money will lose its value after a year(between 50-75%).

rent (in million tomans): the money that renter should pay each month.

NOTE: there is a formula for rent and deposit in Iran which states: Each 100 in the deposit is equal to 3 in rent.

floor, area, age, number of rooms are too clear to explain.

elevator, warehouse, and parking is 1 if they are included and 0 if not.

Region and district both refer to the location of the house. the region is somehow a sub-division of a district that points to a street or neighbor.

all to deposit has been calculated with the formula (see Note)
and maybe redundant as it has been calculated based on two other features ( i.e deposit and rent)

