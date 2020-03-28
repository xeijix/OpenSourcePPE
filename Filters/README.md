# Filters


## Idea

* Create a 40mm male threaded housing for filter material
* Use accessible materials:
	* MERV13 rated HEPA filters
	* Sanitary Pads - TODO: needs to be tested




## Testing Protocol Proposal

### Problem: 
* Lack accessibility to particle counters (reference [Standard Respirator Testing Procedures](https://www.cdc.gov/niosh/npptl/stps/apresp.html))
* Note that N95 masks means that the filter blocks at least 95% of 0.3 micron (300nm) test particles.
* We need to be able to test at least 300nm particles against our experimental filter

### Idea:
* Use a nebulizer to aerosolize a test solution. 

	> Mists generated using nanomist humidifiers have average particle diameters < 100 nm. whilst produced by ultrasonic humidifiers have particle diameters in the range 200 nm–1250 nm
	([Measurements of particle size distributions produced by humidifiers operating in high humidity storage environments](https://www.researchgate.net/publication/223728643_Measurements_of_particle_size_distributions_produced_by_humidifiers_operating_in_high_humidity_storage_environments))
	
	> Particle sizes from the nebulization process should ideally be in the range of 1 to 5 microns ([Factors Affecting Nebulized Albuterol Aerosol Particle Sizes](https://www.annemergmed.com/article/S0196-0644(13)00915-3/fulltext))

* Dye the solution with UV reactive dye
* The test filter should be layered with a collector paper (maybe coffee filter) as the last layer (most inner layer)
* Filter should be connected to a PAPR blower
* Nebulize the solution for x minutes (TBD)
* Observe the collector paper under UV to see if any particles made it through
* Use the same algorithm employed by NIOSH to determine the N rating


## Resources
* [Standard Respirator Testing Procedures](https://www.cdc.gov/niosh/npptl/stps/apresp.html)
* [What Are The Best Materials for Making DIY Masks?](https://smartairfilters.com/en/blog/best-materials-make-diy-face-mask-virus/)
* [Meltblown Nonwoven Fabrics: Why Meltblown Applications Will Increase](http://blog.fdinonwovens.com/meltblown-nonwoven-fabrics-why-meltblown-applications-will-increase)
* [Quantitative Respirator Mask Testing of HVAC Filters, Baby Wipes, Paper Towels, Coffee Filters](https://youtu.be/PAnpw4_8rfg)