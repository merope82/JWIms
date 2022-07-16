# Images taken during MIRI Commissioning

Over the past months, the MIRI Commissioning Team
has been privy to some gorgeous images that we are
glad to share with the public, now that all commissioning
data has been released. While I am responsible for reducing 
and color-combining these images (and I am sure others will 
do a much better job at it), if published anywhere,
please make sure to credit the entire "Team MIRI".

While beautiful to look at, these images were taken to
commission the instrument for scientific use. Below, I give
a short summary for each observation.

### PID 1039 - NGC 6552 (Seyfert 2 galaxy)

This is an image of a Seyfert 2 galaxy with an active center. 
The nucleus is quite bright at 5.6 microns, therefore produces 
the now familiar diffraction pattern and the MIRI curciform. 
Lots of background galaxies also visible, which are not present 
in the HST image.

The observations were carried out to test the latency
of the imaging detector. To quote for the program abstract:

*"The MIRI detectors can exhibit image persistence in images 
taken after bright sources are observed. The magnitude of 
the persistence is a function of flux of the source of origin 
as well as the time spent observing that source. This latent 
behaviour has been characterised during ground testing, but 
will need to be checked during commissioning to verify that 
the memory effect seen after a source has been observed on 
the detector, is as expected.*

*This CAR activity is designed to imprint an image on the 
imager and MRS detectors and analyse its decay (if any) for 
up to 25 minutes. This is felt to be sufficient to detect 
any large-scale changes from the on-ground behaviour. We 
repeat this test for a low and high background case to 
investigate the impact (F560W and F2100W)."*

There are also 25.5 micron images available, but I only 
reduced the F560W images.

### PID 1023 - Cat's eye nebula

A shockingly beautiful planetary nebula (much like the one shown
in the press release). The core of the nebula is quite small
(0.2 ly radius), but is surrounded by an enormous halo (radius
of 3.7 ly). The nebula is quite far, over 3000 ly from us!
The central star died roughly a 1000 years ago. There are theories
that the central star may have been a binary, but the MIRI image
does not show this (unlike for the southern ring nebula ERO image).

The observations were carried out to study how well annealing
removes latent images. To quote the program abstract:

*"The purpose of the functional test is to demonstrate the ability 
to perform detector anneals and to assess how well they eliminate 
pixel effects. During the procedure, the detector heaters are 
turned on, one at a time, until the anneal tempertaure set point 
is reached, and then the detector is allowed to cool to its nominal 
operating temperature. The rise and return of the tempertaure is 
monitored in real-time to ensure it meets requirements. The standard 
anneals test includes full frame unbinned images before the anneal, 
and when the 3 detectors have been annealed a series of full frame 
unbinned images are taken to monitor the background and noise levels 
as the detectors recover (the data will be analysed off-line). 
The first section will be repeated at regular intervals through the 
commissioning period (and into normal operations), to assess how 
frequently the detector anneals are required.*

*The tuning of anneal settings will only be performed for the initial 
anneals test.  This requires realtime commanding for the anneals 
(alllowing the settings to be chosen), and OSS/APT for the exposures. 
The settings determined from this will be transferred to OSS/APT 
for subsequent 'standard' anneals.  The first standard anneal will 
still use real time commanding, as this is expected to be scheduled 
very soon after the initial anneals test.*

*MIRI should be cold and stable, detector operating temperatures 
optimised and stable, MIRI-002 executed successfully, and 'table 7' 
loaded for MIRI-focussed telemetry. The CCC is closed.*

*The first two standard anneals will use dark exposures to monitor 
the recovery. The third and fourth will use a very bright target to 
produce saturation, allowing the removal of latent images to the 
characterised. The fifth and final instance will use a normal 
brightness target, to provide important information on how quickly 
the photometry recovers after an anneal has been done."*

### PID 1040 - LMC imaging for sky flat field 

A relatively empty region of the Large Magellanic cloud was imaged
using ALL MIRI imaging filters to generate "sky" flat field images.
The method was somewhat unique, dubbed the "thousand points of light",
where the variation of each stellar source as they were dithered was
used to measure the low-frequency component of the flat field.
Aligning the images shows what MIRI is capable of in all of its 
filters and the production of some really nice color images (make 
sure to zoom in on the full resolution image).

To quote the program abstract:

*"This measurement gives data the sky flat low spatial frequency component, 
and mask fading by the “thousand-points-of-light” technique. With this 
technique the overlapping regions will give the flat information. The highly 
overlapping mosaic gives the low spatial frequencly flat information, while 
the dither positions enhance the medium freq components and also the coverage 
of the detector. This data gives also information about cosmetics found on the 
detector, and also an acceptable SNR (~50-200 depending on the filter) pixel 
flat can be calculated using this data. The pixel flat will be compared with 
ground data for trending and also further improve calibration product. The correct 
sky flat will be measured for the first time with this measurement. Therefore 
acceptable SNR is necessary to calculate initial calibration product for the pipeline.
The fading of the entrance mask is slightly different for the telescope background 
in comparison with the fading of stars. Also, this flat component is filter 
dependent, therefore all filters are to be measured.*

*This LMC field was chosen to avoid quick saturation at the shortest wavelengths 
by >4mJy stars. The field has only one 3.2 mJy star @ 5.6um, what gives 6 groups 
before 80% hard saturation. The limit for the longest wavelegths is the telescope 
background."*

### PID 1052 - Background Field

This relatively empty image was taken of a field within Corona Borealis, with
the goal of studying the sky background variation as a function of telescope
pointing. As always RED galaxies everywhere!

To quote the program abstract:

*"This CAR aims at characterising variations in the telescope background emission 
spectrum observed by the MIRI imager. We will measure the observatory thermal 
background in the MIRI imager’s filters at two different attitude configurations: 
slew-to-cold and slew-to-hot. The aim is to bound the extreme cases for the 
thermal background emission spectrum which will be seen by MIRI during science operations.*
 
*There are already Goddard-led Comissioning Activites that include tests at hot/cold 
attitudes. CAR-752 and CAR-808 will keep the telescope at hot and cold attitudes for 
4 and 14 days, respectively. The proposal is to run the two parts of this MIRI CAR after 
the telescope has moved to the hot (slew-to-hot) and cold (slew-to-cold) position.
The current version of the CAR proposes four different targets. Two are in the region 
of the North and South Ecliptic Pole, respectively, and are alternatives to be used in 
the slew-to-hot observations. The other two lie close to an ecliptic latitute of about 
45 degress with respect to the North Ecliptic Pole, and have been selected for the 
slew-to-cold observations. All four targets are regions of the sky that do not have 
any obvious sources in the WISE 3-bands combined image (similar wavelength coverage to MIRI).*
 
*To trace the SED of the background measured by MIRI we will use a suite of different 
filters. Each of the selected filters probes a regime where a different observatory 
component (tower, sunshield, OTE) is expected to dominate. For instance, at 12 microns 
the sunshield emisson, that represents one of the main contributors to the thermal 
background seen by MIRI, begins to contribute. We are also adding the 7.7 microns 
filter, to measure a wavelength region that will not have significant contributions 
from the thermal emission, but rather from the zodiacal light. Once the set of filters 
has been used, we propose repeating the observation at 12.8 microns, to measure any 
potential relaxation in the sunshield emission. The observing sequence will then be:*
 
*F770W, F1280W, F1500W, F1800W, F2100W, F2550W and again F1280W.*
 
*A 2x2 mosaic with 50% overlap in the F1800W filter will allow us to evaluate the presence 
of spatial structure in the thermal emission at longer wavelengths, and to correlate 
it with the measurements in all other filters. It will also provide enough coverage 
and redundancy to apply background matching techniques to the data. Each mosaic 
tile/individual pointing uses a 3-points dither pattern per filter."*

### PID 1090 - MSX LMC 443

MIRI was not the driving instrument for this program, rather used in parallel mode with
NIRISS. While NIRISS was observing a small emission-line nebula in the LMC, MIRI was taking
parallel data at various wavelengths to verify that the NIRISS spectra remained within its
FOV.

Serendipitously, MIRI imaged a Mass Losing Asymptotic-Giant-Branch star. In the MIRI
image you can see the dust trail the star is leaving behind (at least I am pretty
sure that that is what we see). Oh, and obviously, background galaxies. They are
everywhere.

To quote the program abstract:

*" The wavelength dispersion solution of the GR150C and GR150R grisms of the WFSS mode 
will be measured at the center of the NIRISS FOV by observing an emission line source 
as a wavelength calibrator.  Subarray exposures are also included to ensure that 
non-saturated direct images of the target are captured. Care should be taken to ensure 
that both the direct image and the 1st-order spectral traces remain within the FOV. 
Coordinated parallel exposures with MIRI are also included to validate this capability."*

### PID 1171 - LMC Field Alignment test - MIRI first Light

This program provided a set of images taken using the F770W filter of a field within the
LMC. The PAH features are breathtaking! These images were taken on April 12/13, yielding
first light images with MIRI! Amazingly, one of the fields were also imaged at F560W, yielding
an opportunity to also make a color-combo MIRI image with our first-light observations.
As you can imagine, seeing this in April was a joyful moment for the team.

The goals of this program were quite simple. Quoting from the program proposal:

*"This proposal is to achieve better than 1 arcsec absolute pointing for MIRI during OTE 
commissioning. It is the implemention of OTE-34.*

*1. Determine the geometric distortion and plate scale of the MIRI Imager and MRS and 
their alignment relative to FGS1 and FGS2. 
2. The SOC PRD's "MIRI_SIAF.xml" are to be updated based upon these observations.
3. These observations will also provide an estimate of possible vignetting across 
the MIRI FOV."*

### PID 1464 - MIRI PSF check following MIMF recovery

This image was taken as part of the optical system checkout, following MIMF (muli-instrument,
multi-field) alignment. As you can see, the PSFs are sharp for MIRI, so the OTE alignment
went well. This may be less interesting than the other images, but it is still a nice image,
so I wanted to include it, especially as it helps to understand the various instrument and
system checkouts that were executed during commissinoning.
