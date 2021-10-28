<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Western Music and Modernity in Early Modern Korea"
       author="Jiyoon Auo"
       banner="https://www.vectorstock.com/royalty-free-vector/traditional-asian-patterns-abstract-background-vector-37551869" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

In this project, I will examine how Western music was introduced during Korea’s colonization roughly between 1900-1945 in early modern Korea by using Timeline JS. Around the same time in the 19th century numerous imperial attempts to open national borders of Joseon, a Korea dynastic kingdom at that era, and Western missionaries’ attempts to educate Koreans had begun. As Japan had accepted Western superiority discourse; Korea, a colony of Japan, naturally followed the colonial discourse that legitimizes Western hegemony. Not only were technological/industrial products manufactured, such as cannons and railroads, which signified modernity, but also music as an auditory medium sparked a modern shift in people’s lives. These mediums included gramophones/phonographs, radios and orchestras and were introduced as new symbols of a ‘new’ modern culture. Eventually Western music contributed to setting up a binary between Western culture and traditional culture; subject and other, advanced and underdeveloped, civilized and barbaric cultures. By visualizing timelines with the help of Timeline JS, I’m hoping to see the process of how Western music introduced in early modern Korea. 
![image](https://user-images.githubusercontent.com/93286626/139331545-68523590-a912-489f-85e9-72215ff9d73e.png)


# Basic usage

## Image

_Girl with a Pearl Earring_ (Dutch: Meisje met de parel) is an oil painting by Dutch Golden Age painter Johannes Vermeer, 
dated c. 1665. Going by various names over the centuries, it became known by its present title towards the end of the 
20th century after the earring worn by the girl portrayed there.[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)

