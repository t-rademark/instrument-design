# DD-007: Bridge Coupling

**Status:** Approved  
**Date:** 2026-08-13

## The Question

How should the bridge couple the vibrating strings to the body of the reference cigar box guitar?

The neck-through structure established in DD-006 provides the principal structural backbone of the instrument.

The bridge has a different role. In addition to defining one end of the vibrating string length, it provides an important path through which string vibration can excite the body.

The reference instrument is intended primarily for amplified use, but the body should still make a noticeable and musically useful acoustic contribution.

The design therefore needs to balance structural stability with sufficient soundboard movement to give the instrument physical and acoustic character.

## Related Decisions

This decision builds on:

- [`DD-005-string-set-and-tension.md`](DD-005-string-set-and-tension.md), which defines the reference strings and normal tension range;
- [`DD-006-neck-architecture.md`](DD-006-neck-architecture.md), which establishes the continuous neck-through structural backbone.

DD-006 deliberately left the detailed relationship between the bridge, soundboard and neck-through member open for this decision.

## Goals

The bridge coupling should:

- preserve stable playing geometry;
- transfer string vibration effectively into the body;
- allow the box to make a noticeable acoustic contribution;
- provide useful unplugged sound even though amplification is the primary mode of use;
- allow some controlled movement of the soundboard;
- prevent excessive long-term deformation around the bridge;
- avoid making the resonant box merely decorative;
- avoid requiring the soundboard to provide the principal longitudinal structural path for string tension;
- remain compatible with the neck-through architecture;
- provide a useful balance between structural control and acoustic character.

## Design Space

### Option 1: Bridge Coupled Directly to the Neck-Through Structure

Support the bridge very rigidly from the neck-through member so that the soundboard contributes relatively little movement at the bridge.

**Advantages**

- provides strong geometric control;
- minimises soundboard deformation around the bridge;
- creates a very direct and predictable structural arrangement;
- reduces dependence on the strength and stiffness of the soundboard.

**Disadvantages**

- reduces the opportunity for the soundboard to respond to string vibration;
- may reduce the audible and physical contribution of the box;
- risks making the body function primarily as an enclosure rather than an active part of the instrument;
- provides less opportunity to explore acoustic behaviour during the reference build.

### Option 2: Bridge Supported Primarily by a Freely Moving Soundboard

Place the bridge on a relatively unsupported region of the soundboard and allow the soundboard substantial freedom to move.

**Advantages**

- encourages strong soundboard participation;
- may increase unplugged acoustic response;
- allows the body resonances to contribute strongly to the character of the instrument.

**Disadvantages**

- places greater structural demand on the soundboard;
- increases the risk of excessive local deformation;
- may make bridge geometry less stable over time;
- requires more careful soundboard and bracing design;
- prioritises acoustic output beyond what is required for an amplified-first instrument.

### Option 3: Supported Soundboard Coupling

Place the bridge on the soundboard so that string vibration is transferred directly into the resonant body, while providing structural support nearby rather than rigidly clamping the bridge area to the neck-through member.

The soundboard is allowed controlled movement around the bridge while the surrounding structure limits excessive deformation.

**Advantages**

- gives the body a genuine role in the instrument's sound;
- allows useful acoustic and physical response;
- retains nearby structural support;
- separates the roles of structural stability and acoustic response;
- works naturally with the neck-through architecture;
- provides useful opportunities to learn from the acoustic behaviour of the reference instrument.

**Disadvantages**

- requires more careful design than rigidly supporting the bridge;
- soundboard stiffness and support placement become important variables;
- some acoustic energy will be shared with the body rather than remaining entirely in the vibrating strings;
- the correct degree of soundboard freedom will need to be evaluated in the completed instrument.

## Structural Relationship

The bridge will sit on the soundboard rather than directly on the neck-through member.

The neck-through structure will remain nearby and will continue to provide the principal structural backbone of the instrument.

The soundboard in the bridge region will not be rigidly clamped to that backbone.

Instead, the bridge area will form a small, controlled supported span that permits useful soundboard movement while nearby internal structure limits excessive deflection and long-term deformation.

The exact dimensions, clearances and support arrangement remain later design details.

## Acoustic Priority

The reference cigar box guitar is primarily an amplified instrument, but unplugged acoustic behaviour remains desirable.

The aim is not maximum acoustic volume.

The aim is for the player to be able to hear and feel that the box participates in the instrument's voice.

The body should therefore contribute:

- resonance;
- acoustic colour;
- physical feedback;
- useful unplugged sound;

without compromising stable playing geometry.

## Trade-Offs

The central trade-off is between **soundboard freedom and structural control**.

Rigidly supporting the bridge from the neck-through member would maximise structural control but reduce the role of the resonant body.

Allowing the bridge region to move too freely could increase acoustic response but risk deformation and unstable geometry.

The supported-soundboard approach deliberately occupies the middle ground.

The backbone protects the instrument's structural integrity, while the soundboard is given enough freedom to contribute meaningfully to the sound.

For the reference instrument, a small theoretical sacrifice in string-dominated sustain is acceptable if the result is a more lively, characterful and physically engaging instrument.

Structural stability remains the higher priority if the two objectives come into genuine conflict.

## Decision

**Option 3: Supported Soundboard Coupling**

The bridge of the reference cigar box guitar will sit on the soundboard.

The soundboard around the bridge will be allowed controlled movement so that string vibration can excite the body and give the instrument a noticeable acoustic character.

The neck-through structure will provide nearby structural support but will not rigidly clamp the bridge directly to the backbone.

The design will prioritise stable playing geometry while deliberately allowing the resonant box to participate in the instrument's voice.

## Consequences

This decision means that:

- the bridge will load and excite the soundboard locally;
- the soundboard must be strong and stiff enough to remain stable under normal bridge loading;
- the bridge area will require nearby structural support;
- the neck-through member will not directly immobilise the soundboard beneath the bridge;
- the exact supported span and internal support arrangement remain open design questions;
- body and soundboard material choices will influence the acoustic result;
- bridge design must consider both vibration transfer and intonation;
- the instrument should produce useful unplugged sound despite being designed primarily for amplified playing;
- acoustic response and bridge-area deformation should both be evaluated during and after the reference build;
- future instruments may choose a different balance between acoustic freedom and structural rigidity.

## Future Revisit

The bridge coupling should be reviewed after the reference instrument has been completed and played both amplified and unplugged.

We should then ask:

- Does the body make a clearly noticeable contribution to the sound?
- Does the instrument feel lively in the player's hands?
- Is the unplugged sound useful and enjoyable?
- Has the soundboard remained stable around the bridge?
- Has the bridge position or action changed under string load?
- Is the bridge region too rigid or too flexible?
- Did allowing controlled soundboard movement produce a worthwhile result?
- Would more or less structural coupling improve a future instrument?
- Would we choose this architecture again for a similar amplified-first cigar box guitar?

## Sign-Off

**Approved.**

The reference cigar box guitar will use a bridge mounted on a controlled, supported region of the soundboard, allowing the resonant body to contribute meaningful acoustic character while the neck-through structure preserves the instrument's overall structural stability.
