# Starmap generation files
Contains files related to generating starmap with FME

# Data descriptions and units

## category

### stars
* Class O, Class O type stars are the most luminous and massive main sequence stars in the galaxy. They burn very brightly appearing very blue. They are very short lived with lifetimes of 1 - 10 million years, ending in supernova. 
* Class B, Class B stars are very luminous blue-white stars. Their lifetimes are shorter than most main sequence stars. 
* Class A, Class A stars are hot white or bluish white main sequence stars.  
* Class F, Class F stars are white main sequence stars.  
* Class G, G stars are white-yellow main sequence stars.
* Class K, Class K stars are yellow-orange main sequence stars with a long and generally stable life.
* Class M, Class M stars are red stars that form the bulk of the main sequence stars in the galaxy. their mass is low, as is their surface temperature.

### asteroids	
* C-type, Carbonaceous asteroids are grayish in color and are the most common, including more than 75 percent of known asteroids. They probably consist of clay and stony silicate rocks, and inhabit the main belt's outer regions.
* S-type, Silicaceous asteroids are greenish to reddish in color, account for about 17 percent of known asteroids, and dominate the inner asteroid belt. They appear to be made of silicate materials and nickel-iron.
* M-type, Metallic asteroids are reddish in color, make up most of the rest of the asteroids, and dwell in the middle region of the main belt. They seem to be made up of nickle-iron.
* V-type, Asteroids typified by Vesta have a basaltic, volcanic crust.

### comets	
* P-comet, Periodic
* C-comet, Non-periodic
* X-comet, No orbit
* D-comet, Lost

### planets	
* CH, Chthonian planet, An extrasolar planet that orbits close to its parent star. Most Chthonian planets are expected to be gas giants that had their atmospheres stripped away, leaving their cores.
* CA, Carbon planet, A theoretical type of terrestrial planet that could form if protoplanetary discs are carbon-rich and oxygen-poor.
* CO, Coreless planet, A theoretical type of planet that has undergone planetary differentiation but has no metallic core. It is not the same as a hollow Earth.
* DE, Desert planet, A theoretical type of terrestrial planet with very little water.
* GD, Gas dwarf planet, A low-mass planet composed primarily of hydrogen and helium.
* GG, Gas giant planet, A massive planet composed primarily of hydrogen and helium.
* HE, Helium planet, A theoretical type of planet that may form via mass loss from a low-mass white dwarf. Helium planets are predicted to have roughly the same diameter as hydrogen–helium planets of the same mass.
* IG, Ice giant planet, A giant planet composed mainly of 'ices'—volatile substances heavier than hydrogen and helium, such as water, methane, and ammonia—as opposed to 'gas' (hydrogen and helium).
* IC, Ice planet, A type of planet with an icy surface and consist of a global cryosphere.
* IR, Iron planet, A type of planet that consists primarily of an iron-rich core with little or no mantle.
* LA, Lava planet, A theoretical type of terrestrial planet with a surface mostly or entirely covered by molten lava.
* OC, Ocean planet, A theoretical type of planet which has a substantial fraction of its mass made of water.
* PR, Protoplanet, Protoplanets are large planetary embryos that originate within protoplanetary discs and have undergone internal melting to produce differentiated interiors. They are believed to form out of kilometer-sized planetesimals that attract each other gravitationally and collide.
* PU, Puffy planet, Gas giants with a large radius and very low density are sometimes called "puffy planets" or "hot Saturns", due to their density similar to or lower than Saturn's.
* SI, Silicate planet, A terrestrial planet that is composed primarily of silicate rocks. All four inner planets in our Solar System are of silicate type.
* TE, Terrestrial planet, A terrestrial planet, telluric planet or rocky planet is a planet that is composed primarily of carbonaceous or silicate rocks or metals. 

### natural satellite
* moon, A natural satellite or moon is, in the most common usage, an astronomical body that orbits a planet or minor planet (or sometimes another small Solar System body). 

## mass
* kg

## radius
* km

## surface gravity
* 1=Earth (log g)
* 0 means < 0.00001

## celestial_body
* star
* asteroid
* comet
* planet
* natural satellite

## temperature
* K

## atmosphere	
* No
* Components of atmosphere in order of % amount

## atm_pressure
* bar

## habitable_zone
* AU (how far from the star is the habitable zone)
* Not located in the habitable zone (for planets and moons)
* Located in the habitable zone (for planets and moons)

## orbiter_count
* count of orbiters (stars has planets, planets has moons)

## distance (orbiting distance)
* AU

## orbital_period
* years

## rotation
* days

## name_generated
* name generated, different for different celestial body

## name_known	
* Known name for celestial body

## gs-xxxx
* geoserver rendering stats
* Not used for players only used in rendering the map in geoserver
