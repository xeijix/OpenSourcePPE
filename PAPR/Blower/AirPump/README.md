# Air Pump PAPR Blower

![Diagram](./images/output/diagram-01.png)

## Materials
* Air Pump, one of the following: 
	* [ONG NAMO Electric Air Pump](https://www.amazon.com/gp/product/B07PHSXD1B/ref=ox_sc_act_title_2) - Preferred
	* [Electric Air Pump](https://www.amazon.com/gp/product/B083LYCB4H/ref=crt_ewc_title_dp_1) - Preferred
* Gasket material, one of the following:
	* Silicone
	* Sugru 

## Caveat Emptor
* Air pumps are not made to be airtight. A PAPR system must be made airtight to prevent unmanaged particulate ingress.
* Air pumps must be disassembled (look for air pumps that are held together by screws). We need to be able to seal the air pump from the inside.
	* We cannot ensure proper seal when attempting to seal it from the outside. 
	* Areas which are problematic include:
		* Where the power cable mates with the chassis. This is because the chassis is rigid by the power cable is flexible. Flexing increases the chance of the sealing substrate detaching
		* If the air pump has a plug/socket instead of a permanently attached power cable, then the concern is that we cannot guarantee that the plug/socket design is airtight (and we cannot ensure a proper seal from the outside as that would obscure the actual socket)
* Manufacturer warns that prolonged usage of the air pump may cause the unit to overheat (they caution to run the pump for a max of 20 minutes). And the air vents are intended to help dissapate heat
	* However, I've successfully ran the pump for approximately 1.5hrs with the vents sealed. It seems to be ok.
	* Please be aware of possible overheating issue.


## TODO:
* Pressure test
* Battery pack design
* Cable lock design - Use to keep power cable locked to prevent accidental disconnects
* [Airflow Meter / Indicator](https://www.3m.com/3M/en_US/company-us/all-3m-products/~/3M-Versaflo-Air-Flow-Indicator-TR-971-for-TR-600-PAPR-1-EA/) - Used to verify the CFM meets requirements


## Instructions

1. Disassemble Air Pump
2. Seal all areas of ingress with silicone.
	* Possible areas of ingress:
		* Vents
		* Power socket / power cable mating point to the chassis
		* Switch
		* Seam where parts of the chassis mate
		* Screw holes
	* **NOTE**: you may want to reserve sealing the seam for after pressure testing the rest of your seals **OR** construct a gasket for the chassis seam instead of attempting to seal it silicone.
3. Attach the [40mm inlet](./files/Inlet.stl) and [40mm outlet](./files/Outlet.stl) to the appropriate areas of the air pump.
	* **NOTE**: Most air pumps are designed such that the outlet is along the seam of the chassis. That means that once you install the 40mm outlet component, you cannot take the pump apart without removing the 40mm outlet. 
4. Perform a pressure test using [40mm Female Valve Cap](../../../Components/files/40mm%20Female%20Valve%20Cap.stl), [40mm Male Cap](../../../Components/files/40mm%20Male%20Cap.stl)

