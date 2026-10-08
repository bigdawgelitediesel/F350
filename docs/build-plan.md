# Build Plan

## Truck

| Item | Spec |
|---|---|
| Year / model | 2011 Ford F350 |
| Engine | 6.7 Power Stroke (first year Scorpion) |
| Drivetrain | 4x4, 6R140 trans |
| Rear axle | Sterling 10.5, SRW, 35 spline |
| Front axle | Dana Super 60 |
| Tires | 37 inch |
| Current lift | Old 6 inch, Bilstein shocks (too stiff) |

## Goal

Cadillac ride empty, easy towing, capable but not extreme off road for hunting.

## Decisions

### Rear axle: replace bent housing, regear to 4.30

- Current rear housing is bent. Replace with a straight used Sterling 10.5 from a 2011 to 2016 F250/F350 SRW. Any ratio is fine, it gets regeared.
- Confirm donor is a 10.5 not a 10.25. Check tubes with a string line. Pull cover and check for metal.
- Confirm donor has ABS tone ring, parking brake hardware, backing plates, and matches E-locker vs open.
- Carrier break: 3.73 and down uses the low carrier, 4.10 and up uses the high carrier. A 4.10+ donor saves buying a carrier for 4.30.
- Parts: 4.30 ring and pinion, master install kit, carrier if needed, axle seals, wheel bearings, cover gasket, 75W-140 (about 3.5 qt).

### Front axle: regear to 4.30 to match

- Required on 4x4. Front and rear must match or the transfer case binds.
- Parts: 4.30 ring and pinion for Dana Super 60, master install kit, 75W-140 (about 3 qt).
- Inspect while apart: unit bearings, tie rod ends, drag link, track bar bushings.

### Why 4.30

37s on stock gearing is like running a half-ton ratio. 4.30 puts a 37 back to a stock 3.73 feel. 4.56 tows better but buzzes on the highway. 4.30 is the pick.

### Suspension: drop from 6 inch to 4.5 inch Carli

**DECIDED: Carli Option 1, Full Progressive Leaf Springs, 4.5 inch.**

- Complete replacement rear leaf pack, no lift block. Progressive rate, soft empty, carries a trailer loaded.
- Built by Deaver for Carli. Roughly $1,500 to $2,000 per pair.
- Rejected: Carli Progressive Add-A-Pack (option 2). Cheaper but keeps a block and is not the full fix.
- Spring rate: **Standard** (not Heavy Duty or Extreme Heavy Duty). Truck runs mostly empty, Cadillac ride is the goal, air bags carry the trailer. Switch to Heavy Duty only if a gooseneck or fifth wheel with 3,000+ lb pin weight gets towed often, or a permanent heavy bed load goes in.

### Carli order, priced 2026-10-08

| Part | Pick | Why |
|---|---|---|
| Backcountry 2.0 System, 4.5 inch, 11-16 F250/F350 4x4 | Yes | Front coils, Carli SPEC 2.0 shocks, brake lines, adjustable track bar, caster adjusters. 2.0 shocks are right for hunting speed off road and towing. Pintop 2.5 reservoir not needed. |
| Full Progressive Leaf Springs, Standard | Yes | Rear. Replaces block. |
| Leaf Spring Shackles 05-26 4x4 | Yes | Carli geometry is designed around their longer shackle. New bushings. |
| Long Travel Airbags 08-16 SRW | Yes | Sized to the leaf travel. Replaces the Ride-Rite idea. 5 to 10 psi empty, pump up to tow. |
| Fabricated Adjustable Radius Arms 05-22 | Yes | Sets caster and centers axle for 37s. Fixes highway wander. Replaces the radius arm drop brackets in the Backcountry kit. Order the system configured with arms instead of brackets. |
| Sway Bar Drop Brackets 11-16 4x4 | Yes | Fixes end link angle at 4.5 inch. |
| Carrier Bearing Drop 05-26 | Yes | Two piece rear driveshaft, prevents vibration after lift. |
| High Mount Steering Stabilizer 05-26 | Yes | Tucked up for brush and rocks. |
| Low Mount Steering Stabilizer | No | One or the other. High mount chosen. |

**Quoted total: $7,390** for everything above.

Not in that total, budget separately:
- Install labor and alignment.
- Air compressor or onboard air for the bags, or a manual fill schrader setup.
- U-bolts if not included with the leaf springs (confirm with Carli).
- Wheels if current offset does not clear 37s at 4.5 inch.
- Front end wear parts found during the regear (unit bearings, tie rod ends, drag link, track bar bushings).

Before ordering, call Carli or a dealer (Thuren, Fogelsanger) to confirm current part numbers for a 2011 F350 SRW 4x4 on 37s that tows, that rear height matches the front springs, and that the Backcountry comes configured for the adjustable arms.

### 37s on 4.5 inch

- Fits with correct wheel offset, roughly negative 12 to negative 18 on a 20x9 or 20x10.
- Expect minor trimming on front valance and inner fender liner. Check rear fender on compression.

## Order of operations

1. Buy straight Sterling 10.5 donor, regear rear to 4.30.
2. Regear front Dana 60 to 4.30, inspect and replace worn front end parts.
3. While rear axle is out, install Carli Backcountry 2.0 with adjustable radius arms, Standard Full Progressive Leaf Springs, and shackles.
4. Carli SPEC 2.0 shocks (in the Backcountry kit), long travel air bags, high mount stabilizer, carrier bearing drop, sway bar drop brackets.
5. Reprogram PCM for 37 inch tires and 4.30 ratio.
6. Alignment.

## Open items

- Read door sticker axle code to confirm current ratio.
- Confirm whether truck has E-locker.
- Tire load rating on the 37s (need E or at minimum D for towing).
- Trailer weight, to size brake controller and weight distribution.
- CP4 pump: bypass kit or CP3 conversion is mandatory before any tune.
