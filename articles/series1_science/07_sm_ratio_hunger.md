# The S/M Ratio: Why Some LEDs Trigger Hunger

*A new metric reveals the appetite-disrupting difference between 448nm and 455nm*

---

You've heard that "blue light" affects circadian rhythms. But this framing misses something critical: **not all blue light is equivalent**, and the effects extend far beyond sleep.

Spectral analysis reveals that a 7nm difference in blue peak wavelength-invisible to the naked eye-can determine whether a light source triggers chronic hunger or leaves appetite regulation intact.

The key metric: the **S-cone to Melanopsin ratio (S/M)**.


## What is the S/M Ratio?

The S/M ratio measures the balance between two photoreceptor systems:

**S-cones** (short-wavelength cones)
- Peak sensitivity: ~440nm (violet-blue)
- Connect to dopaminergic amacrine cells in the retina
- Associated with alertness and reward-seeking behavior

**Melanopsin** (in ipRGCs)
- Peak sensitivity: ~480nm (cyan-blue)
- Projects to hypothalamus including appetite-regulating regions
- Associated with circadian signaling and satiety

**S/M Ratio = Light power in 420-460nm ÷ Light power in 460-500nm**

A higher S/M ratio means more S-cone stimulation relative to melanopsin-more "seek" signal relative to "satisfied" signal.


## What Does Natural Light Look Like?

Measurements across 33 natural light conditions-dawn through dusk, direct sun through deep shade-reveal a consistent pattern:

| Condition | S/M Ratio |
|-----------|-----------|
| Direct noon sun | 0.80 |
| Morning shade | 1.00 |
| Tree shade | 1.02 |
| Building shade (pure sky) | 1.12 |
| Dawn vertical | 0.86 |

**Natural light range: 0.69 to 1.13**

No natural condition measured exceeded S/M = 1.13. This represents the spectral environment under which human appetite regulation evolved.


## Artificial Light Comparison

Spectral analysis of common LED sources reveals dramatic departures from natural baselines:

| Light Source | CCT | Blue Peak | S/M Ratio | Assessment |
|--------------|-----|-----------|-----------|------------|
| Natural light (max) | varies | varies | 1.13 | Baseline |
| Warm LED (2700K) | 2678K | 457nm | 0.56 | Below natural |
| Warm LED (2751K) | 2751K | 451nm | 0.83 | Within natural |
| **Cold LED A (6258K)** | 6258K | **448nm** | **1.88** | **66% above max** |
| **Cold LED B (6097K)** | 6097K | **455nm** | **0.94** | **Within natural** |
| Cold LED C (6649K) | 6649K | 452nm | 1.20 | 6% above max |
| Computer monitor | ~6500K | 446nm | 2.90 | 157% above max |

**Key finding**: Two cold LEDs with similar CCT (6258K vs 6097K) have dramatically different S/M ratios (1.88 vs 0.94). The difference is blue peak wavelength: 448nm vs 455nm.


## The 7nm Difference

The critical variable is where the blue peak falls relative to S-cone and melanopsin sensitivity:

```
S-cone peak         Melanopsin peak
   ↓                      ↓
  440nm                  480nm
   │                      │
   │   448nm   455nm      │
   │     ↓       ↓        │
   ├─────●───────●────────┤
   │                      │
  420    440    460    480    500
```

**448nm peak**: Falls on the steep part of S-cone sensitivity curve, low melanopsin activation. High S/M ratio.

**455nm peak**: Falls between the two systems. Balanced activation. Normal S/M ratio.

Seven nanometers-0.000007 millimeters-determines whether the spectrum is within natural range or 66% beyond it.


## The Biological Pathway

Why does S/M ratio affect appetite? The pathway involves three stages:

### Stage 1: S-cones → Retinal Dopamine

S-cones provide input to dopaminergic amacrine cells in the retina. Short-wavelength light triggers dopamine release.

Research confirms multiple cone pathways regulate retinal dopamine ([Nature Scientific Reports](https://www.nature.com/articles/srep28916)).

### Stage 2: Melanopsin → Hypothalamic Satiety

Melanopsin-containing ipRGCs project to the lateral hypothalamus-the "feeding center"-and to orexin neurons that regulate appetite.

Research confirms the retinohypothalamic tract projects monosynaptically to orexin-A neurons ([PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC12181770/)).

### Stage 3: The Imbalance

**High S/M ratio (>1.13)**:
- Elevated dopamine: "seek, forage, acquire"
- Suppressed satiety signal: weak "you're satisfied" message
- Result: Hunger without resolution

**Balanced S/M ratio (<1.0)**:
- Normal dopamine: appropriate alertness
- Normal satiety signal: appropriate appetite regulation
- Result: Eating when hungry, stopping when full


## Daytime vs Nighttime Effects

Existing research on artificial light and metabolism focuses on **nighttime exposure**:
- Light at night disrupts melatonin
- Light at night shifts circadian phase
- Light at night impairs sleep quality

The S/M ratio mechanism operates **independently of time of day**:

| Time | Natural S/M | High-S/M LED | Monitor |
|------|-------------|--------------|---------|
| 8am | 0.95 | 1.88 | 2.90 |
| 12pm | 0.80 | 1.88 | 2.90 |
| 4pm | 0.85 | 1.88 | 2.90 |
| 8pm | - | 1.88 | 2.90 |

The hunger signal doesn't require darkness. Eight hours of daytime exposure to high-S/M lighting delivers continuous appetite dysregulation.


## Connection to Obesity Research

A 2019 NIH study of 43,000 women found that sleeping with artificial light increased obesity risk. Notably, the researchers reported that "poor sleep by itself was associated with obesity and weight gain, [but] it did not explain the associations between exposure to artificial light while sleeping and weight" ([NIH](https://www.nih.gov/news-events/nih-research-matters/artificial-light-during-sleep-linked-obesity)).

The S/M ratio may explain this discrepancy. Spectral composition-not just presence of light-could drive metabolic effects through the dopamine/orexin pathway independently of sleep disruption.


## Connection to ADHD Research

Children with more than 2 hours of daily screen time have 7.7× higher odds of meeting ADHD diagnostic criteria ([WebMD](https://www.webmd.com/add-adhd/childhood-adhd/childhood-adhd-screen-time)).

Standard explanations focus on content: fast-paced media, dopamine hits from games, attention fragmentation.

The S/M ratio suggests an additional mechanism: **chronic high-S/M exposure dysregulates dopamine systems directly through spectral composition**, independent of content. Screens with S/M ratios of 2.5-3.0 deliver sustained dopaminergic stimulation that may contribute to attention dysregulation.


## Practical Thresholds

Based on natural light measurements and the biological pathway:

| S/M Ratio | Assessment | Recommendation |
|-----------|------------|----------------|
| < 0.8 | Below natural | Safe, may cause drowsiness |
| 0.8 - 1.13 | Natural range | Safe for extended use |
| 1.13 - 1.5 | Above natural | Limit duration, monitor effects |
| 1.5 - 2.0 | High | Avoid extended exposure |
| > 2.0 | Critical | Minimize exposure |

**The threshold of 1.13 is not arbitrary**-it represents the maximum S/M ratio measured across all natural light conditions.


## Product Comparison: WIZ vs Extrastar

Two tunable smart bulbs with dramatically different S/M profiles:

### Cold Mode (~6000K)

| Metric | WIZ v2 | Extrastar | Difference |
|--------|--------|-----------|------------|
| CCT | 6258K | 6097K | Similar |
| Blue Peak | 448nm | 455nm | +7nm |
| S-cone % | 21.2% | 16.1% | -24% |
| Melanopsin % | 11.3% | 17.1% | +51% |
| S/M Ratio | 1.88 | 0.94 | **2× better** |
| Assessment | HUNGER RISK | Safe | - |

### Warm Mode (~2700K)

| Metric | WIZ v2 | Extrastar | Difference |
|--------|--------|-----------|------------|
| CCT | 2751K | 2678K | Similar |
| Blue Peak | 451nm | 457nm | +6nm |
| S/M Ratio | 0.83 | 0.56 | Both safe |

**The critical difference**: Extrastar maintains S/M < 1.0 across all color temperature settings. WIZ exceeds 1.13 in cold mode.

Same color appearance. Same tunable functionality. Different biological effects.


## Why the Difference Exists

The S/M ratio is determined primarily by blue peak wavelength:

- **448nm peak** (WIZ): Maximum S-cone stimulation, low melanopsin stimulation
- **455nm peak** (Extrastar): Balanced stimulation of both systems

This difference arises from LED chip selection. Most manufacturers use 445-450nm blue chips because they're slightly more efficient. A 455-460nm chip would produce the same color appearance with dramatically better S/M ratios.

The choice is technical, not biological. Manufacturers optimize for electrical efficiency, not appetite regulation.


## How to Assess Your Lighting

Without a spectroradiometer, direct S/M measurement isn't possible. Proxy indicators:

### If Manufacturer Lists Blue Peak Wavelength
- **455-465nm**: Likely good S/M ratio
- **445-452nm**: Likely problematic in cold modes

### Behavioral Indicators
- Increased snacking urges under certain lights
- Reduced hunger when switching to warmer settings
- Different appetite patterns on outdoor vs indoor days

### Product Research
- Check spectral data if available
- Look for "violet pump" LEDs (405nm primary)-these have different issues
- Prioritize brands that publish full spectral data


## Practical Recommendations

### For Immediate Action
1. **Use warm mode** on tunable bulbs when possible
2. **Limit cold LED duration** to 2-3 hours
3. **Don't eat under high-S/M lighting**-move to natural or warm light for meals
4. **Use warm/night mode on monitors** despite the yellow appearance

### For Purchasing Decisions
1. **Request spectral data** from manufacturers
2. **Prioritize 455nm+ blue peaks** if data available
3. **Default to warm CCT (2700-3000K)** when spectral data unavailable
4. **Consider products with documented biological optimization**

### For Workplaces
1. **Audit fixture S/M ratios** if spectral data obtainable
2. **Provide warm alternatives** for eating areas
3. **Design temporal variation** (cool morning, warm afternoon)
4. **Maximize natural light access** during work hours


## The Bottom Line

The S/M ratio-the balance between S-cone and melanopsin stimulation-predicts whether a light source will dysregulate appetite.

**Natural light**: S/M 0.69-1.13 (never exceeds 1.13)
**Good LEDs** (455nm peak): S/M 0.56-0.94 (within natural range)
**Problematic LEDs** (448nm peak): S/M 1.2-1.9 (up to 66% above natural)
**Monitors**: S/M 2.5-3.0 (up to 157% above natural)

Color temperature and melanopic lux don't capture this distinction. Two lights with identical CCT and melanopic EDI can have opposite S/M ratios and opposite effects on appetite.

The metric is new. The mechanism is supported by existing neuroscience. The practical implications are significant for anyone spending extended time under artificial lighting-which is nearly everyone.


*Next: "The Extrastar Exception: How One Bulb Got It Right"*
