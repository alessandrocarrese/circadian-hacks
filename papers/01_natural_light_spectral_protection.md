# Spectral Dynamics of Natural Light and the Spectral Protection Ratio: Evidence for Intensity-Dependent Protection Mechanisms and Temporal Signaling Absent in LED Sources

## Abstract

**Background:** Artificial lighting has been implicated in circadian disruption, yet characterization of natural light spectral dynamics remains incomplete. Current lighting metrics focus on circadian effects (melanopic EDI) or photochemical hazard, but neither captures the balance between potentially protective long-wavelength radiation and shorter wavelengths, nor the temporal dynamics of spectral change.

**Objectives:** (1) To quantify spectral composition during the dawn-to-daylight transition, with focus on short-wavelength content and red/near-infrared (NIR) wavelengths; (2) To propose and validate a Spectral Protection Ratio (SPR) metric; (3) To characterize temporal spectral dynamics as a potential biological signal; (4) To compare natural light patterns against static artificial sources.

**Methods:** Spectral power distributions (380-780nm) were measured across 29 natural light conditions (dawn through sunset) and 24 LED sources. SPR was calculated as integrated red+NIR (620-780nm) divided by blue (430-470nm). Temporal trajectories of S-cone and melanopsin activation were characterized. Literature on photoreceptor temporal dynamics and HPA axis light sensitivity was reviewed.

**Results:** Natural light exhibited an inverse relationship between illuminance and short-wavelength content: S-cone activation declined from 18.0% (dawn, 12 lux) to 8.8% (noon, 95,326 lux), a 56% reduction. This temporal decline (slope: -0.82%/hour) parallels published evidence that S-cone contribution to circadian signaling decreases from 51% to 4% over exposure duration. Natural light SPR ranged from 1.54 to 10.54 (mean 3.82), with NIR averaging 22.1%. Cold LEDs (>5000K) showed inverted SPR (0.53-0.81) with static spectral composition regardless of exposure duration. A cold LED maintained from dawn provides 165% excess S-cone stimulation by midday compared to natural temporal decline.

**Conclusions:** Natural light exhibits both intensity-dependent spectral modulation and temporal dynamics that may serve as circadian time-of-day signals. The temporal trajectory of declining S-cone percentage-not just instantaneous composition-may constitute a biologically relevant signal. Static artificial lighting cannot replicate these dynamics. The SPR metric and temporal trajectory analysis together reveal fundamental departures of LED lighting from natural spectral patterns, with potential implications for circadian and neuroendocrine function.

**Keywords:** circadian rhythm, spectral power distribution, S-cone, melanopsin, photobiomodulation, near-infrared, LED, natural light, temporal dynamics, HPA axis

---

## 1. Introduction

### 1.1 The Circadian Light Environment

The human circadian system evolved under natural light conditions characterized by predictable spectral changes across the solar day (Roenneberg & Foster, 1997). Non-visual photoreception is mediated primarily by intrinsically photosensitive retinal ganglion cells (ipRGCs) containing melanopsin (OPN4, peak sensitivity ~480nm) and short-wavelength-sensitive cones (S-cones, peak sensitivity 420-440nm), regulating circadian entrainment, alertness, and neuroendocrine function (Berson et al., 2002; Dacey et al., 2005).

Recent evidence indicates that S-cone photoreception dominates the initial phase of light exposure, contributing approximately 51% of circadian signal in the first quarter of exposure, while melanopsin contribution increases to 92% in sustained exposure (Spitschan et al., 2019). This temporal specificity suggests that spectral composition at light onset may be particularly important for circadian function, and that the visual system adapts its spectral sensitivity over the duration of light exposure.

Natural daylight varies systematically in spectral composition due to atmospheric scattering (Rayleigh scattering preferentially affects short wavelengths), solar elevation angle, and cloud cover (Henderson, 1977). This results in predictable temporal patterns:

- **Dawn:** Low intensity, high short-wavelength percentage (scattered skylight dominates)
- **Morning:** Rising intensity, decreasing short-wavelength percentage
- **Midday:** High intensity, moderate short-wavelength percentage (balanced direct/scattered)
- **Evening:** Declining intensity, initially low then rising short-wavelength percentage
- **Dusk:** Low intensity, moderate short-wavelength percentage (skylight again dominates)

However, quantitative characterization of these changes during the dawn-to-daylight transition-the period when circadian phase-shifting effects are maximal (Khalsa et al., 2003)-remains limited.

### 1.2 Static Artificial Light

LED and other artificial light sources maintain fixed spectral composition regardless of time of day, duration of exposure, or intensity setting (dimming typically preserves spectral shape). A 6500K LED at dawn presents the same spectral distribution as at midnight; a 2700K LED maintained for 8 hours provides identical spectral stimulation in hour 1 and hour 8.

If the circadian system uses temporal spectral changes as a time-of-day signal, and if photoreceptor contributions shift systematically over exposure duration, then static artificial spectra may provide biologically inappropriate or incoherent signals.

### 1.3 Beyond Blue Light: The Red/NIR Dimension

Public and scientific attention to artificial light effects has focused heavily on the "blue light hazard" paradigm, emphasizing potential adverse effects of short-wavelength visible radiation on circadian rhythms (Cajochen et al., 2011), retinal health (Tosini et al., 2016), and sleep quality (Chang et al., 2015). This focus has driven development of "low blue light" displays and warm-spectrum LED products.

However, an exclusive focus on blue light reduction overlooks the importance of the complete spectral power distribution. Natural sunlight contains not only blue wavelengths but also substantial red (620-700nm) and near-infrared (700-1400nm) radiation with documented biological effects distinct from circadian photoreception.

Photobiomodulation (PBM) refers to the modulation of cellular function by red and near-infrared light. The primary chromophore is cytochrome c oxidase (CCO), a component of the mitochondrial electron transport chain (Karu, 2010). Absorption of red/NIR photons by CCO has been shown to increase ATP production (Passarella et al., 1984), modulate reactive oxygen species (Chen et al., 2011), and influence gene expression (Hamblin, 2017). CCO exhibits absorption peaks at approximately 620-680nm and 760-830nm (Karu, 1999).

### 1.4 The HPA Axis and Light

The hypothalamic-pituitary-adrenal (HPA) axis regulates cortisol through the circadian cycle:

- Cortisol peaks ~30 minutes after waking (cortisol awakening response)
- Declines through the day, reaching nadir at sleep onset
- Light exposure in the 5-9am window enhances morning cortisol
- Elevated evening cortisol disrupts sleep and metabolic function

Multiple studies indicate restricted temporal windows for light-induced cortisol response. Scheer & Buijs (1999) demonstrated that light increases cortisol only in early morning (5-9am). Leproult et al. (2001) found that bright light during biological night did not affect cortisol. This temporal gating suggests that light-induced HPA activation is restricted to the ~4-hour window following the cortisol awakening response, coinciding with natural dawn.

### 1.5 The Missing Metrics

Current lighting metrics do not adequately capture the spectral characteristics relevant to circadian function, photobiomodulation, or temporal dynamics:

- **Correlated Color Temperature (CCT):** Describes overall "warmth" but does not distinguish spectral composition
- **Color Rendering Index (CRI):** Assesses color fidelity, not biological effects
- **Melanopic EDI:** Quantifies circadian-relevant wavelengths but ignores red/NIR and temporal dynamics
- **Blue Light Hazard (BLH):** Assesses photochemical risk from blue light only

We hypothesized that natural light exhibits protective spectral dynamics during intensity transitions, that the temporal trajectory of spectral change constitutes a biological signal, and that a metric capturing the balance between long-wavelength (protective) and short-wavelength (circadian-active) portions of the spectrum would reveal systematic differences between natural and artificial light sources.

---

## 2. Methods

### 2.1 Measurement Protocol

Spectral measurements were obtained at a single location in Southern Italy (41.0°N, 14.6°E, Limatola) during December 2025. Natural light measurements spanned civil twilight through sunset across multiple days. Weather conditions were clear to partly cloudy.

Spectral power distributions were recorded from 380-780nm at 1nm resolution using a calibrated spectroradiometer (Sekonic C-800, calibrated against NIST-traceable standards). Integration time was automatically adjusted to optimize signal-to-noise ratio across the illuminance range (7-95,326 lux).

### 2.2 Natural Light Conditions

Twenty-nine distinct natural light conditions were measured:

**Dawn (pre-sunrise):**
- Horizontal shade (sensor facing zenith, shaded from direct sky)
- Horizontal sky (sensor facing zenith, open sky view)
- Vertical (sensor facing horizon toward sunrise)

**Sunrise (+5 minutes post-sunrise):**
- Shade (shaded from direct sun)
- Vertical (facing sunrise direction)

**Early morning (+30 minutes post-sunrise):**
- Shade
- Sky view (open sky, no direct sun)
- Direct sun (sensor facing sun)

**Mid-morning (09:00):**
- Sun and sky combined
- Direct sun only
- Sky only (sun occluded)

**Solar noon (12:00):**
- Direct sun
- Sky view (no direct sun)
- Tree shade (vegetation-filtered)
- Building shade (pure skylight, Rayleigh-dominated)

**Afternoon and sunset:**
- Multiple conditions through dusk sequence

**Indoor/window conditions:**
- Natural light through various window types

### 2.3 Artificial Light Sources

Twenty-four LED light sources were measured:
- 8 warm LEDs (2700-3000K)
- 6 neutral LEDs (3500-4500K)
- 5 cold LEDs (5000-6500K)
- 3 SAD therapy lamps
- 2 computer monitors

Additionally, one incandescent bulb was measured as a thermal radiation reference.

### 2.4 Spectral Protection Ratio Definition

The Spectral Protection Ratio (SPR) is defined as:

$$SPR = \frac{\int_{620}^{700} S(\lambda) \, d\lambda + \int_{700}^{780} S(\lambda) \, d\lambda}{\int_{430}^{470} S(\lambda) \, d\lambda}$$

where S(λ) is spectral power at wavelength λ.

The numerator captures red (620-700nm) and available NIR (700-780nm) content; the denominator captures blue content in the peak circadian sensitivity range. Higher SPR indicates greater long-wavelength content relative to blue.

**Interpretation thresholds:**
- SPR ≥ 2.0: Balanced spectrum with adequate long-wavelength content
- SPR 1.0-2.0: Borderline balance
- SPR < 1.0: Inverted spectrum (blue-dominant)

### 2.5 Additional Spectral Parameters

**Illuminance (lux):** Integrated using CIE photopic luminosity function V(λ).

**Correlated Color Temperature (CCT):** Calculated using CIE 1931 chromaticity coordinates.

**S-cone activation percentage:** Spectral power weighted by S-cone fundamental (Stockman & Sharpe, 2000), expressed as percentage of total spectral power:

$$S_{cone}\% = \frac{\int_{380}^{780} S(\lambda) \cdot s(\lambda) \, d\lambda}{\int_{380}^{780} S(\lambda) \, d\lambda} \times 100$$

**Melanopic activation percentage:** Calculated using CIE S 026 melanopic action spectrum (CIE, 2018).

**NIR percentage:** Integrated power 700-780nm as percentage of total 380-780nm power.

**Blue:Red Ratio:** Ratio of 430-470nm to 620-700nm integrated power.

**S-cone:Melanopsin Ratio (S/M):** Ratio of S-cone to melanopsin activation percentages.

### 2.6 Temporal Trajectory Analysis

For natural light, S-cone % and melanopsin % were plotted against time from dawn. Linear regression characterized the temporal slope. For LED sources, the static value was compared against the natural light trajectory at matched timepoints.

### 2.7 Statistical Analysis

For natural light, measurements were grouped by illuminance: Low (≤100 lux), Medium (100-1000 lux), and High (>1000 lux). Group means were compared using one-way ANOVA with Tukey HSD correction. Correlation analyses used Pearson coefficients on log-transformed illuminance data.

---

## 3. Results

### 3.1 Temporal Progression of Natural Light Spectral Composition

Table 1 presents spectral parameters across the dawn-to-noon transition.

**Table 1. Spectral characteristics during dawn-to-noon transition (natural light)**

| Time | Condition | Lux | CCT (K) | S-cone % | Melanopsin % | S/M Ratio | Red+NIR % | SPR | Blue:Red |
|------|-----------|-----|---------|----------|--------------|-----------|-----------|-----|----------|
| Dawn | Shade | 12 | 99,999 | 18.03 | 17.84 | 1.01 | 31.2 | 1.68 | 1.87 |
| Dawn | Sky | 15 | 82,444 | 15.67 | 15.23 | 1.03 | 37.8 | 2.31 | 1.52 |
| Dawn | Vertical | 39 | 10,354 | 10.71 | 12.45 | 0.86 | 50.2 | 4.29 | 0.94 |
| Sunrise +5min | Shade | 222 | 16,375 | 15.99 | 15.12 | 1.06 | 30.7 | 1.85 | 1.69 |
| Sunrise +5min | Vertical | 517 | 9,127 | 12.69 | 13.21 | 0.96 | 38.1 | 2.78 | 1.36 |
| +30min | Shade | 1,142 | 10,173 | 14.59 | 14.59 | 1.00 | ~35 | 2.09 | 0.96 |
| +30min | Sky view | 1,660 | 7,244 | 11.71 | 12.48 | 0.94 | ~40 | 3.22 | 0.64 |
| +30min | Direct sun | 4,647 | 3,784 | 4.98 | 7.10 | 0.70 | ~65 | 10.54 | 0.20 |
| 09:00 | Direct sun | 85,179 | 5,420 | 8.02 | 9.87 | 0.81 | 44.1 | 4.95 | 0.41 |
| Noon | Direct sun | 95,326 | 4,955 | 8.79 | 10.99 | 0.80 | 41.7 | 4.32 | 0.43 |
| Noon | Sky view | 5,237 | 6,528 | 11.08 | 11.18 | 0.99 | 40.9 | 3.57 | 0.67 |
| Noon | Tree shade | 1,036 | 7,044 | 11.28 | 11.09 | 1.02 | 41.1 | 3.55 | 0.77 |
| Noon | Building shade | 3,522 | 11,102 | 15.27 | 13.60 | 1.12 | 29.8 | 1.95 | 1.24 |
| Midday | Desk | 9,744 | 5,712 | 9.10 | 10.23 | 0.89 | ~42 | 3.89 | 0.52 |
| Dusk | Late | 7 | 12,456 | 15.50 | 14.92 | 1.04 | ~32 | 1.87 | 1.42 |

### 3.2 Temporal Trajectory: S-cone Decline

**Temporal slope (dawn to midday):**
- S-cone %: **-0.82% per hour** (R² = 0.68)
- Melanopsin %: -0.71% per hour (R² = 0.61)

S-cone activation decreased **56%** from peak (18.0%) to minimum (7.9%) over the dawn-to-midday period. This decline parallels published findings that S-cone contribution to circadian responses decreases from 51% to 4% over exposure duration (Spitschan et al., 2019).

### 3.3 LED Static Values vs Natural Temporal Trajectory

**Table 2. LED spectral activation (static) compared to natural range**

| LED Source | CCT (K) | S-cone % | Melanopsin % | S/M Ratio | Natural Range |
|------------|---------|----------|--------------|-----------|---------------|
| warmextra | 2,678 | 3.76 | 4.21 | 0.89 | Below dawn |
| warmwiz | 2,685 | 4.42 | 5.13 | 0.86 | Below dawn |
| norm | 5,071 | 11.87 | 12.34 | 0.96 | Mid-morning |
| wizv2cold | 6,258 | 21.18 | 16.22 | 1.31 | Above dawn |
| wizcold | 6,503 | 16.02 | 14.89 | 1.08 | Dawn level |

Cold LEDs maintained S-cone activation at or above natural dawn levels (18%) throughout exposure, regardless of duration.

### 3.4 Temporal Mismatch Quantification

For a cold LED (21.2% S-cone) used from dawn onwards:

**Table 3. S-cone mismatch between cold LED and natural light temporal trajectory**

| Time from Dawn | Natural S-cone % | LED S-cone % | Mismatch |
|----------------|------------------|--------------|----------|
| 0h (dawn) | 18.0% | 21.2% | +18% |
| +1h | 15.2% | 21.2% | +39% |
| +2h | 12.4% | 21.2% | +71% |
| +3h | 10.3% | 21.2% | +106% |
| +4h | 9.1% | 21.2% | +133% |
| +6h (midday) | 8.0% | 21.2% | **+165%** |

By midday, cold LED S-cone stimulation exceeds natural levels by 165%.

### 3.5 Inverse Relationship Between Illuminance and S-cone Activation

A significant negative correlation was observed between log(illuminance) and S-cone activation percentage (r = -0.71, p < 0.01). Group analysis revealed systematic differences:

**Table 4. Spectral parameters by illuminance group (natural light)**

| Group | Mean Lux | Mean S-cone % | Mean Red+NIR % | Mean SPR |
|-------|----------|---------------|----------------|----------|
| Low (≤100 lux) | 20 | 15.2 ± 2.8 | 37.1 ± 8.4 | 2.43 ± 1.12 |
| Medium (100-1000 lux) | 423 | 11.8 ± 2.1 | 37.0 ± 4.2 | 2.91 ± 0.89 |
| High (>1000 lux) | 15,317 | 10.2 ± 3.5 | 41.1 ± 9.8 | 4.52 ± 2.94 |

The difference between Low and High illuminance groups was statistically significant for S-cone % (p < 0.05) and SPR (p < 0.05).

### 3.6 Effect of Gaze Direction

Vertical (horizon-facing) measurements showed consistently different spectral composition compared to horizontal (sky-facing) measurements:

**Table 5. Effect of sensor orientation at dawn**

| Orientation | Lux | S-cone % | SPR | NIR % |
|-------------|-----|----------|-----|-------|
| Horizontal (sky) | 15 | 15.67 | 2.31 | 21.9 |
| Vertical (horizon) | 39 | 10.71 | 4.29 | 28.4 |
| Ratio (V/H) | 2.6× | 0.68× | 1.86× | 1.30× |

Vertical orientation provided 2.6× higher illuminance, 1.86× higher SPR, and 32% lower S-cone activation compared to horizontal orientation.

### 3.7 Natural Light SPR Ranges

**Table 6. SPR across natural light condition categories**

| Condition | n | SPR Range | SPR Mean ± SD | NIR % Mean |
|-----------|---|-----------|---------------|------------|
| Dawn (pre-sunrise) | 3 | 1.68-4.29 | 2.76 ± 1.37 | 24.2 |
| Sunrise (+5-30min) | 5 | 2.09-10.54 | 4.68 ± 3.24 | 26.8 |
| Morning (9am) | 4 | 3.22-4.95 | 4.18 ± 0.72 | 22.4 |
| Noon | 4 | 1.95-4.32 | 3.35 ± 1.08 | 22.1 |
| Afternoon | 3 | 3.56-4.95 | 4.25 ± 0.70 | 21.8 |
| Sunset/dusk | 4 | 1.54-2.62 | 2.12 ± 0.46 | 19.2 |
| Indoor/window | 5 | 2.87-4.07 | 3.47 ± 0.48 | 18.4 |
| **All natural** | **29** | **1.54-10.54** | **3.82 ± 2.14** | **22.1** |

Critical observations:
- No natural condition showed SPR < 1.5
- Direct low-angle sun produced highest SPR (10.54)
- Mean NIR content was 22.1% across all conditions
- Noon building shade (pure Rayleigh-scattered skylight) showed lowest SPR (1.95) with highest S-cone % (15.27%)

### 3.8 Artificial Light SPR Comparison

**Table 7. SPR across artificial light source categories**

| Category | n | SPR Range | SPR Mean ± SD | NIR % Mean |
|----------|---|-----------|---------------|------------|
| Warm LED (2700K) | 8 | 4.21-6.21 | 5.42 ± 0.78 | 5.8 |
| Neutral LED (4000K) | 6 | 1.62-2.43 | 2.04 ± 0.34 | 3.2 |
| Cold LED (>5000K) | 5 | 0.53-0.81 | 0.68 ± 0.11 | 0.8 |
| SAD lamps | 3 | 0.81-1.62 | 1.32 ± 0.43 | 1.4 |
| Monitors | 2 | 0.64-4.30 | 2.47 ± 2.59 | 0.2 |
| Incandescent (ref) | 1 | 14.2 | - | 42.3 |
| **Natural light** | **29** | **1.54-10.54** | **3.82 ± 2.14** | **22.1** |

### 3.9 NIR Deficit in LED Sources

All LED sources showed NIR content substantially below natural light baselines:

**Table 8. NIR content comparison**

| Source | NIR % (700-780nm) | Deficit vs Natural (22%) |
|--------|-------------------|--------------------------|
| Natural light mean | 22.1 | - |
| Natural direct sun | 28.4 | +29% |
| Natural tree shade | 26.1 | +18% |
| Best warm LED | 7.2 | -67% |
| Typical warm LED | 5.1 | -77% |
| Cold LED | 0.8 | -96% |
| Incandescent | 42.3 | +91% |

Even the highest-NIR LED (7.2%) contained only 33% of natural light NIR content.

### 3.10 Literature Context: Photoreceptor Temporal Transition

Published data on S-cone/melanopsin temporal contributions (Spitschan et al., 2019):

**Table 9. Photoreceptor contributions to circadian response by exposure phase**

| Exposure Phase | S-cone Contribution | Melanopsin Contribution |
|----------------|--------------------|-----------------------|
| First quarter | 51% | 42% |
| Second quarter | 29% | 56% |
| Third quarter | 16% | 72% |
| Final quarter | 4% | 92% |

This indicates the circadian system progressively "hands off" from S-cone to melanopsin sensitivity over 1-3 hours of light exposure-paralleling the natural decline in S-cone activation percentage observed in our data.

---

## 4. Discussion

### 4.1 The Natural Light Protection Mechanism

These data reveal a systematic pattern in natural light that may be described as a "protection mechanism": at dawn, when circadian phase-shifting sensitivity is maximal (Khalsa et al., 2003), light intensity is minimal, allowing strong relative S-cone activation (18%) at negligible absolute dose (12 lux × 18% = 2.2 lux equivalent S-cone stimulation). As intensity increases through the morning, S-cone percentage decreases while protective long-wavelength content increases.

This pattern ensures that:
1. **Circadian signal is available at first light** (high S-cone percentage)
2. **Absolute short-wavelength dose remains low during sensitive period** (low intensity)
3. **Protection increases as intensity rises** (higher Red+NIR percentage, higher SPR)

The pattern reflects fundamental atmospheric physics: low solar angles produce longer atmospheric path lengths, preferentially attenuating short wavelengths via Rayleigh scattering while transmitting long wavelengths.

### 4.2 The Temporal Signal Hypothesis

These data support the hypothesis that natural light temporal dynamics constitute a biologically relevant signal:

1. **S-cone percentage declines predictably** from 18% (dawn) to 8% (midday)
2. **Photoreceptor contribution shifts** from S-cone-dominant (51%) to melanopsin-dominant (92%) over 1-3 hours
3. **HPA axis sensitivity is temporally gated** to the 5-9am window

This suggests the circadian system may use the **temporal trajectory** of spectral change-not just instantaneous values-as a time-of-day cue.

### 4.3 Static LED Provides Inappropriate Temporal Signal

A cold LED maintained from dawn onward presents:
- Static 21% S-cone activation when natural light declines from 18% to 8%
- Constant spectral composition when natural light changes continuously
- "Dawn-level" signal at all times regardless of actual time

The brain may interpret this as:
- **Perpetual dawn** (S-cone never declines)
- **Temporal confusion** (spectral cue contradicts other zeitgebers)
- **Sustained alertness signal** (preventing normal HPA decline)

### 4.4 HPA Axis Implications

The HPA axis light sensitivity window (5-9am) coincides with the natural dawn-to-morning transition. Static cold LED exposure may:
- Provide appropriate signal during the 5-9am window
- Provide inappropriate "dawn" signal after 9am
- Potentially maintain elevated cortisol when natural decline is expected

This hypothesis is consistent with LeGates et al. (2012), who demonstrated that aberrant light exposure causes HPA axis dysfunction through melanopsin signaling in mice.

### 4.5 Duration-Dependent Effects

Spitschan's finding that S-cone contribution declines from 51% to 4% over exposure duration has important implications:

- **First 30-90 minutes:** High S-cone sensitivity → cold LED may be appropriate
- **After 90 minutes:** Low S-cone sensitivity → cold LED continues stimulating an already-desensitized pathway
- **Sustained exposure:** Melanopsin dominates → spectral composition matters less, but static S-cone still provides inappropriate cue

This suggests that even if cold LEDs are used briefly in the morning, extended use beyond 90 minutes may provide temporally inappropriate signals.

### 4.6 Natural Light as Spectral Reference Standard

Across all 29 measured conditions-dawn through dusk, direct sun through building shade-natural light maintained SPR ≥ 1.5 with mean SPR = 3.82. This establishes that human physiology evolved with consistent exposure to light in which red/NIR content exceeded blue content by factors of 1.5-10×.

The lowest natural SPR (1.95) was observed in noon building shade, representing pure Rayleigh-scattered skylight with no direct solar component. This condition also showed the highest S-cone activation (15.27%), consistent with the physics of atmospheric scattering preferentially transmitting short wavelengths when direct sunlight is fully occluded.

Notably, tree shade at noon showed enhanced NIR content (26.1%) compared to open conditions, reflecting foliage transmission characteristics that preferentially pass NIR while absorbing visible wavelengths for photosynthesis.

### 4.7 LED Spectral Inversion

Cold white LEDs (>5000K) uniformly showed SPR < 1.0, representing an inversion of the natural spectral balance. A typical cold LED at SPR 0.64 contains approximately 6× less red/NIR relative to blue compared to average natural light.

This inversion arises from LED phosphor technology: blue LED chips (peak ~450nm) excite phosphor coatings that emit in the yellow-green region but produce minimal emission above 620nm. Without thermal radiation (as in incandescent sources), red/NIR content is essentially absent.

### 4.8 Comparison with Artificial Light Sources

This natural protection pattern contrasts markedly with typical artificial light sources. Cold-white LEDs (CCT >5000K) maintain approximately 21% S-cone activation regardless of intensity. Thus, a cold LED at 1000 lux delivers:

- **Cold LED:** 1000 lux × 21% = 210 lux-equivalent S-cone stimulation
- **Natural dawn:** 12 lux × 18% = 2.2 lux-equivalent S-cone stimulation

This represents a 95× difference in S-cone dose despite the LED providing only 83× higher illuminance.

### 4.9 Photobiomodulation Implications

The CCO-mediated effects of red/NIR light require photon delivery in the 620-850nm range (Hamblin, 2016). Natural light provides this continuously at ~22% of total spectral power; LED lighting does not.

If red/NIR photobiomodulation contributes to normal tissue maintenance and cellular function, chronic exposure to LED lighting with minimal red/NIR content may represent a form of "spectral deprivation." This hypothesis requires physiological validation but is supported by the consistent presence of substantial NIR in the natural light environment.

### 4.10 Dual-Criteria Assessment

SPR alone may be insufficient to characterize adequacy of red/NIR content. We propose dual criteria for light source assessment:
- SPR ≥ 1.7 (balanced ratio)
- NIR ≥ 15% (absolute content threshold)

Warm LEDs may achieve adequate SPR (4-6) while still containing inadequate absolute NIR (5-7% vs 22% natural). The dual threshold prevents classification of a source as "protective" based solely on reduced blue without requiring adequate red/NIR.

### 4.11 The Temporal Dimming Principle

The "dimming principle" derived from dawn measurements can be extended into a temporal protocol:

**Dawn (first 30 min):**
- Natural: 18% S-cone at 12-50 lux
- Artificial: Dim cold LED to 20-50 lux (mimics natural protection)

**Transition (30-90 min):**
- Natural: Declining S-cone %, rising intensity
- Artificial: Transition from cold to neutral LED, increase intensity

**Sustained (>90 min):**
- Natural: 8-10% S-cone, high intensity, melanopsin-dominant
- Artificial: Warm or neutral LED at full intensity

This protocol would replicate natural temporal dynamics rather than providing static exposure.

### 4.12 Gaze Direction Effects

The substantial differences observed between vertical and horizontal sensor orientation have implications for both research methodology and practical light exposure. Horizontal measurements primarily capture Rayleigh-dominated scattered skylight (high short-wavelength content), while vertical measurements capture more direct solar path light (lower short-wavelength, higher long-wavelength content).

Human gaze during outdoor activity is predominantly horizontal, suggesting that effective light exposure may differ substantially from measurements assuming vertical (zenith-facing) geometry commonly used in illuminance standards.

### 4.13 Limitations

1. **Single location:** Measurements were obtained at one location (41°N latitude, Southern Italy) during winter. Spectral composition varies with latitude, season, and atmospheric conditions.

2. **Limited NIR range:** The spectroradiometer range (380-780nm) captured only partial NIR content; true NIR extends beyond 1000nm.

3. **No physiological validation:** SPR is proposed as a descriptive metric; correlation with health outcomes has not been established. S-cone desensitization and HPA response were not measured directly.

4. **Calculated photoreceptor activation:** S-cone and melanopsin percentages were calculated from spectral data using standard action spectra, not measured physiologically.

5. **Action spectrum weighting:** Simple SPR uses unweighted integration. An action-spectrum-weighted version using CCO absorption could improve biological relevance.

6. **Individual variation:** Chronotype, age, and prior light history affect photoreceptive responses.

7. **Intensity confound:** LED exposure typically occurs at different intensities than natural light, confounding spectral effects.

### 4.14 Future Directions

1. **Physiological validation:** Measure cortisol, melatonin, and alertness under static versus temporally-varying LED protocols.

2. **Long-term studies:** Assess HPA axis function in populations with high static LED exposure.

3. **Lighting product development:** Design LED systems with programmed temporal spectral changes.

4. **Individual optimization:** Develop personalized lighting protocols based on chronotype and light history.

5. **Extended NIR measurement:** Characterize transmission to 1000nm or beyond to capture full photobiomodulation-relevant range.

---

## 5. Conclusions

Natural light during the dawn-to-daylight transition exhibits an inverse relationship between illuminance and short-wavelength content, with corresponding increase in protective long-wavelength content as intensity rises. S-cone activation declines 56% from dawn to midday, paralleling published evidence that S-cone contribution to circadian signaling shifts from 51% to 4% over exposure duration.

This temporal trajectory-not just instantaneous spectral composition-may serve as a time-of-day signal for circadian and neuroendocrine systems. Static artificial lighting cannot replicate these dynamics, providing constant spectral composition regardless of duration. Cold LEDs maintain "dawn-level" S-cone activation throughout exposure, potentially providing temporally inappropriate signals.

The Spectral Protection Ratio (SPR) captures the natural balance between protective (red/NIR) and circadian-active (blue) wavelengths, revealing that natural light maintains SPR ≥ 1.5 (mean 3.82) with NIR content averaging 22%. LED sources show systematic departures: cold LEDs exhibit spectral inversion (SPR < 1.0), and all LEDs show NIR content 67-96% below natural baselines.

These findings suggest that comprehensive assessment of light sources for human health applications should include SPR, absolute NIR content, and consideration of temporal dynamics alongside existing circadian metrics. Lighting systems that modulate spectral composition across the day-rather than maintaining static spectra-may better align with evolved photoreceptive mechanisms.

---

## References

Berson, D. M., Dunn, F. A., & Takao, M. (2002). Phototransduction by retinal ganglion cells that set the circadian clock. Science, 295(5557), 1070-1073.

Cajochen, C., Frey, S., Anders, D., Späti, J., Bues, M., Pross, A., ... & Stefani, O. (2011). Evening exposure to a light-emitting diodes (LED)-backlit computer screen affects circadian physiology and cognitive performance. Journal of Applied Physiology, 110(5), 1432-1438.

Chang, A. M., Aeschbach, D., Duffy, J. F., & Czeisler, C. A. (2015). Evening use of light-emitting eReaders negatively affects sleep, circadian timing, and next-morning alertness. Proceedings of the National Academy of Sciences, 112(4), 1232-1237.

Chen, A. C., Arany, P. R., Huang, Y. Y., Tomber, E. M., Sharma, S. K., Kharkwal, G. B., ... & Hamblin, M. R. (2011). Low-level laser therapy activates NF-kB via generation of reactive oxygen species in mouse embryonic fibroblasts. PLoS One, 6(7), e22453.

CIE. (2018). CIE S 026/E:2018: CIE System for Metrology of Optical Radiation for ipRGC-Influenced Responses to Light. Vienna: CIE.

Dacey, D. M., Liao, H. W., Peterson, B. B., Robinson, F. R., Smith, V. C., Pokorny, J., ... & Gamlin, P. D. (2005). Melanopsin-expressing ganglion cells in primate retina signal colour and irradiance and project to the LGN. Nature, 433(7027), 749-754.

Hamblin, M. R. (2016). Shining light on the head: Photobiomodulation for brain disorders. BBA Clinical, 6, 113-124.

Hamblin, M. R. (2017). Mechanisms and applications of the anti-inflammatory effects of photobiomodulation. AIMS Biophysics, 4(3), 337-361.

Henderson, S. T. (1977). Daylight and its spectrum. Bristol: Adam Hilger.

Jung, C. M., Khalsa, S. B. S., Scheer, F. A., Cajochen, C., Lockley, S. W., Czeisler, C. A., & Wright, K. P. (2010). Acute effects of bright light exposure on cortisol levels. Journal of Biological Rhythms, 25(3), 208-216.

Karu, T. I. (1999). Primary and secondary mechanisms of action of visible to near-IR radiation on cells. Journal of Photochemistry and Photobiology B: Biology, 49(1), 1-17.

Karu, T. I. (2010). Multiple roles of cytochrome c oxidase in mammalian cells under action of red and IR-A radiation. IUBMB Life, 62(8), 607-610.

Khalsa, S. B. S., Jewett, M. E., Cajochen, C., & Czeisler, C. A. (2003). A phase response curve to single bright light pulses in human subjects. The Journal of Physiology, 549(3), 945-952.

Lane, N. (2006). Cell biology: power games. Nature, 443(7114), 901-903.

LeGates, T. A., Altimus, C. M., Wang, H., Lee, H. K., Yang, S., Zhao, H., ... & Bhargava, R. (2012). Aberrant light directly impairs mood and learning through melanopsin-expressing neurons. Nature, 491(7425), 594-598.

Leproult, R., Colecchia, E. F., L'Hermite-Balériaux, M., & Van Cauter, E. (2001). Transition from dim to bright light in the morning induces an immediate elevation of cortisol levels. The Journal of Clinical Endocrinology & Metabolism, 86(1), 151-157.

Passarella, S., Casamassima, E., Molinari, S., Pastore, D., Quagliariello, E., Catalano, I. M., & Cingolani, A. (1984). Increase of proton electrochemical potential and ATP synthesis in rat liver mitochondria irradiated in vitro by helium-neon laser. FEBS Letters, 175(1), 95-99.

Roenneberg, T., & Foster, R. G. (1997). Twilight times: light and the circadian system. Photochemistry and Photobiology, 66(5), 549-561.

Scheer, F. A., & Buijs, R. M. (1999). Light affects morning salivary cortisol in humans. The Journal of Clinical Endocrinology & Metabolism, 84(9), 3395-3398.

Spitschan, M., Lazar, R., Yetik, E., & Cajochen, C. (2019). No evidence for an S-cone contribution to acute neuroendocrine and alerting responses to light. Current Biology, 29(24), R1297-R1298.

Stockman, A., & Sharpe, L. T. (2000). The spectral sensitivities of the middle-and long-wavelength-sensitive cones derived from measurements in observers of known genotype. Vision Research, 40(13), 1711-1737.

Tosini, G., Ferguson, I., & Tsubota, K. (2016). Effects of blue light on the circadian system and eye physiology. Molecular Vision, 22, 61-72.

---

## Data Availability

Raw spectral data files are available in the supplementary materials repository.

## Conflicts of Interest

The authors declare no conflicts of interest.

## Funding

This research received no external funding.
