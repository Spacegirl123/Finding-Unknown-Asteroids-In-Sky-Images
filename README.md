# Strengthening Planetary Defense: Detecting Unknown Asteroids using Open Data, Math, and Python

Asteroid collision risks are real and unpredictable. 66 million years ago the Chicxulub asteroid impact wiped away the dinosaurs. My project strengthens planetary defense by using robotic telescopes, open data, math, and python to find unknown asteroids.

I took images from 4 telescopes located on different latitudes to get full sky coverage. I wrote Python algorithms to query European Space Agency’s GAIA and NASA’s Horizon sky catalogs to find all known stars and asteroids. Mean, standard deviation, and histograms were used to create masks to remove known objects. The remaining objects were classified as possible asteroid candidates.

I detected 3 ‘preliminary’ asteroids. My algorithm’s plate solving ability determined its Right Ascension and Declination using the focal length of the telescope and celestial location. I reported this information by creating a Minor Planet Center report for my images. I have made my code and methodology open-source to crowdsource planetary defense.
