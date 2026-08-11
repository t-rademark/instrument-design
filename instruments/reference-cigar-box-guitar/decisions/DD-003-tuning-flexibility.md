# DD-003: Tuning Flexibility

**Status:** Approved  
**Date:** 2026-08-11

## The Question

What range of tunings should the reference cigar box guitar be designed to support?

The reference instrument is intended to be explored and played in different ways.

A single permanent tuning would unnecessarily constrain that experimentation. At the same time, attempting to support an extremely broad tuning range with one set of strings could compromise string tension, feel and playability.

The design therefore needs to establish a useful normal tuning envelope without treating any one tuning as permanent.

## Goals

The tuning approach should:

- support experimentation rather than prescribe a single permanent tuning;
- suit the instrument's blues-focused character;
- support riffs, rhythm, slide and groove;
- allow exploration of both chordal and more harmonically ambiguous or modal sounds;
- retain the chunky, lower-register voice intended for the instrument;
- allow useful changes of tuning using the normal string set;
- avoid requiring restringing or setup changes for ordinary tuning experiments;
- keep string tension and playability within a useful range;
- expose useful lessons about intervals, harmony and the effect of different tunings;
- allow more adventurous tuning experiments later where different strings or setup changes are justified.

## Design Space

### Option 1: Fixed Tuning

Choose one tuning and optimise the instrument specifically around it.

**Advantages**

- allows string gauges and setup to be optimised very precisely;
- provides predictable string tension and feel;
- simplifies some design decisions.

**Disadvantages**

- unnecessarily limits musical experimentation;
- makes a reversible musical choice part of the permanent instrument design;
- reduces opportunities to explore harmony, intervals and different playing styles;
- conflicts with the reference instrument's role as a learning platform.

### Option 2: Defined Normal Tuning Envelope

Design the standard string set around a deliberately chosen range of useful tunings.

Tunings inside that envelope should be accessible by retuning the existing strings without requiring restringing or significant setup changes.

More extreme tunings remain possible, but may require different string gauges or setup adjustments.

**Advantages**

- provides meaningful musical flexibility;
- supports direct comparison between different tunings;
- retains good string tension and playability;
- encourages experimentation without trying to accommodate every conceivable tuning;
- separates normal use from more specialised experiments;
- supports the learning mission of the reference instrument.

**Disadvantages**

- string gauges will involve some compromise rather than being optimised for one tuning;
- the normal envelope must be deliberately constrained;
- some desirable future tunings may fall outside the standard setup.

### Option 3: Maximum Tuning Flexibility

Attempt to choose strings and setup that accommodate the broadest practical range of pitches.

**Advantages**

- greatest theoretical flexibility;
- allows many tunings without restringing.

**Disadvantages**

- some tunings may result in strings that feel excessively loose or tight;
- may compromise playability in the tunings that matter most;
- makes string selection unnecessarily difficult;
- optimises for theoretical capability rather than the intended musical use of the instrument.

## Reference Tunings

Two contrasting tunings will initially be used as reference cases for the normal tuning envelope.

### G2-D3-G3

This tuning provides:

- root, fifth and octave;
- a strong drone character;
- no major or minor third;
- harmonic ambiguity;
- a useful foundation for blues riffs, slide and groove.

### G2-B2-D3

This tuning provides:

- root, major third and fifth;
- a complete G major triad;
- a contrasting chordal character;
- an opportunity to explore how the presence of the third changes the sound and musical possibilities.

These are reference tunings rather than permanent tunings.

Other tunings may be explored wherever they remain within the intended operating range of the strings and instrument.

## Normal Tuning Envelope

The normal tuning envelope will be designed around the following per-string ranges:

- **low string:** G2;
- **middle string:** B2 to D3;
- **high string:** D3 to G3.

This produces an overall reference register from approximately **G2 to G3**.

The standard string set should allow movement within these ranges while maintaining useful tension and playability.

In particular, both reference tunings should be achievable by retuning the standard strings without requiring restringing or significant setup changes.

## Extended Tuning Envelope

Tunings outside the normal envelope are not prohibited.

They are considered experimental configurations and may require:

- different string gauges;
- different string materials;
- setup adjustments;
- reassessment of string tension and structural loading.

The instrument should not be compromised in normal use merely to accommodate these less common possibilities.

## Trade-Offs

The central trade-off is between **tuning flexibility** and **optimising the instrument for a particular tuning**.

A fixed tuning could provide highly consistent string tension and feel, but would restrict one of the most useful areas of musical experimentation.

An extremely broad tuning range would provide greater theoretical flexibility, but could produce poor string tension or playability at its extremes.

A defined normal tuning envelope provides the useful middle ground.

It allows the instrument to explore substantially different musical personalities while keeping the standard setup focused on the sounds and playing styles that matter most to the reference instrument.

## Decision

**Option 2: Defined Normal Tuning Envelope**

The reference cigar box guitar will not have a single permanent tuning.

It will instead be designed to support a normal tuning envelope that allows useful experimentation using the standard string set.

The initial reference tunings will be:

- **G2-D3-G3** for a droning, harmonically open voice;
- **G2-B2-D3** for a chordal major voice.

The normal per-string tuning ranges will be:

- **low string:** G2;
- **middle string:** B2 to D3;
- **high string:** D3 to G3.

The instrument should support these ranges comfortably through retuning alone.

Tunings outside this envelope may be explored using alternative string gauges or setup changes where appropriate.

## Consequences

This decision means that:

- no single tuning is considered part of the permanent identity of the instrument;
- scale length and string gauges must be selected with the normal tuning envelope in mind;
- string tension should be evaluated across the intended pitch range rather than at only one tuning;
- both chordal and harmonically ambiguous tunings will be available for experimentation;
- the standard setup should support the two reference tunings without restringing;
- tuning experiments can become part of the musical learning process;
- future build and playing notes should record useful discoveries about particular tunings;
- more extreme tunings remain available as experiments rather than requirements of the standard configuration.

## Future Revisit

The tuning envelope should be reviewed after the reference instrument has been built and played across a range of tunings.

We should then ask:

- Did the standard string set work comfortably across the intended tuning range?
- Were both reference tunings musically useful?
- Did the lower register provide the chunky, blues-focused voice we wanted?
- Did switching between chordal and ambiguous tunings provide useful musical variety?
- Were there other tunings we repeatedly wanted that fell outside the normal envelope?
- Was the tuning range too broad, too narrow or appropriately balanced?
- Should future instruments retain the same tuning envelope?

## Sign-Off

**Approved.**

The reference cigar box guitar will be designed around a flexible normal tuning envelope rather than a single fixed tuning, allowing its musical character to evolve through experimentation.