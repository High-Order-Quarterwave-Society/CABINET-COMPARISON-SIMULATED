# HOQS Subwoofer CABINET-COMPARISON-SIMULATED
HornResp Software Cabinet comparison at 1 Watt and exported impulse response into REW.
The cabinet base [X]Ohm is set as base. For example 2x 8Ohm drivers in parallel = 1w/4Ohm 1x 4Ohm = 1w/4Ohm and 1x 8Ohm is 1w/8Ohm

Since HR Impulse export is 20 to 30 dB higher, all measures are corrected by taking the HR 100Hz=SPL line. The SPL from HR is then SPL corrected on the 100Hz line in REW.

## Current list of cabinet simulations:

### 21" loudspeaker cabinets
- Othorn 21" Tapped Horn 
- Paraflex Type-R-121 Dual Quarterwave resonator horn
- Paraflex TC2E-121 Dual Quarterwave resonator horn- 
- SKhorn (SKRAM) Hybrid Bassd Reflex / bandpass Horn 2x 21"

### 18" loudspeaker cabinets
- Paraflex Type-C-CRAM-218 Dual Quarterwave resonator horn
- Paraflex Type-O-CRAM-218 Dual Quarterwave resonator horn
- Paraflex Type-R-118 Dual Quarterwave resonator horn
- OHA-BR218  Standard Bass-Reflex 2x 18"
- OTH-218EB dual Tapped Horn 2x 18"
- Cubo-18 Tapped Rear Bandpass Horn 1x 18"
- Paraflex Type-R-118  Dual Quarterwave resonator horn 1x 18"

### 15" loudspeaker cabinets
- Paraflex TC2E-215 Dual Quarterwave resonator horn  2x 15"
- BFM Tuba-60 Front Loaded Horn 1x 15"
- BFM Titan-48 Front Loaded Horn 1x 15"



## NOTE:
Take note that HornResp sofware peaks and valleys are slightly larger (or sometimes non-existent) in the real world measurements

## There is no competition
Comparing cabinets output is not a competition, there is not a 'BEST' performing subwoofer cabinet ift there was, we all would be using the same cabinet after 100 years of loudspeaker innovations. There is only the right tool for the Job and personal taste. 

In 99% of the cases all subwoofers may operate **within** the range of 30Hz <> 100Hz. The bandwidth is Limited by selecting Crossover points. it should be chosen to get the most transient and output performance and at the same time protecting the loudspeaker driver. Using a subwoofer above 100hz is waste of performance. Using subwoofer below 30hz is waste of power. You choose the right subwoofer cabinet for the job (or music type) 

For Public Address (PA) we intend to deploy multiple cabinets of the same type. You can deploy 4 or you can deploy 60. Using multiple subs flattens out the bandwidth and coupling (summation) of the cabinets within the 0 <> 120 degree phase will give you optimal results. 

### Extending frequencie range of lower notes
Using multiple cabinets, a single cabinet will not 'magically' add 10Hz to its range. Multiple subwoofers can result in increased sound pressure levels for lower frequencies. This is due to a phenomenon called "coupling" or "summation," where the sound waves produced by multiple subwoofers combine constructively to create a more powerful bass response. The combined output of multiple subwoofers can be louder and more impactful than that of a single subwoofer, particularly in larger or challenging acoustic environments.

### Long throw should not be used to point out directional perfomance of the subwoofer cabinet
The term "long throw" used in the context of subwoofers can be confusing when considering the omnidirectional nature of low-frequency sound waves. While subwoofers radiate sound in all directions, the term "long throw" primarily refers to the physical movement capability of the subwoofer's **driver** rather than its dispersion characteristics.

### Directivity
Enclosure designs with horn-loaded or ported configurations can exhibit some degree of directivity, but it is generally limited to specific frequency ranges and is not as pronounced as with high-frequency drivers. As sound waves propagate, they naturally disperse and spread out in all directions. This behavior is more pronounced for lower frequencies due to their longer wavelengths. Consequently, subwoofers radiate sound in a more omnidirectional or semi-omnidirectional manner, meaning they distribute sound relatively evenly in multiple directions rather than in a tightly focused beam.

![Alt text](/Subwoofer-comparison-simulated-output-at-1w.png?raw=true "REW Screenshot")
