# MapDataVisualization

Gossiping is one of the true natures of almost all human. With the developments of portable devices and social media, people are sharing all kinds of opinions on the Internet. Consequently, some views shared by a large group of people are believed to be facts. As a large country with different kinds of disparity of regional development, there are some wide-spread sayings about how living in a wealthy region will change your life entirely in China. However, are these sayings solid facts or just rumors? Does living in a prosperous region have significant effects on all aspects of people's lives? In this short article, I will explore some most famous sayings about the deterministic effects of regional economic development on peoples lives and try to verify these sayings with data visualization. I used the official datasets published by National Bureau of Statistics of PRC  and National Health and Family Planning Commission of PRC. As the data in 2017 and 2018 are still not fully published, all of my data are from the 2016 datasets.

First, let me show you which regions in China are wealthy or prosperous. The following two pictures are per capita GDP by region and per capita disposable income by region respectively. From both of the pictures, we can see that the traditional belief that the coastal areas in are the most wealthy areas is still a fact by now. Also, some other regions in eastern China have relatively better economic developments compared to the western part of China. After seeing where the wealthy parts are, we can start to explore the unverified sayings.
![Per Capita GDP](https://github.com/MARVELOUSbear/MapDataVisualization/blob/master/images/gdp.png)
![Per Capita Disposable Income](https://github.com/MARVELOUSbear/MapDataVisualization/blob/master/images/imcome.png)

##Famous saying  1: Living in a wealthy region gets you better health care
![health workers](https://github.com/MARVELOUSbear/MapDataVisualization/blob/master/images/health.png)
![hospitals](https://github.com/MARVELOUSbear/MapDataVisualization/blob/master/images/health.png)
People in western China often complain about not having enough health care, while people in eastern China also complain about the difficulties to get health care. In general, people in China believe that wealthy eastern regions have better health care and medical treatments, so many people in western regions in China travel across the country to get medical care every year. I collected the numbers of registered health workers (doctors, nurses and other kinds of related professional employees) by provincial regions and the numbers of 3A hospitals (the highest level of medical institutions in China) by provincial regions to take a peak on the health care condition in different parts of China. First, the number of health workers per civilian population can show us the accessibility to medical service for people in a specific region. From the map, we can see that the economic condition and the accessibility to medical service in a region do have a connection, but not a decisive connection. None of the wealthy areas has a low level of accessibility to medical service. However, fortunately, due to the extraordinary national projects set for improving the medical condition in western areas in China, the western regions' medical service accessibilities are not bad, and some of them are even better than the eastern regions on this scale. However, if we look at the distribution of top medical institution around the country, the eastern regions of China have a substantial advantage. The number of 3A hospitals per civilian population is still much higher after the great dilution effect of dense population, which means most institutions providing the latest high-tech treatments are in eastern China. In conclusion, for daily health care, western regions are actually not bad choices, but for special treatments for serious diseases, western regions still have a long way to go.

##Famous saying 2: People in wealth regions have more divorces but fewer children 
![birth rate](https://github.com/MARVELOUSbear/MapDataVisualization/blob/master/images/br.png)
![divorce rate](https://github.com/MARVELOUSbear/MapDataVisualization/blob/master/images/dr.png)
There's always a saying in China that people in wealthy eastern regions are reluctant to have children and intolerant of incompatible spouses. I investigated the birth rate and the crude divorce rate by provincial regions. According to the two maps, neither of the crude divorce rate and the birth rate has a strong connection to the regional economic condition. In fact, these two rates are more related to regional culture. In areas with male-dominant cultures like Shandong and the southern coastal regions, people have a real passion, but they are often unwilling to divorce because it's shameful in their culture. In western regions in China, many people refused the birth-control policies because of religious reasons, so birth rates are very high in these areas. In eastern coastal areas with a  competitive culture, many people are cautious before choosing to get married and have children, so both of the birth rate and divorce rate are relatively low. In summary, money doesn't have a deterministic effect on marriage or having children, so this wide-spread saying is a rumor.

##Famous saying 3: People in poor regions get much worse educational opportunities.
![higher education](https://github.com/MARVELOUSbear/MapDataVisualization/blob/master/images/het.png)
![male illiteracy rate](https://github.com/MARVELOUSbear/MapDataVisualization/blob/master/images/milrate.png)
![female illiteracy rate](https://github.com/MARVELOUSbear/MapDataVisualization/blob/master/images/filrate.png)
It is almost a consensus that families with better economic status can give children better educational opportunities, but does the financial state of a region also has this effect? I summarized the number of registered higher education institutions and found the illiteracy rate of people above 15 in different regions. The contrast of the color in the higher education institution number map is screaming about the crazy situation of Chinese high education. Regions are divided into the higher half colored by purple and the lower half colored by gold with the median number of 82, almost all the regions colored by purple locate in the eastern part of China. Beijing has 91 higher education institutions in a single city, which is almost 12 times the number in the Tibet Autonomous Region. When it comes to illiteracy rate of male and female above15, the disadvantage of western China is also pronounced. As a developing country, the illiteracy rate is meager now in most parts of China thanks to the continuous efforts made by generations of people. However, in the poorest western regions, although the governments invested billions of money in education, illiteracy and poverty are still two complementary factors decreasing the development speed of each other. A more depressing fact is that female illiteracy rate is more than twice of the male illiteracy rate in 87% of Chinese provincial regions, so it's way more difficult for female students there to get primary education. As a conclusion, the economic situation of a region has powerful effects on people's educational opportunities all the way from basic needs to higher education.

After briefly going through the three famous saying on the Chinese Internet, we can see that some of the sayings are true or at least reasonable in some way, but some of them are just unreasonable stereotypes. When we are looking at these sayings on the Internet, verifying them by data visualization may be an excellent way to help us be more rational and avoid falling into the traps of rumors.
