---
# MIOP terms
methodology_category: sample extraction and purification
project: NOAA NWFSC Cook Inlet Beluga Whale
purpose: biodiversity assessment objective [OBI:0001969]
analyses: DNA extraction [OBI:0000257]
geographic_location: Cook Inlet [GAZ:00051076], Turnagain Arm [GAZ:00051080], Kenai River [GAZ:00197390]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], freshwater biome [ENVO:00000873]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024], freshwater river [ENVO:01000297], estuary [ENVO:00000045]
environmental_medium: sea water [ENVO:00002149], fresh water [ENVO:00002011]
target: deoxyribonucleic acid (DNA) [NCIT:C449]
creator: Zachary Gold
materials_required: vortexer [OBI:0400118], centrifuge [OBI:0400106], incubator [OBI:0000136], liquid extraction robot [OBI:0001097]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 	480
personnel_required: 1
language: en
issued:	2026-11-10
audience: scientists
publisher:	NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies
hasVersion: 1.0.0
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_vol_we_dna_ext: 1000
samp_vol_we_dna_ext_unit: mL
nucl_acid_ext_lysis: physical | enzymatic | thermal
nucl_acid_ext_sep: column-based
nucl_acid_ext: XXX
nucl_acid_ext_kit: QIAGEN Power Soil Pro Kit
nucl_acid_ext_modify: Modified for longmire buffer preservation of filter, additional centrifugation of longmire buffer to pellet DNA, transfer pellet in CD1 buffer to filter, reagent volume altered
dna_cleanup_0_1: 0
dna_cleanup_method: not applicable
concentration: not applicable
concentration_unit: ng/µl
concentration_method: Qubit Fluorometer v.4 dsDNA high sensitivity kit
ratioOfAbsorbance260_280: not applicable
pool_dna_num: not applicable
nucl_acid_ext_method_additional: not applicable
---

# NOAA NWFSC Power Soil Pro for eDNA Kit Protocol Using the Qiacube

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY All authors known to have contributed to the preparation of this protocol, including those who filled in the template.  | AFFILIATION | ORCID (visit https://orcid.org/ to register) | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Kim Parsons | NOAA NWFSC  | 0000-0003-4580-3651 |2026-11-10|
|Zachary Gold	|Ocean Molecular Ecology, NOAA PMEL|	0000-0003-0490-7630	|2026-11-10|

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protocols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| NOAA-PMEL-OME_Extraction_Protocol_DiscFilter_Centrifuge |https://github.com/HanWeinrich/NOAA-PMEL-OME_eDNA_DiscFilters_Extraction_Protocol_Centrifuge_BeBOP/blob/main/NOAA-PMEL-OME_eDNA_DiscFilters_Extraction_Protocol_Centrifuge.md  | 1.1.1  | 2025-11-14 |Internal |
| NOAA-PMEL-OME_Extraction_Protocol_Sterivex_Qiavac | https://github.com/Brown-NOAA/NOAA-PMEL-OME_Extraction_Sterivex_QIAvac_Protocol_BeBOP/blob/main/NOAA-PMEL-OME_eDNA_Sterivex_Extraction_Protocol_QIAVac.md | 1.2.0 | 2025-11-14 |Internal|
| NOAA-PMEL-OME_Qubit_Quantification_Protocol |https://github.com/HanWeinrich/NOAA-PMEL-OME-Qubit-Quantification-Protocol-BeBOP/blob/main/NOAA-PMEL-OME_Qubit_Quantification_Protocol.md | 1.0.1  |2025-11-14| Internal |
| Spens et al. 2017 |https://doi.org/10.1111/2041-210X.12683 | 1.0  | 2016-11-15  | External |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2026-11-10 | Initial release |


### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|BSC	|Biosafety cabinet |
|CICOES| Cooperative Institute for Climate, Ocean, and Ecosystem Studies|
|DNA	|Deoxyribonucleic acid|
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|MCE|Mixed Cellulose Ester|
|NOAA|National Oceanic and Atmospheric Administration|
|NWFSC	|Northwest Fisheries Science Center|
|OME	|Ocean Molecular Ecology|
|PCR| Polymerase chain reaction |
|PMEL	|Pacific Marine Environmental Laboratory
|PPE    | Personal protective equipment |
|UV| Ultraviolet|
|UW| University of Washington

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Extraction blank  | Extraction negative control. Typically, nuclease-free water or an empty filter is run through the DNA extraction process to control for contamination in the DNA extraction step.  |
| Field blank  | Sampling negative control. Typically, distilled or reverse osmosis water is run through a filter like a seawater eDNA sample to control for contamination in the field sampling step.  |
| No template control | PCR negative control. Typically, nuclease-free water is loaded in place of a sample on a PCR to control for contamination in the PCR step. |
| Positive control  | PCR positive control. Typically, a synthetic DNA strand, non-indigenous DNA extract, or intentionally designed mock community is loaded in place of a sample on a PCR to control for contamination and index hopping in the PCR step. |


## BACKGROUND

This document describes the required protocol to extract DNA from a 1 µm MCE disk filter.

### Summary

Nucleic acid extraction from MCE disk filters preserved in longmire's buffer using the QIAGEN Power Soil Pro Kit with some modifications to the manufacturer’s protocol. These extraction protocols were used by NWFSC for the Characterizing the Prey Landscape of Endangered Cook Inlet Beluga Whales Using an eDNA Time Series project. This protocol follows [Spens et al 2017](https://doi.org/10.1111/2041-210X.12683) protocol for longmire precipitation.

### Method Description and Rationale

The Qiagen Power Soil Pro Kit protocol is a widely used, highly reproducible, and easily executable DNA extraction protocol from disk filters collected in high sediment load environments. 1 µm MCE filters were chosen to enable one liter filtration in highly turbid Cook Inlet which has high glacial silt loads. This extraction protocol was modified from the manufacturer to hand filters preserved in longmires buffer stored at room temperature. Specifically, we conducted a slow, cold centrifugation of the longmire buffer supernatant to pellet out any DNA in solution in addition to extracting DNA from the filter itself. We also utilized a QiaCube liquid handling robot to speed up laboratory processing.


### Spatial Coverage and Environment(s) of Relevance

This protocol has been used to extract DNA from Cook Inlet, Turnagain Arm, and Kenai River.

### Personnel Required

One person with molecular biology experience.

### Safety

Solutions CD1 and CD3 contain chaotropic salts (e.g. guanidine hydrochloride) and is classified as category 4 for acute toxicity [(Safety Data Sheet)](https://www.qiagen.com/en-us/resources/download/kithandbookandprotocol/hb-2495-006-hb-dny-powersoil-pro-0623-ww). Solution EA and Solution C5 are flammable. Additional care should be taken when working with this buffer. This protocol also uses bleach and ethanol, both of which are classified as hazardous chemicals. Appropriate PPE must be worn, and standard safety procedures should be followed to avoid skin and eye exposure.

### Training Requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and previous DNA/RNA extraction experience) is required to conduct this protocol.

### Time Required to Execute the Procedure

Extracting DNA from 24 sterivex samples, including a field blank, takes 4 hours (240 minutes), including incubation time.

## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumables may need to be sterilized, some commercial solutions may need to be diluted or shielded from light during the operating procedure.

For a full extraction set, including 23 eDNA samples and a field blank:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |||||||
|Liquid Handling Robot|QiaCube |Qiagen|1|Can be substituted with generic|
|BioSafety II cabinet|Biological safety cabinet (INT-1100A2)|Kewaunee|1|Can be substituted with generic; internal UV light required.|
| Heatshaker | Fisherbrand incubating mini-shaker | Fisher Scientific | 1 | Can be substituted with generic; hot bath not recommend for sterility reasons. |
| Centrifuge | Eppendorf 5425 R  | Fisher Scientific | 1 | Can be substituted with generic - needs to fit 1.5 mL tubes. |
| Vortex | Analog vortex mixer | Fisher Scientific | 1 | Can be substituted with generic. |
| Vortex adapter for 1.5 mL tubes | Analog vortex mixer | Fisher Scientific | 1 | Can be substituted with generic. |
| UV crosslinker | UV crosslinker AH (115V), 234100 | Boekel Scientific  | 1 | Recommended not required; can be substituted. |
| Forceps |  Plastic Tweezers Acid Resistant, ESD Safe ID 51-1625-0224 | Oxford Instruments | 1 per sample | Can be substituted with generic. |
|-20°C freezer|TSX high-performance -20°C manual defrost freezer |Fisher Scientific|1|Can be substituted with generic but recommend temperature display.|
|Pipettor: 20 - 200 μL	|Pipetman P200L|Gilson|	1|Can be substituted with any accurate pipettor.|
|Pipettor: 100-1000 μL	|Pipetman P1000	|Gilson	|1|Can be substituted with any accurate pipettor.|
| Microtube racks | 96-Well flipper microtube racks | Fisher Scientific | 2 | Can be substituted with generic, but must fit 1.5-2.0 mL tubes. |
| 50 mL tube racks | SPL snap 50 mL tube rack (25 place) | SPL Life Sciences | 2 | Can be substituted but must fit sterivex. |
| 4-way tube racks | 4 way interlocking tube rack| Cole-Parmer | 4 | Can be substituted with generic, must fit 12 x 5 mL tubes and 50 mL tubes. |
|Trash bag holder|Bel-Art scienceware bench-top biohazard holders|Fisher Scientific|1|Can be substituted with generic.|
|Wash bottles|Safety wash bottles 500 mL for EtOH and bleach|VWR|2|Can be substituted with generic, but recommend different colored bottles for each reagent. Must be sterilized before use. |
|Cryoboxes|TruCool hinged lid cryoboxes|VWR|4|Can be substituted with generic, but recommend set color for eDNA. Must be sterilized before use. |
| **Consumable equipment** |
| 200 μL pipette tips  | TipOne RPT filter tips 200 μL graduated| USA Scientific |96 | Can be subsituted with generic. Must be sterile and filtered. |
| 1000 μL pipette tips  | TipOne RPT filter tips 1000 μL | USA Scientific |220 | Can be subsituted with generic. Must be sterile and filtered. |
| 1.5 mL tubes | Snap cap DNA LoBind 1.5 mL tubes, PCR-clean| Eppendorf |24 | Can be substituted with generic. Must be sterile. |
| 1.5 mL gasketed cryotubes | Screw cap gasketed 1.5 mL tubes, sterile| Corning |24 | Can be substituted with generic. Must be sterile. |
| 5 mL tubes | DNA LoBind 5 mL PCR clean centrifuge tube | Eppendorf | 24 | Can be substituted with generic, must be sterile/PCR clean |
| 50 mL falcon tubes | Falcon 50 mL high clarity conical centrifuge tube | Corning Falcon | 3 | Can be substituted with generic. Must be sterile. |
| Sterivex/syringe caps | Male/female sterile luer caps |McKesson | 48 | Can be substituted with generic, must be sterile and individually packaged. |
| 5 mL luer lock syringes | BD luer lock disposable syringe| BD | 24 | Can be subsituted with generic. Must be sterile and luer lock. |
| Kimwipes | Delicate task wipes | Kimtech | 5 | Can be substituted with generic. Must be lint-free.|
| Nitrile gloves | Powder free nitrile gloves | Fisher Scientific | 8 | Can be subsituted with generic nitrile gloves. Does not come sterile; it must be sterilized before use.|
| Lab notebook | Durable, hardcover lab notebook | Generic | 1 | Dedicated to the lab space|
| Writing utensils | Sharpies and pens | Generic | 2 | Dedicated to the lab extraction space. Not made of wood - must be able to be wiped down with bleach/EtOH.  |
|Trash bags for BSC|Teivio 1.2 Gallon 360 Counts Strong Trash Bags|Teivio|3|Can be substituted with generic.|
| **Qiacube Rotor Adapters** | QIAGEN Rotor Adapters | QIAGEN | 1 | For this protocol at scale (i.e., 250 samples)|
| **QIAGEN Extraction Kit** | QIAGEN Power Soil Pro Kit | QIAGEN | 1 | For this protocol at scale (i.e., 250 samples), additional volumes of some buffers need to be purchased.|
| *QIAGEN kit consumables* |  |  |  |  |
| Spin columns | Mini spin column | **Included in kit** | 24 | Kit contains 250 columns - sufficient for 250 extractions using this protocol. |
| Collection tubes | 2 mL collection tube | **Included in kit**| 500 | Kit contains 500 tubes - sufficient for 250 extractions using this protocol. |
| Microcentrofuge tubes | 2 mL collection tube | **Included in kit**| 500 | Kit contains 500 tubes - sufficient for 250 extractions using this protocol. |
| Elution tubes | 2 mL collection tube | **Included in kit**| 500 | Kit contains 500 tubes - sufficient for 250 extractions using this protocol. |
| *QIAGEN kit chemicals* |  |  |  |  |
| Solution CD1 | QIAGEN Solution CD1 | **Included in kit** | 200 mL | Kit contains 200 mL  - sufficient for 250 extractions. |
| Solution CD2 | QIAGEN Solution CD2 | **Included in kit** | 60 mL | Kit contains 60 mL  - sufficient for 250 extractions. |
| Solution CD3 | QIAGEN Solution CD3 | **Included in kit** | 175 mL | Kit contains 175 mL  - sufficient for 250 extractions. |
| Solution EA | QIAGEN Solution EA | **Included in kit** | 175 mL | Kit contains 175 mL  - sufficient for 250 extractions. |
| Solution C5 | QIAGEN Solution C5 | **Included in kit** | 175 mL | Kit contains 175 mL  - sufficient for 250 extractions. |
| Solution C6 | QIAGEN Solution C6 | **Included in kit** | 66 mL | Kit contains 66 mL  - sufficient for 250 extractions. |
| Eppendorf LoBind Tubes | 1.5 mL Eppendorf LoBind Tubes EP0030108442 | Eppendorf | 500 | Need 1 tube per sample |
| **Chemicals** |
| 100% molecular grade EtOH | 200 proof molecular biology grade ethanol | Fisher Scientific | 30 mL|Can be substituted with generic, must be 200 proof and molecular biology grade. |
| 70% EtOH | Molecular biology grade ethanol | 20 mL | For cleaning, can be substituted with generic. |
| 10% bleach | Hypochlorite bleach | Clorox | 10 mL| Remake every ~5 days as bleach decomposes quickly at 10% concentration. The majority is used in bottle/tube sterilization.|

## STANDARD OPERATING PROCEDURE

#### Preparation

To minimize the risk of sample contamination, this protocol should be carried out in dedicated eDNA extraction laboratories/rooms. When possible, the full dedicated lab space should be sterilized with UV.

### Before DNA Extraction

1. Run UV light for 30 minutes in the BioSafety II cabinet (BSC) and room, if not run since last use.
2. Sterilize workspaces and durable equipment, including pipettes within the BSC, with 10% bleach. Then wipe down all surfaces and equipment with 70% EtOH. If you have a UV crosslinker available, UV pipettes and tube racks regularly for 2 minutes.
3. Turn on the centrigue and set to 4°C. 
4. If the CD3 has precipitate, place in a heatshaker. Allow the buffer to heat until all precipitate is gone (~15 minutes), swirl as needed.
5. Set up a 50 mL tube racks for Power Soil Pro Tubes and label 12 tubes. Run 11 samples and 1 blank per extraction (Qiacube can only hold 12 samples). Ensure that all intermediate sample containers (i.e., bead tubes) are labeled with at least the sample number on the top.
6. Assemble sterilized forceps. 

**Recommended (not required)**: Aliquot buffers into 15 or 50 mL tubes to reduce contamination caused by repeated use of large volume bottles.

### DNA Extraction

1. Assemble 11 samples in 50 mL tube rack. 
2. Briefly spin bead tubes
3.  Using sterile forceps, transfer filter to tube.[NOTE: Optimal transfer is assisted with a 1000µL pipette tip to pull the filter to the rim of the tube and then use forceps to grab the top. With Cook Inlet samples there is a lot of sediment and frequently ~50 µL spills out during the transfer]
4. Spin remaining longmire solution at 6,000 g for 30 minutes at 4˚C.
5. After centrifugation, pipette off most of liquid (pellet is not stable, BE CAREFUL not to disturb). Dispose of liquid appropriately.
6. Pipette 800 µL of CD1 buffer to pellet, mix 10 x up and down, transfer to filter+bead tube. Add CD1 buffer directly to tube for the extraction blank. The rest of the extraction follows the [manufacturer's protocol](https://www.qiagen.com/en-us/resources/download/kithandbookandprotocol/hb-2495-006-hb-dny-powersoil-pro-0623-ww).
7. Place tubes on vortex adapter, max speed for 10 minutes.
8. Centrifuge at 15,000 x g for 1 minute
9. Transfer the supernatant to 2 ml Microcentrifuge Tube (500-600 µL expected)
10. Add 200 µL of CD2 buffer and vortex 5 sec
11. Centrifuge at 15,000 x g for 1 minute
12. Avoiding the pellet, transfer up to 850 µl of supernatant to 2 ml Microcentrifuge Tube (500–600 µl Expected) 
13. Place samples in 2mL shaker adapter to load into Qiacube. 

**Note**: This is a good time to pre-label your final 1.5 mL tubes. Tubes containing DNA aliquots should be labeled on both the top and side with at least the sample number. OME also labels the sides of storage tubes with the cruise number and date of extraction. 

**Qiacube Set-up**

- If not used recently, run Tightness Test to check tightness of tip gasket, additionally check with an operator for potential maintenance runs needed
With Qiacube door closed, turn on & allow to initialize.
- Ensure waste drawer is empty.
- Refer to [QIAcube Protocol Sheet](https://www.qiagen.com/us/resources/softwarerelateddownload/qiacube-classic-dna-protocols-v29)
- Add 1000 µL, Disposable Filter-Tips in both tip rack positions
- Pull blue QIAcube reagent bottle rack for fecal extractions. Check that it’s set up for PowerSoil.
- Fill any bottles with low volume. If not used recently then replace all buffers. If any have a precipitate, warm in hyb oven.

Reagent Bottle Rack:

|Position|Buffer|
|---|---|
|P1| [empty]|
|P2| Solution CD3|
|P3| Solution EA|
|P4| Solution C5|
|P5| Solution C6|
|P6| [empty]|

**Note**: Keep reagents capped until loading bottle rack into Qiacube. REMOVE lids when loading reagent tray into Qiacube!

- Load appropriate number of Qiacube rotor adaptors into acrylic set-up tray & fill with 1.5ml collection tubes & QIAamp spin columns.
- Load labeled 1.5 mL safe lock tube in each at position 3 of the Qiacube adaptors, ensure seeded all the way down. 
- Place filter columns in position 1, ensure seeded correctly, and discard collection tube. 
- Following location guide, load rotor adapters onto centrifuge inside Qiacube. Note sample locations. Extraction negative must go in position 1. 
- Loading 1 or 11 samples is not an option.
12 samples fill all spots.

**Set-up protocol on Qiacube:**

- Turn on Qiacube, if not already on.
Tap “DNA” 
- Scroll to “4. eDNA Power Soil Pro” and “Select”
- Confirm on “1.Soil”, tap “Select
- Scroll to “4. Var Elut Vol” and, tap “Select”
- Tap “Edit Modified” in the upper right
- For each of the four steps listed, confirm the following by scrolling to each item, tapping select for that item, and confirming the correct setting or scrolling to the correct setting, then tapping save.
	- “1.ElutionVolume” is set at 50 ul
- Return to “Sample Prep-Bench” walkthrough above

**Sample loading & running Qiacube:**

- When all above is done, load labeled 2.0ml tubes containing 850 ul lysate into Qiacube sample rack.
- Ensure that tubes are properly seated & lids tucked into lid slots.
- Extraction negative in position #1
- Record sample rack positions & sample numbers for troubleshooting if necessary (sample rack numbers correspond to rotor adapter locations on centrifuge).
- Select “Start” on the confirmed protocol.
Walk through the steps shown on screen, confirming the tips are in place, adding the un-capped reagents, adding the sample lysate etc.
- Return in 5-10 minutes to confirm passed all checks
Once done, check to make sure all sample tubes are empty
- If lysate remains in one of the sample tubes, note the sample position number.
- Remove the rotor adapters to the adapter rack
- Remove reagent rack, replace lids
- Pull elution tubes and check there is volume in it before tossing sample tube and filter, dispose of liquid waste in rotor adaptors in EtOH waste, then adaptor is tossed.

15. Quant eluted DNA with High Sensitivity reagents
16. Store eDNA in the freezer (-20˚C, or -80˚C).



### Quality Control

A negative control (field blank or extraction blank) is included in every 12 set of extractions (i.e., 11 samples + NC). Samples and controls are quantified to verify DNA concentration using the [NOAA-PMEL-OME-Qubit-Quantification-Protocol-BeBOP](https://github.com/HanWeinrich/NOAA-PMEL-OME-Qubit-Quantification-Protocol-BeBOP/blob/main/NOAA-PMEL-OME_Qubit_Quantification_Protocol.md). Lastly, samples are PCR amplified alongside no template and positive controls.

**Recommended (not required):** OME splits all DNA extracts into three aliquots: a working stock for immediate use at -20°C (~20-30 µl) in a 1.5 mL tube; a backup stock at -20°C in case the working stock is finished or contaminated (~30-40 μL) in a 1.5 mL tube; and an archival stock in a 1.5 mL gasketed cryotubes and frozen at -80°C indefinitely (~40 µl). All are stored in labeled cryoboxes.

## REFERENCES

- Spens, J., Evans, A. R., Halfmaerten, D., Knudsen, S. W., Sengupta, M. E., Mak, S. S. T., Sigsgaard, E. E., & Hellström, M. (2017). Comparison of capture and storage methods for aqueous macrobial eDNA using an optimized extraction protocol: the advantage of an enclosed filter. Methods in Ecology and Evolution, 8 (5), 635-645. https://doi.org/10.1111/2041-210X.12683