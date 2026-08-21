# DD-009: Soundboard Support

**Status:** Approved  
**Date:** 2026-08-21

## The Question

How should the soundboard of the reference cigar box guitar be supported around the bridge?

DD-007 established that the bridge will sit on a controlled, supported region of the soundboard rather than being rigidly coupled directly to the neck-through backbone.

DD-008 established that the body will use a solid-wood resonant soundboard intended to make a meaningful acoustic contribution.

The support system must therefore allow enough soundboard movement for useful acoustic response while preventing excessive deflection, distortion or long-term deformation under bridge loading.

## Related Decisions

This decision builds particularly on:

- [`DD-007-bridge-coupling.md`](DD-007-bridge-coupling.md), which establishes supported soundboard coupling around the bridge;
- [`DD-008-body-architecture.md`](DD-008-body-architecture.md), which establishes the resonant wooden body and comparatively stiff side structure.

The exact soundboard material, thickness and bridge dimensions remain open.

## Goals

The soundboard support should:

- provide adequate support around the bridge;
- allow controlled movement of the soundboard;
- preserve the acoustic role established in DD-007;
- limit excessive bridge-area deflection and long-term deformation;
- remain mechanically simple and understandable;
- avoid unnecessary acoustic-guitar-style bracing complexity;
- work naturally with the comparatively stiff body sides;
- remain mechanically separate from the neck-through backbone where practical;
- allow final brace spacing to respond to the eventual bridge dimensions;
- provide a useful baseline that can be evaluated and refined through the reference build.

## Design Space

### Option 1: Rigid Bridge-Area Support

Provide substantial support directly beneath or immediately around the bridge, minimising movement of the soundboard.

**Advantages**

- strong resistance to bridge-area deformation;
- predictable structural behaviour;
- relatively insensitive to soundboard stiffness;
- simple to make structurally robust.

**Disadvantages**

- restricts soundboard movement;
- weakens the acoustic intent established in DD-007;
- risks making the bridge region behave more like part of the structural backbone than a resonant panel;
- provides less opportunity to learn from the acoustic behaviour of the reference build.

### Option 2: Minimally Braced Soundboard

Allow the soundboard to span a relatively large unsupported area around the bridge.

**Advantages**

- provides substantial freedom for soundboard movement;
- may increase acoustic response;
- keeps internal construction very simple.

**Disadvantages**

- increases the risk of excessive deflection;
- increases the possibility of long-term soundboard deformation;
- makes bridge geometry more dependent on the soundboard alone;
- may require a thicker or stiffer soundboard, reducing some of the intended benefit.

### Option 3: Two Transverse Bridge Braces

Use two transverse braces running side to side across the soundboard, with one positioned ahead of the bridge and one behind it.

The bridge sits on the soundboard between the braces.

The braces define a controlled unsupported span around the bridge while the stiff side walls support their ends.

**Advantages**

- provides direct support on both sides of the bridge region;
- leaves the bridge itself on a free-moving section of soundboard;
- creates a simple and understandable structural arrangement;
- uses the stiff body sides effectively;
- allows the unsupported bridge span to be adjusted deliberately;
- avoids elaborate conventional guitar bracing patterns;
- provides a useful baseline for evaluating soundboard behaviour.

**Disadvantages**

- brace spacing becomes an important acoustic and structural variable;
- braces may suppress soundboard movement if positioned too close to the bridge;
- excessive spacing could permit undesirable deformation;
- final brace dimensions will need to be matched to the soundboard material and thickness.

## Brace Orientation

The reference instrument will use two **transverse braces**.

Each brace will run across the width of the soundboard from one side wall to the other.

One brace will be positioned on the neck side of the bridge and the other on the tail side.

This arrangement creates a defined bridge region between the two supports.

## Relationship to the Neck-Through Backbone

The transverse braces will be supported by the body sides rather than using the neck-through member as their primary support.

Where a brace crosses above the neck-through structure, the brace will remain mechanically separate from it.

A small clearance will be maintained so that the brace does not rigidly couple the soundboard to the backbone at that point.

The exact clearance will be determined during detailed structural design.

This maintains the separation established in earlier decisions:

- the neck-through member provides the principal structural backbone;
- the soundboard and its braces form the local resonant support system around the bridge.

## Bridge Region

The bridge will sit on the soundboard between the two transverse braces.

No solid block or brace will be placed directly beneath the bridge merely to maximise stiffness.

The unsupported bridge region should remain small enough to control deformation while large enough to allow the soundboard to move meaningfully.

The intention is controlled flexibility rather than either maximum rigidity or maximum freedom.

## Brace Spacing

Exact brace spacing will not be fixed until the bridge dimensions are known.

Instead, the design rule will be:

> The transverse braces should sit just outside the bridge footprint, creating the smallest practical unsupported soundboard span that still allows the bridge region to move as a coherent resonant panel.

This prevents an arbitrary brace dimension from constraining the later bridge design.

It also ensures that the structural relationship between the bridge and its supports remains deliberate.

## Brace Dimensions and Material

The exact:

- brace timber;
- brace width;
- brace height;
- brace profile;
- final spacing;

remain open implementation details.

These choices will depend on:

- soundboard species;
- soundboard thickness;
- bridge dimensions;
- body construction;
- the stiffness of the completed components.

The reference build should use the simplest brace construction that provides adequate support.

## Trade-Offs

The central trade-off is between **soundboard freedom and resistance to deformation**.

Braces placed very close to the bridge would provide excellent structural control but could suppress the soundboard movement deliberately sought in DD-007.

Braces placed too far away would allow greater movement but increase the risk of sagging, distortion or unstable bridge geometry.

Two transverse braces provide a simple way to define and control that trade-off.

Their spacing can be adjusted relative to the bridge rather than committing the design to a complex predetermined bracing pattern.

This supports both the acoustic goals of the instrument and the learning goals of the reference build.

## Decision

**Option 3: Two Transverse Bridge Braces**

The reference cigar box guitar will use two transverse soundboard braces around the bridge region.

One brace will sit ahead of the bridge and one behind it.

The braces will:

- span between the stiff body sides;
- support the soundboard locally;
- remain mechanically separate from the neck-through backbone;
- define a controlled resonant span containing the bridge.

The bridge itself will remain on the unsupported soundboard region between the braces.

Exact brace spacing will be determined after the bridge footprint is known, using the bridge dimensions rather than an arbitrary predetermined measurement.

Brace material and dimensions remain later design choices.

## Consequences

This decision means that:

- the body sides must provide suitable support for the ends of both transverse braces;
- the soundboard will have a deliberately defined flexible region around the bridge;
- the neck-through structure will not rigidly support the braces where they cross it;
- the bridge design must be established before final brace spacing can be determined;
- soundboard material and thickness must be considered together with brace dimensions;
- brace dimensions should be kept as simple as practical while providing adequate stiffness;
- bridge-area movement and deformation should be evaluated during the reference build;
- brace spacing and dimensions may be refined if the completed instrument proves too rigid or too flexible;
- more elaborate bracing should only be introduced in future instruments if experience demonstrates a need for it.

## Future Revisit

The soundboard support arrangement should be reviewed after the reference instrument has been completed and played for a meaningful period.

We should then ask:

- Has the soundboard remained stable under bridge loading?
- Has the bridge region developed any undesirable deflection?
- Does the soundboard move enough to provide useful acoustic response?
- Does the instrument feel lively when played?
- Are the transverse braces unnecessarily heavy or stiff?
- Would different brace spacing improve the balance between resonance and stability?
- Did maintaining clearance from the neck-through backbone produce a useful result?
- Would a simpler or different support arrangement improve a future instrument?
- Would we choose two transverse braces again for an instrument with similar goals?

## Sign-Off

**Approved.**

The reference cigar box guitar will use two transverse soundboard braces spanning between the stiff body sides, with the bridge positioned on a controlled resonant span between them and the bracing kept mechanically separate from the neck-through backbone.
