Challenge Description :

During a covert intelligence operation, a reconnaissance team intercepted an image believed to have been taken from a strategic observation point. Unfortunately, the metadata has been stripped, and the exact location of the photographer remains unknown.

Your task is to analyze the image and determine the precise coordinates from which it was captured. Use any visible landmarks, terrain features, infrastructure, environmental clues, or other geospatial indicators to pinpoint the exact location.

If the coordinates are 1.1234, -1.1234, the flag would be: {1.1234, -1.1234}

Your submission must not include {}

---

First we label and extract everything in the image like the taverns, bars, other stores like Fit2Run and Rick's.

We then load it into google image search with the added context and keywords based on what we extracted.

We managed to get a hit on Duval St Keywest Florida USA : https://maps.app.goo.gl/1VSHBdnoUyzqu4DV6

To get the exact coordinates Unfortunately we had to bruteforce it to get exactly in four decimal points.

Flag : 24.5588, -81.8049
