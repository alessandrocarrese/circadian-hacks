# Beyond Blue Light: The Spectral Protection Ratio (SPR)

*Why color temperature tells you almost nothing about light safety*

---


You've probably heard that "blue light is bad" and that you should choose "warm" light bulbs with low color temperature (CCT). Maybe you've installed f.lux or Night Shift on your devices. Perhaps you've bought 2700K bulbs marketed as "eye-friendly."

Here's the problem: **color temperature is the wrong metric.**

Two LED bulbs with identical 6500K color temperature can have dramatically different effects on your metabolism, stress hormones, and eye health-with one being 4× more harmful than the other. The number on the box tells you almost nothing about safety.

What actually matters is something called the **Spectral Protection Ratio (SPR)**-a metric that captures what color temperature misses entirely.


## The Problem with Color Temperature

Color temperature (measured in Kelvin) describes how "warm" or "cool" light appears to your eye. A candle is around 1800K (warm orange), daylight is 5500-6500K (neutral white), and a clear blue sky can exceed 10000K (cool blue).

But CCT only describes *appearance*, not *composition*.

Here's a real-world example from spectral measurements:

| Light Source | CCT | Blue:Red Ratio | Metabolic Risk |
|--------------|-----|----------------|----------------|
| LED Bulb A | 6503K | 5.69:1 | HIGH |
| LED Bulb B | 6262K | 2.26:1 | Moderate |
| Natural Sun | 5500K | 1.29:1 | Baseline |

LED Bulb A and B have nearly identical color temperatures (within 4% of each other), yet Bulb A delivers **2.5× more metabolic stress** than Bulb B. Why? Because CCT doesn't account for:

1. **How much potentially harmful blue light** (440-470nm) the source emits
2. **How much protective red and near-infrared light** (620-850nm) accompanies it
3. **The ratio between protective and harmful wavelengths**


## Introducing the Spectral Protection Ratio

The Spectral Protection Ratio (SPR) measures what CCT ignores: **the balance between protective and potentially harmful wavelengths in a light source.**

**SPR = (Red + NIR power) / (Blue power)**

Where:
- **Red (620-700nm)**: Wavelengths that support mitochondrial function via cytochrome c oxidase activation
- **NIR (700-850nm)**: Near-infrared wavelengths that penetrate tissue and provide cellular protection
- **Blue (440-470nm)**: Wavelengths associated with photochemical stress and circadian disruption

A higher SPR means more protective wavelengths relative to potentially harmful ones.


## What Does Natural Light Look Like?

Before evaluating artificial light, we need a reference point. Natural daylight-the light environment our eyes evolved under-provides the baseline:

| Condition | SPR | Context |
|-----------|-----|---------|
| Direct morning sun | 4.95 | Full protection, high intensity |
| Natural shade | 1.74 | Diffuse light, prolonged exposure safe |
| Scattered sky (blue sky only) | 1.54 | Blue-enriched from Rayleigh scattering |
| Sunset/twilight | 1.58-2.62 | Transitional, low intensity |

**Key insight**: Even at its most blue-enriched (scattered sky), natural daylight maintains an SPR above 1.5. The protective wavelengths are always present.

For **prolonged indoor exposure**, the appropriate reference is natural shade (SPR 1.74), which represents the kind of diffuse daylight humans experienced for extended periods throughout evolution.


## How Do Artificial Light Sources Compare?

Here's where things get concerning:

| Light Source | SPR | Rating |
|--------------|-----|--------|
| Dimmed incandescent | 112.74 | Exceptional |
| Warm LED (best tested) | 6.21 | Excellent |
| Warm LED (typical) | 3.56 | Good |
| Natural shade baseline | 1.74 | Reference |
| Cool white LED | 1.0-1.5 | HIGH RISK |
| Cold LED (6500K) | 0.64 | CRITICAL |
| Computer monitor | 0.64 | CRITICAL |

**The pattern is stark**: Modern cool-white LEDs and computer monitors have *inverted* spectra compared to natural light. They deliver more blue than red/NIR-the opposite of what our eyes evolved to expect.


## Why SPR Matters for Health

### 1. Retinal Protection

Blue light (particularly 440-470nm) can induce photochemical damage to retinal tissues through:
- Oxidation of lipofuscin in retinal pigment epithelium
- Generation of reactive oxygen species (ROS)
- Direct mitochondrial dysfunction in photoreceptors

Red and NIR wavelengths counteract these effects by:
- Stimulating cytochrome c oxidase (Complex IV)
- Increasing ATP production
- Upregulating antioxidant defense systems
- Providing preconditioning against subsequent blue light damage

When SPR is high, the protective mechanisms can keep pace with oxidative stress. When SPR is low (or inverted), damage accumulates.

### 2. Metabolic Effects

Research shows that blue-enriched light without adequate red/NIR causes:
- **+30% insulin resistance** within 30 minutes of exposure
- **Elevated blood glucose** despite normal food intake
- **Paradoxical hunger** (cells can't access glucose despite high blood levels)

Meanwhile, red/NIR light:
- **Reduces blood glucose by 27.7%** at 2 hours post-meal
- Stimulates mitochondrial glucose consumption
- Supports normal insulin sensitivity

The blue:red ratio-closely related to SPR-predicts these metabolic effects far better than CCT.

### 3. Stress Response

Low SPR lighting correlates with:
- Elevated cortisol beyond normal morning peak
- Extended HPA axis activation
- Chronic low-grade stress markers

This isn't surprising: our circadian system interprets sustained high-blue/low-red light as "something is wrong" because it never occurs in nature.


## Practical SPR Thresholds

Based on natural light measurements and physiological research, here are evidence-based SPR guidelines:

| SPR Range | Rating | Recommendation |
|-----------|--------|----------------|
| > 6.0 | Excellent | Safe for extended evening use |
| 3.5 - 6.0 | Very Good | Safe for all-day use |
| 1.7 - 3.5 | Acceptable | Use with time limits (2-3 hours) |
| 1.0 - 1.7 | High Risk | Minimize exposure, morning only |
| < 1.0 | Critical | Avoid or supplement with red/NIR |

The critical threshold of **SPR ≥ 1.7** matches the natural shade baseline-the minimum protection level humans experienced during extended daylight hours throughout evolution.


## The NIR Problem

There's a second criterion that SPR alone doesn't capture: **absolute NIR content**.

Natural shade contains approximately **17% NIR** (as a percentage of total spectral power). Even the best-performing warm LEDs contain only **5-7% NIR**-a 60-70% deficit.

This means that even with a good SPR, most LED sources lack the absolute NIR exposure that natural light provides. For truly optimal indoor lighting:

- **SPR ≥ 1.7** (spectral balance)
- **NIR ≥ 15%** (absolute content)

Currently, no commercial LED meets both criteria. This suggests that supplemental NIR sources may be necessary for optimal indoor light environments.


## How to Estimate SPR Without a Spectrometer

You probably don't have a spectroradiometer at home. Here's a practical shortcut:

**Look for CIE R9 value** (deep red rendering index)

Analysis of LED sources reveals a strong correlation (r = 0.94) between SPR and R9 values:
- **R9 > 90**: Likely SPR > 3.5 (very good)
- **R9 50-90**: Likely SPR 1.5-3.5 (acceptable to good)
- **R9 < 50**: Likely SPR < 1.5 (problematic)

R9 measures how accurately a light source renders deep red colors. High R9 requires substantial red wavelength content-which directly contributes to SPR.

When shopping for bulbs, look for:
1. **High CRI (>90)** as a baseline quality indicator
2. **R9 specifically listed and >90** as the key SPR predictor
3. **Warm CCT (2700-3000K)** as a secondary indicator (correlated but not definitive)


## The Bottom Line

Color temperature is a marketing metric, not a safety metric. Two bulbs with identical CCT can have vastly different physiological effects.

**SPR tells you what actually matters**: the balance between protective and potentially harmful wavelengths in your light environment.

For healthy indoor lighting:
- **Target SPR ≥ 1.7** for prolonged exposure
- **Look for R9 > 90** when shopping for bulbs
- **Supplement with red/NIR** if using cool-white sources
- **Prioritize incandescent or high-quality warm LEDs** for evening use

Your eyes evolved under natural light with built-in protection. Modern artificial lighting has removed that protection. SPR helps you measure what's missing-and choose sources that restore it.


*Next in this series: "The NIR Deficit: What Modern Lighting Is Missing"*
