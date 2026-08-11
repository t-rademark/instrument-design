# DD-004: Scale Length

**Status:** Approved  
**Date:** 2026-08-11

## The Question

What nominal scale length should the reference cigar box guitar use?

Scale length is the vibrating length of an open string, measured nominally from the nut to the bridge.

It affects several important characteristics of the instrument, including:

- string tension;
- fret spacing;
- left-hand reach;
- playing feel;
- the string gauges required for the intended tuning envelope.

The reference instrument should feel familiar when moving between it and a conventional acoustic guitar while remaining well suited to its three-string, blues-focused role.

## Goals

The scale length should:

- provide a familiar guitar-like playing feel;
- avoid making the reference instrument feel unnecessarily small or specialised;
- work comfortably with the normal tuning envelope defined in DD-003;
- allow practical string gauges and useful string tension;
- provide conventional fret spacing and left-hand reach;
- support both fretted and slide playing;
- provide a useful reference point for future instruments;
- avoid adding novelty where there is no clear benefit.

## Existing Instrument Reference

The builder's acoustic guitar was measured from the nut to the centre of the 12th fret.

The measured distance was approximately:

**315 mm**

Because the 12th fret divides the vibrating string length approximately in half, this indicates a nominal scale length of approximately:

**630 mm**

Matching this scale closely should make the reference cigar box guitar feel familiar when moving between the two instruments.

## Design Space

### Option 1: Approximately 630 mm

Use a nominal scale length matching the builder's existing acoustic guitar as closely as practical.

**Advantages**

- maximises familiarity;
- provides familiar fret spacing and left-hand reach;
- remains firmly within conventional guitar scale territory;
- removes the need to adapt unnecessarily between instruments;
- should provide suitable string tension for the intended tuning range once appropriate gauges are selected.

**Disadvantages**

- does not deliberately exploit the softer feel that a shorter scale could provide;
- does not provide the slightly greater tension of a longer scale.

### Option 2: 635 mm / 25 inches

Use a nominal 25-inch scale.

This is extremely close to the measured acoustic guitar scale while providing a convenient round design dimension.

**Advantages**

- familiar guitar-like feel;
- only 5 mm longer than the measured reference;
- convenient nominal dimension;
- provides slightly greater string tension than 630 mm.

**Disadvantages**

- offers no significant practical advantage over directly matching the familiar instrument;
- introduces a small difference in fret spacing without a clear requirement for it.

### Option 3: Approximately 648 mm / 25.5 inches

Use a longer conventional guitar scale.

**Advantages**

- provides somewhat greater string tension for a given pitch and string gauge;
- remains within familiar conventional guitar proportions;
- may suit players who prefer a firmer string feel.

**Disadvantages**

- increases fret spacing and left-hand reach;
- moves farther away from the feel of the builder's existing acoustic guitar;
- greater tension is not currently a design requirement;
- adds a difference in playing feel without a demonstrated benefit.

## Trade-Offs

The principal trade-off is between **familiarity of feel** and deliberately altering string tension or instrument proportions.

A shorter scale could provide a softer and more compact instrument.

A longer scale could provide greater string tension and slightly wider fret spacing.

Neither characteristic is currently required by the mission of the reference instrument.

The measured scale of the builder's existing acoustic guitar already lies in an appropriate conventional guitar range and provides a known, comfortable reference.

Matching that scale therefore avoids introducing an unnecessary variable into the first reference build.

## Decision

**Option 1: 630 mm Nominal Scale Length**

The reference cigar box guitar will use a nominal scale length of:

**630 mm**

This closely matches the builder's existing acoustic guitar and should therefore provide familiar fret spacing, reach and general playing feel.

The scale length will be used as the nominal basis for fret-position calculations and subsequent string-tension analysis.

## Bridge Compensation

The nominal scale length does not necessarily mean that the physical string contact point at the bridge will be exactly 630 mm from the nut.

Practical intonation normally requires a small amount of compensation, which may place the effective bridge contact point slightly beyond the nominal scale length.

The amount and implementation of compensation will be determined later as part of the bridge and intonation design.

This does not alter the declared nominal scale length of the instrument.

## Consequences

This decision means that:

- fret positions will be calculated using a 630 mm nominal scale;
- the instrument should feel broadly familiar when moving from the builder's acoustic guitar;
- string gauges will be selected using 630 mm as an input to tension calculations;
- string tension must be evaluated across the tuning envelope defined in DD-003;
- neck dimensions and body placement can now be developed around a known vibrating string length;
- bridge position will ultimately include any intonation compensation required by the completed instrument;
- future instruments may deliberately use shorter or longer scales where their goals justify doing so.

## Future Revisit

The scale length should be reviewed after the reference instrument has been completed and played for a meaningful period.

We should then ask:

- Did the instrument feel familiar when moving between it and the reference acoustic guitar?
- Was the fret spacing comfortable?
- Did the scale work well for both fretted and slide playing?
- Did the selected string gauges provide appropriate tension across the tuning envelope?
- Would a shorter or longer scale have improved the instrument?
- Would we choose 630 mm again for an instrument with similar goals?

## Sign-Off

**Approved.**

The reference cigar box guitar will use a nominal 630 mm scale length, providing a familiar guitar-like playing geometry and a defined basis for fret placement, string selection and subsequent structural design.