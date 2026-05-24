# Flight Tools

Interactive weight & balance and performance calculators for light aircraft, hosted via GitHub Pages.

---

## Piper PA-28-181 Cherokee Archer II

**[Open Calculator](./archer_ii_wb_performance.html)**

A fully interactive W&B and takeoff performance calculator built directly from the PA-28-181 Cherokee Archer II Pilot's Operating Handbook (Report VB-790, issued June 1976).

### What it covers

**Weight & Balance — Section 6**
- Direct moment calculation (Weight × Arm = in-lb), per POH Fig 6-9
- Arms: front seats 80.5 in, rear seats 118.1 in, fuel 95.0 in, baggage 142.8 in
- Live CG envelope plot (Fig 6-15) with normal and utility category boundaries
- Forward CG limit interpolated along the diagonal limit line (82.0 in @ 1950 lb → 86.5 in @ 2550 lb)

**Takeoff Performance — Section 5**
- 0° flaps (Figs 5-5, 5-9) and 25° flaps (Figs 5-7, 5-11) selectable
- Correct takeoff speed table for each flap setting
- Distance charts vs weight, pressure altitude, OAT, and wind component
- Wind correction applied per POH method (−10% per 9 kts headwind)

**Climb Performance — Fig 5-13**
- Full throttle, flaps up, 76 KIAS at 2550 lb gross
- Rate of climb and gradient vs pressure altitude and OAT
- Service ceiling 13,650 ft

**Landing Performance — Figs 5-33, 5-35**
- 40° flaps, 66 KIAS approach, full stall touchdown, maximum braking
- Ground roll and 50 ft obstacle distance

**Go / No-Go Summary**
- Automatic pass/fail/marginal for weight, CG, takeoff distance vs runway, and climb gradient
- Adjustable real-world safety factor (default 1.21×)

### Accuracy

All performance data is digitised from the POH charts and verified against the POH's own worked examples:

| Check | Calculated | POH target |
|---|---|---|
| 0° flaps ground roll | 1101 ft | 1100 ft |
| 0° flaps 50 ft obstacle | 1897 ft | 1900 ft |
| 25° flaps ground roll | 949 ft | 950 ft |
| 25° flaps 50 ft obstacle | 1789 ft | 1860 ft |
| Landing ground roll | 774 ft | 825 ft |
| Landing 50 ft obstacle | 1248 ft | 1290 ft |

### Disclaimer

> This tool is for **general information and planning purposes only**. It must not be used as a substitute for the aircraft's current approved Pilot's Operating Handbook. Performance figures are interpolated estimates — always read the actual POH charts. Applicability is limited to serial numbers 28-7790001 through 28-7990589.

---

*Data source: Piper Aircraft Corporation POH Report VB-790, PA-28-181 Cherokee Archer II, issued June 18, 1976.*
