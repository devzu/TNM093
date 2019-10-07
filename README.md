# TNM093
Data for TNM093 course 2019
Kör allt via W: för att undvika CORS problem. 
Alternativt kör på egen dator.

Geojson över kommungränsen är från Kodapan.se. Har rensat upp i filen för att göra den mindre. 
Det ni ska använda för att rita upp kartan är att göra paths av mapgeo.features. Där är själv koordinaterna. 
Går även bra att göra filen till topojson för mindre laddtid, MEN kom ihåg att ni ändå får göra om till geojson för att rita upp kartan. 
Rekommenderar att använda d3.GeoAlbers och sen translera allt till koordinaterna 16,62.
Använd vilken scale ni vill. 

Geojson kommungräns data
https://devzu.github.io/TNM093/mapgeo.json

För att underlätta ännu mer har jag gjort en merge av geojson filen och den datan vi fick angående kommunerna. Dessa är ihoplänkade via regionkod.
Sök upp choropleth sen för hur ni gör med visualisering. 
(OBS! All data vi behöver använda är under properties. Så typ, properties.population) 

Geojson + data fil
https://devzu.github.io/TNM093/data.json

Använd länkarna och hämta datan från direkt, eller gå in på länken och välj "save as". Antingen som json eller geojson. Men akta er som sagt för CORS komplikationer. 
Om du använder detta, så ge mig en high five som tack iaf. 
Lycka till. Har ni frågor är det bara att maila agnli457@student.liu.se 
