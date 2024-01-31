
# This is my version of Tech with Tim: Orbits Program. 

It will take most of my life before uploading the .py file!

A screenshot of the orbits could be available much  sooner.

The simulation consists of:

1. The sun + 4 planets and an Apollo type asteroid.
2. The asteroid is initially a space probe launched from earth orbit.
3. The mass of the Moon is added to the Earth mass. This 1% correction really makes a difference in whether Jupiter tosses the asteroid out of the solar system in one simulation.
4. The code was modified to use acceleration rather than force.
5. The components of acceleration. will be expressed as directed distance/r^3.
6. The orbit x, y LIST runs for 1 Jupiter year, then is reinitialised.
7. At reinitialise the planets "orbit trails" are redrawn afresh. which eliminates overlapping asteroid tracks (temporarily).
8. The program window was modified to fit my Andoid screen. Pygame is loaded without pip. So there are no display issues.
9. Even at this point the game is more fun to play than code.
10. Thank you Tim for the wonderful intro to pygame!
11. Near miss distances are flashed onto the screen (surface) with blit. For all planets. Nearer misses are slowed down with 1 sec delay to see if the encounter is less than .001 AU.
That is really fun. It has never happened that the asteroid comes within 20000 miles of Earth. But, as mentioned, the effect of Jupiter is amazing even a million miles away.

12. The simulation  slows down by 50% as the orbit data LIST grows to 4000 tuples. I suppose another GB of RAM on my phone would fix fhis. Not a big issue.
13.
14. later, etc

