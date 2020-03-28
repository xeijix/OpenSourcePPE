# PAPR Blower

## Idea
* Take a fan capable of high CFM and static pressure
* Create an enclosure around the fan with a 40mm round-threaded inlet and outlet 
* Power the fan with a USB battery pack (preferable) or a 12v battery pack
	* Can we construct a dock to use different drill batteries easily?
		* Issues: There's no battery management system on the battery itself. The tool is required to handle
			* [reference](https://syonyk.blogspot.com/2017/04/dewalt-20v-max-60ah-pack-teardown.html)
			* Would need to use something like: [20V Max Power Source for Dewalt Heated Jacket DCB091 Converters with USB and 12V Outlets Fit for Dewalt 20V Battery](https://www.amazon.com/dp/B07HLW5FYG/ref=sspa_dk_detail_7)

## Requirements
* CFM with filter attached must exceed: 
	* 4 CFM for masks
	* 6 CFM for hoods
	* Reference: [General Cautions and Limitations for Powered Air-Purifying Respirators (PAPR)](https://wwwn.cdc.gov/NIOSH-CEL/Limitations/Papr)
* 40mm female threading for inlet
* 40mm male threading for outlet
* Battery connection must be locked to prevent accidental disconnects

## Testing Requirements
* Enclosure must be airtight to prevent contaminated air seepage 

## Testing Protocol
* Seal inlet and outlet with [40mm Female Valve Cap](../../Components/files/40mm\ Female\ Valve\ Cap.stl), [40mm Male Cap](../../Components/files/40mm\ Male\ Cap.stl)
* Pressurize blower to x (target pressure TBD)
* Check that pressure is holding steady
* Submerge in water for y minutes (TBD)
* Observe for air leaks

## Possible Designs
* [Air Pump Design](./Air\ Pump/README.md)


## References
* [DeWalt Battery adapter](https://www.thingiverse.com/thing:2723049)
* [DeWalt Drill Battery Mount for Electric Skateboard (+anything else)](https://www.thingiverse.com/thing:3008278)


## Possible supplies
* Mattress air pump
	* [Omont Rechargeable Air Pump](https://www.amazon.com/dp/B07RV9J3TV/ref=sspa_dk_detail_4)
	* [Electric Air Pump](https://www.amazon.com/gp/product/B083LYCB4H/ref=crt_ewc_title_dp_1)
	* [LotFancy Electric Air Pump,](https://www.amazon.com/gp/product/B013UQ0T2Y/ref=crt_ewc_title_dp_2)
	* NOTES:
		* Static pressure and CFM unknown. May not be the same from brand to brand.

* 40mm Server Fans
	* [GFB0412EHS Delta 40mm 56mm 4056 1U server high speed fan DC12V 1.82A cooling fan](https://www.newegg.com/p/1YF-00B0-000K7?Item=9SIAAES8G63859)
		* 60-65 CFM
		* Static pressure unknown

	* [New original Delta FFB0412VHN -F00 DC 12V 1.92W 0.24A 9500RPM Cooling Fan Speed 3-Wire 3-pin 4cm 4028 40*40*28mm](https://www.newegg.com/p/1YF-00B0-001J0?Item=9SIAAES91X3779)
		* >80 CFM
		* Minimum Wind Pressure: 0.120 Pa

* Silicon adhesive to seal components airtight

* Battery pack
	* [TalentCell Rechargeable 12V 6000mAh](https://www.amazon.com/TalentCell-Rechargeable-12000mAh-Multi-led-indicator/dp/B00ME3ZH7C/ref=sr_1_3?dchild=1&keywords=12v+battery+pack&qid=1584844335&sr=8-3)
	* [TalentCell 12V Lithium ion Battery PB120B1, Rechargeable 38400mAh](https://www.amazon.com/dp/B07H8F5HYJ/ref=sspa_dk_detail_1)
	* [Makita 12V battery](https://www.amazon.com/Makita-BL1021B-2-Lithium-Ion-Battery-Pack/dp/B01N1UY51P/ref=sr_1_35)
	* [Dewalt 12V battery](https://www.amazon.com/DEWALT-DCB127-2-Lithium-Battery-2-Pack/dp/B00JQ74WCA/ref=sr_1_4)
	* [Conventer DCB091 Power Source Replace for Dewalt 20V Battery Charge for Dewalt Heated Jacket with USB and 12V Outlets Fit for Dewalt 20V MAX Battery 2packs](https://www.amazon.com/dp/B082YSSJ13/ref=sspa_dk_detail_7)
	* [20V Max Power Source for Dewalt Heated Jacket DCB091 Converters with USB and 12V Outlets Fit for Dewalt 20V Battery](https://www.amazon.com/dp/B07HLW5FYG/ref=sspa_dk_detail_7)
	
* Connection terminals
	* [Ace Insulated Wire Male Disconnect Blue 10 pk](https://www.acehardware.com/departments/lighting-and-electrical/boxes-fittings-and-conduit/lugs/34529)