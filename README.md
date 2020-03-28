# OpenSourcePPE

**DISCLAIMER**: This is a work-in-progress project and none of the methods or equipment outlined in this repository have been medically approved. Use at your own risk.


## Purpose

Our frontline healthcare workers (HCWs) are running low on personal protective equipment (PPEs). Sourcing these items is becoming difficult as many of the items are either made outside of the US or the components are made outside of the US. Many countries are either withholding crucial supplies because they need it in their own fight against Covid-19, or their own infrastructure is collapsing.

The goal of this repository is to determine simple, actionable, and reliable steps people can take in order to produce their own PPE.

## Requirements

* PPEs must use off-the-shelf components. As our supply chain continues to fail, we must be able to adapt to using components which continues to have large surpluses.
* PPEs should not rely on dwindling medical supplies. We must look towards other non-medical areas when sourcing supplies as we do not want to further cripple the stockpile of medical equipment
* PPEs should be adaptable. Many multi-component PPEs (eg. Personal Air-Purifying Respirators, AKA PAPRs) have multiple components which are not standardized; our design must allow us to interface with non-standard equipment to prolong the use of any mass-produced PPEs. 


## Areas of Interest

* Personal Air-Purifying Respirators (PAPRs)
	* Hoods
	* Masks
	* Blowers
* N95 Filters - housing and possible filter material
* Component Adapters - for adapting between components of different brands
* Method of disinfection for reusable medical devices


## Standards

All OpenSource components should follow a common standard so that components are interchangeable

* 40mm External Round Threading (male connector) - for hose-like connections (eg, filter to PAPR blower; blower to air-supply hose, air-supply hose to mask, etc)
	* Pitch: 3.5mm
	* Section size: 3mm (2mm with 1mm diameter offset)
	* Minor Diameter: 36.65mm (38.25) (37.65)
	* Major Diameter: 39.65mm 
	* Coil length: 14.5mm
	* Length: 16.5mm	

* 40mm Internal Round Threading (female connector)
	* Minor Diameter: 38.65mm
	* Major Diameter: 40.65mm
	* Section size: 2mm

## References
* [Zhejiang University - Handbook of COVID-19 Prevention and Treatment](https://covid-19.alibabacloud.com/)
* [Open Source COVID19 Medical Supplies](https://www.facebook.com/groups/670932227050506/)
	* [Open Source COVID19: Our Intent, Needs, and Your Role](https://docs.google.com/document/u/0/d/1-71FJTmI1Q1kjSDLP0EegMERjg_0kk_7UfaRE4r66Mg/mobilebasic)
* [MasksForDocs](https://masksfordocs.com/)
	* [Twitter Post](https://twitter.com/MasksForDocs/status/1241461367720120320)
* [DIY MED](https://www.diymed.org/home)