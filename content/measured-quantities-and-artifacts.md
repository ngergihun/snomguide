# Origin of Artifacts

This page explains the origins of measurement artifact in SNOM focusing mainly on imaging mode, but some of the problem also appear in nano-FTIR measurements.

```{figure} ./images/pshetPSD.svg
:label: pshetpsd
:width: 80%
:alt: Power spectrum of the detector signal in imaging s-SNOM.

The power spectrum of the detector signal in imaging mode s-SNOM. More details in Ref. {cite}`Ocelic2006`. Image from ME.
```

$$u_{n,m}=2k_ur_RJ_m(\gamma)\textcolor{red}{s_n}\cos{\left(\textcolor{blue}{\varphi_n}-\Phi_R-\frac{m\pi}{2}\right)}$$


## Amplitude and phase signal

Both amplitude and phase signal is derived from multiple frequency components. Using an even and an odd $m$ in the equation above, we acquire the real and the imaginary part of the complex Fourier component, which makes it possible to extract amplitude and phase values of the signal, which ideally means:

$$\textcolor{red}{s_n}=\sqrt{|u_{n,2}|^2 + |u_{n,1}|^2} ,\qquad \textcolor{blue}{\varphi_{n}}=\text{atan}\left(\frac{u_{n,1}}{u_{n,2}}\right)$$

## Problem I: Optical and Instrumental Sensitivity

Potential sources of variation include:

- Optical alignment
- Detector sensitivity
- Laser power
- AFM parameters

### Solution

- Use relative measurements.
- Measure a reference under comparable conditions.

## Problem II: Long- and Short-Term Stability

The signal can vary because of both long-term drift and short-term instability.

### Solution

Apply image corrections to reduce these effects.

## Problem III: Non-Local Effects

Non-local contributions can arise from indirect tip illumination.

## Problem IV: Negative Phase

Negative phase values may appear in the measured response and require further investigation during data processing.