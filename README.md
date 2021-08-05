<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Peanut Team Essay"
       author="Maria Job, Elizabeth Chant, and Katherine Enright"
       banner="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/A_Peanut_Plant%2C_illustration_from_The_Encyclopedia_of_Food_by_Artemas_Ward_01.jpg/1280px-A_Peanut_Plant%2C_illustration_from_The_Encyclopedia_of_Food_by_Artemas_Ward_01.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

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
      
Peanuts
<param ve-image
       label="John Haberle (1856-1933), Fresh Roasted (Peanuts), 1887"
       attribution="Yale University Art Gallery"
       license="public domain"
       url="https://upload.wikimedia.org/wikipedia/commons/5/50/John_Haberle_-_Fresh_Roasted_%28Peanuts%29_-_1979.8_-_Yale_University_Art_Gallery.jpg">
       
Inca book
<param ve-image
       label="Inca Garcilaso de la Vega (1539-1616), 'Comentarios Reales de los Incas', 1609"
       attribution="Biblioteca Nacional de España, Biblioteca Digital Hispánica"
       license="public domain"
       url="">

## General history

book
<param ve-image
       label=" A peanut plant shown in Book XI of the 'Historia general de las cosas de Nueva España' (1577)"
       attribution="Biblioteca Nacional de España, Biblioteca Digital Hispánica"
       license="public domain"
       url="https://upload.wikimedia.org/wikipedia/commons/b/b0/Florentine_Codex_f.140v_medicinal_plants.jpg">
       
        <span data-click-image-zoomto="193,435,401,348">

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

## Multispecies Engagements: Insects, Fungi, Bacteria

Humans are not the only consumers of the peanut plant. Scientific documentation in <!-- Not sure how to Italicize text --> ‘The Peanut, the unpredictable legume; a symposium’ on non-human consumption of the peanut plant reveals insect, fungi, bacterial, and animal ‘consumers’[15]. This consumption is often represented as ‘infestation’ by ‘pests’ and crop damage due to ‘disease’. This language highlights associations of plant damage to economic ‘damage’ of crop yield. Within the discourse centered on peanut cultivation for human consumption, we find the assertive presence of insects that feed on the peanut foliage and its subterranean parts. The insects represented in the following network analysis, for example, are some of the wondrous creatures that share humanity’s appetite for the peanut plant. Some non-human consumers prefer the foliage, or sometimes the juices within the leaves, while others enjoy feasting on the subterranean parts of the plant. Some insects like the Indian Meal Moth, Almond Moth, Saw-toothed Grain Beetle, and Flour Beetles are observed to consume peanuts after they are harvested and when they are stored and transported to markets.

<param ve-d3plus-ring-network 
       url="https://raw.githubusercontent.com/KatherineMEnright/Peanut/main/Network%20Trial%20Ten%20-%20Sheet1.tsv"
       center="Arachis hypogaea">

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">
# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)

