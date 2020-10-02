<h1 align="center">
	<img
		width="300"
		alt="coding duck MX"
		src="https://raw.githubusercontent.com/CodingDuckmx/hello-world/master/codingduckMX_logo.jpeg?sanitize=true">
</h1>

<h3 align="center">
	Data Scientist // Mathematician
</h3>

<p align="center">
	<strong>
    <a href="https://twitter.com/CodingDuckmx">Twitter</a>
		•
		<a href="https://medium.com/@CodingDuckMx">Blog</a>
		•
		<a href="https://www.linkedin.com/in/jesus-caballero-medrano/">LinkedIn</a>
	</strong>
</p>



# Is there a relation between the countries' Gross Domestic Product (GDP) and the LGB rights provided to their citizens?

As I was learning how to code and reviewing some topics from Math and Statistics; I decided to ask myself if there could be a correlation between the GDP of the countries around the globe and the LGBT rights they provide to their citizens.  

## Procedure

I took rights information from the International Lesbian, Gay, Bisexual, Trans and Intersex Association (ILGA) to build an index similar to the <a href="https://doi.org/10.1016/j.worlddev.2019.03.011">“Global Index on Legal Recognition of Homosexual Orientation” (GILRHO)</a> proposed by Kees Waaldjik and compared this index with the GDP of the countries which were obtained from the World Bank.

It is important to notice: 
 
 * no trans rights where considered in this study due lack of information. 
 * the most recent and consistent information of GDP I was able to get was up to 2017.

Many factors contribute to determining a GDP to be as it is.  But I believe in more freedom more development. That was my major motivation for this project. 

In this project, I decided to use the Chi-Squared test to find if there seems to be statistical independence between the LGB rights of a specific country and its GDP. 

### Result

The result of the analysis could be read in my <a href="https://medium.com/@CodingDuckMx/is-there-a-relation-between-lgbt-rights-and-gdp-per-capita-in-the-countries-efba6e7dcc64">blog post</a>.



## In this repository:

Here is the final notebook with the findings and some cool plots to compare the situation throughout the globe. 

## Built With

  * pandas
  * numpy
  * matplotlib.pyplot
  * seaborn
  * scipy.stats
  * geopandas 

## Version

This is the very first version. Sometime I'd like to add some other variables to see what results could be achieve.

## Sources

* <a href="https://ilga.org/maps-sexual-orientation-laws"> ILGA</a>   
* <a href="https://doi.org/10.1016/j.worlddev.2019.03.011">“Global Index on Legal Recognition of Homosexual Orientation” (GILRHO)</a>
* If a Spanish reader, I deeply recomend you to read: <a href="https://www.letraese.org.mx/"> Suplemento Letra S</a> 
