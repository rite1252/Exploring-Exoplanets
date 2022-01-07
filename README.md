# Exploring-Exoplanets
### Finding Exoplanets Principle

Imagine that you are in your room during the daytime with the window curtains open. The room probably would be well-lit. Now, imagine that you close the curtains of the window and block the sunlight from entering the room. In this situation, the room would be darker and the visibility would be low.

So, whenever the curtains are open, the brightness of the light would be higher whereas when the curtains are closed, the brightness would be lower. We can measure the brightness of the light using a spectroscope.

The same principle is applied in searching for an exoplanet. There are billions of galaxies in the universe. These galaxies have millions of stars. One such galaxy is the Milky-way galaxy in which our solar system exists. The solar system has a star called Sun which has its light. In astronomy, a star is a heavenly body that has its light. There are 8 planets in our solar system orbiting around the Sun. Similar to this, in some other galaxy there would be a star and probably a planet would be revolving around that star.

Long back, NASA placed a telescope called the Kepler telescope in space. This telescope is used to measure the brightness of the stars in the far-distant galaxies.
 

<img src='https://student-datasets-bucket.s3.ap-south-1.amazonaws.com/whitehat-ds-datasets/kepler-exoplanets-dataset/kepler-space-telescope.jpg' width="800">

*Image credits: https://www.nasa.gov/feature/ames/kepler/nasa-s-kepler-confirms-100-exoplanets-during-its-k2-mission*

Whenever a planet, while orbiting its star, comes in between the telescope and the star, the brightness of the star recorded by the telescope is lower whereas when the planet goes behind the star, the brightness of the light recorded by the telescope is higher.

This method of detecting exoplanets in far-distant galaxies through the brightness of the light emitted by a star is called the **Transit Method**. 

Essentially, if you plot the brightness on the vertical axis and the time on the horizontal axis, then you will see that the brightness of the star recorded by the telescope increases and decreases periodically. Thus, in the graph, you will notice a wave-like pattern. This indicates that the star has at least one planet. 

<img src = 'https://s3-whjr-v2-prod-bucket.whjr.online/99a90115-148e-45c6-b9b0-4ac4a5db4e18.gif' width=500 >



The image below shows some of the exoplanets (Kepler 4b to Kepler 8b) discovered by the Kepler space telescope. You can see the brightness level radiated by the star for each planet. The Flux values on the vertical axis represent the brightness level of the star.

<img src = 'https://student-datasets-bucket.s3.ap-south-1.amazonaws.com/whitehat-ds-datasets/kepler-exoplanets-dataset/transit-method.jpg' width='800'>

*Image credits: https://www.nasa.gov/content/light-curves-of-keplers-first-5-discoveries*

As you can see in the image above, the bigger the planet (Kepler 6b), the deeper the dip in the brightness level. And, the longer the orbital period of a planet, the broader is the width of the dip (Kepler 7b). Kepler 7b has the greatest orbital period of 4.9 days among these 5 planets.

So, this is how NASA finds a planet beyond our solar system. Now, let's use the Kepler space telescope dataset to create a Pandas DataFrame to find out which stars beyond our solar system have a planet.
