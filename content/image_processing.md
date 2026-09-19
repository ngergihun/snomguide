# Image processing

```{figure} ./images/SNOMschematics.svg
:label: snomsetup
:width: 100%
:alt: Basic schematics of a scattering-type scanning near-field microscope setup.

Schematics of the basic scattering-type scanning near-field microscope setup. More details in {cite}`Ocelic2006`. Image from ME.
```
## Image formation

Just like in AFM, the image is created by **raster scanning** the sample and recording the signal at each point resulting in a pixelated image.
In imaging mode, usually a single-wavelength source is utilized, like a diode or gas laser. The signal is detected by a double demodulation technique referred as pseudo-heterodyne detection. {cite}`Ocelic2006`

The advatanges of this detection scheme:
- Almost background-free detection
- Complex optical data: <span style="color: blue;">amplitude</span> and <span style="color: red;">phase signals</span>
- Multi-order demodulation 
- Simultanous AFM topography and mechanical amplitude and phase

As the final dataset, we receive **mechanical** (M) and **optical** (O), amplitude (A) and phase (P) images demodulated at higher harmonics of the tip oscillation frequency $(n\Omega)$. For example:
- <span style="color: blue;">Optical amplitude images</span>: O1A, O2A, O3A, ....
- <span style="color: red;"> Optical phase images</span>: O1P. O2P, O3P, ....

```{note} 
- Theory of contrast
    + How to understand images
    + Why do we need normalization
- Image artifact types
    + type1
    + type2
```