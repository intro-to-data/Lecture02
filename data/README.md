# About

Documents the data sets found in this folder.

# Diamonds

**Description:** A dataset containing the prices and other attributes of almost
54,000 round cut diamonds.

**Format:** 

- A data frame with 53940 rows and 10 variables:
- **price:** price in US dollars (\$326–\$18,823)
- **carat:** weight of the diamond (0.2–5.01)
- **cut:** quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- **color:** diamond colour, from D (best) to J (worst)
- **clarity:** a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
- **x:** length in mm (0–10.74)
- **y:** width in mm (0–58.9)
- **z:** depth in mm (0–31.8)
- **depth:** total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43–79)
- **table:** width of top of diamond relative to widest point (43–95)



# Penguins

**Description:** Size measurements for adult foraging penguins near Palmer
Station, Antarctica. Includes measurements for penguin species, island in Palmer
Archipelago, size (flipper length, body mass, bill dimensions), and sex.

**Format:** 

- A tibble with 344 rows and 8 variables:
- **species:** a factor denoting penguin species (Adélie, Chinstrap and Gentoo)
- **island:** a factor denoting island in Palmer Archipelago, Antarctica (Biscoe, Dream or Torgersen)
- **bill_length_mm:** a number denoting bill length (millimeters)
- **bill_depth_mm:** a number denoting bill depth (millimeters)
- **flipper_length_mm:** an integer denoting flipper length (millimeters)
- **body_mass_g:** an integer denoting body mass (grams)
- **sex:** a factor denoting penguin sex (female, male)
- **year:** an integer denoting the study year (2007, 2008, or 2009)

**Source:**

Adélie penguins: Palmer Station Antarctica LTER and K. Gorman. 2020. Structural size measurements and isotopic signatures of foraging among adult male and female Adélie penguins (Pygoscelis adeliae) nesting along the Palmer Archipelago near Palmer Station, 2007-2009 ver 5. Environmental Data Initiative https://doi.org/10.6073/pasta/98b16d7d563f265cb52372c8ca99e60f

Gentoo penguins: Palmer Station Antarctica LTER and K. Gorman. 2020. Structural size measurements and isotopic signatures of foraging among adult male and female Gentoo penguin (Pygoscelis papua) nesting along the Palmer Archipelago near Palmer Station, 2007-2009 ver 5. Environmental Data Initiative https://doi.org/10.6073/pasta/7fca67fb28d56ee2ffa3d9370ebda689

Chinstrap penguins: Palmer Station Antarctica LTER and K. Gorman. 2020. Structural size measurements and isotopic signatures of foraging among adult male and female Chinstrap penguin (Pygoscelis antarcticus) nesting along the Palmer Archipelago near Palmer Station, 2007-2009 ver 6. Environmental Data Initiative https://doi.org/10.6073/pasta/c14dfcfada8ea13a17536e73eb6fbe9e

Originally published in: Gorman KB, Williams TD, Fraser WR (2014) Ecological Sexual Dimorphism and Environmental Variability within a Community of Antarctic Penguins (Genus Pygoscelis). PLoS ONE 9(3): e90081. doi:10.1371/journal.pone.0090081

This documentation (and the data) are based on the data found in the
palmerpenguins package version 0.1.0.

