# Synergy in Symphony: Data-driven Artist Pairing using Spotify Analytics

## Authors
Paula Martinez, Anish Pati, Richard Rian, Jeremiah Soliman, James Zabala

## Project Description
Imagine an artist approaching a record label company to produce her next song. The company, being data-driven, wants to use Spotify data to explore ways to make her next track successful.

### Artist: Karencitta
Karen Ann “Karencitta” Cabrera, an award-winning recording artist and songwriter from Cebu City, Philippines, has made a significant impact in the music industry with her unique blend of electronic dance and pop music. Her journey to stardom began in earnest in 2017 with the release of her Sinulog Electronic Dance Pop hit ‘Cebuana’. This track not only topped Spotify's Most Viral Music chart in 2017 but also demonstrated her widespread appeal, as evidenced by the music video garnering over 1 million views within the first 24 hours and amassing a total of 26 million views to date.

## Solution Abstract
This project initiated by collecting and storing data in a CSV file, followed by extracting relevant information for analysis. The resulting dataframe underwent meticulous data cleaning to address null values and ensure proper data types. Foreign artists such as JVKE, Philippine, Borben, and Ãlvaro De Luna were manually removed, and irrelevant features like `key` and `mode` were excluded.

Subsequently, the team delved into data exploration, formulating questions to guide their analysis:

1. What is the distribution of audio features for songs by artists more popular than Karencitta?
2. What is the correlation among each audio feature?
3. Which artists boast the highest number of followers?

Following exploratory data analysis (EDA), the project transitioned to similarity analysis. The team aimed to measure the similarity distance (L1, L2, and Cos) of Karencitta's top hit song, "Cebuana," with each track. This comparison facilitated the identification of potential artist collaborations based on track similarity. The team then compared the performance of each measure and justified the selection of the chosen metric.

Based on the results, the project recommends artists from the 'Filipino' pool as potential featured collaborators for Karencitta's next hit single. This approach leverages the analysis of audio features and similarity measures to make informed and data-driven recommendations for artist collaborations.
