# DD-006: Neck Architecture

**Status:** Approved  
**Date:** 2026-08-13

## The Question

How should the neck of the reference cigar box guitar relate structurally to the body and string anchor?

The neck must preserve the playing geometry established by the nut, frets, strings and bridge while carrying the loads imposed by the strings.

For the reference instrument, the architecture should also make the underlying structural principles easy to understand and provide a robust foundation for later decisions about the body, bridge and neck dimensions.

## Related Principle

This decision applies the shared neck design principles described in:

[`principles/neck.md`](../../../principles/neck.md)

In particular, the neck architecture must provide a stable reference structure that preserves the playing geometry of the instrument under string load, environmental change and time.

## Goals

The neck architecture should:

- provide a stable structural backbone for the instrument;
- support the string loads defined by the reference string set and tuning envelope;
- preserve the playing geometry of the instrument;
- minimise dependence on a complex neck-to-body joint;
- make the structural behaviour of the instrument understandable;
- provide a strong foundation for the string anchor;
- suit the traditional character of a cigar box guitar;
- allow the body to contribute resonance and character without requiring it to carry the primary longitudinal string load;
- prioritise structural stability over maximum acoustic projection;
- remain compatible with the instrument's primarily amplified role.

## Amplified Versus Acoustic Priority

The reference cigar box guitar is intended primarily to be played through an amplifier using a magnetic pickup.

The body should still contribute useful acoustic character, resonance and physical feedback, but maximum unplugged volume is not a primary design objective.

This allows structural stability and predictable geometry to take priority where they conflict with allowing the soundboard to vibrate as freely as possible.

## Design Space

### Option 1: Neck-Through Structure

Continue the neck structure through the body to the tail end of the instrument.

The string anchor is attached to, or structurally supported by, this continuous member.

**Advantages**

- creates a continuous structural backbone;
- avoids relying on a separate neck-to-body joint for the main string load;
- provides a robust location for the string anchor;
- makes the instrument's structural behaviour comparatively easy to understand;
- supports stable playing geometry;
- suits traditional cigar box guitar construction;
- provides a useful reference architecture for learning and future development.

**Disadvantages**

- the through-body member occupies space within the resonant box;
- its interaction with the body may reduce some freedom of acoustic vibration;
- body and bridge design must accommodate the structural member;
- changes to the neck structure may affect a large part of the instrument.

### Option 2: Attached Neck

Terminate the neck at the body and connect it using a separate neck-to-body joint.

The body structure would then participate more directly in transferring the string load toward the tail-end string anchor.

**Advantages**

- allows the neck and body to be treated as more independent components;
- can leave more of the body cavity unobstructed;
- may allow greater freedom in acoustic body design;
- provides experience with conventional neck-joint design.

**Disadvantages**

- introduces a critical structural joint;
- places greater demands on the body structure;
- creates additional opportunities for movement and loss of alignment;
- adds construction complexity without a clear benefit for the reference instrument;
- makes the structural load path less direct and less visually understandable.

## String Anchor

The neck-through member will continue to the tail end of the body and provide the structural foundation for the string anchor.

The three strings will therefore be anchored to a structure that is continuous with the neck rather than relying primarily on the resonant box to resist their longitudinal load.

The exact string-anchor hardware and attachment method will be determined separately.

## Body Relationship

The body will surround and interact with the neck-through structure, but it will not be relied upon as the primary structural backbone of the instrument.

This separation allows the body to be designed for:

- resonance;
- acoustic character;
- appearance;
- ergonomics;
- pickup and control installation;

while the neck-through member provides the principal structural reference.

The detailed relationship between the bridge, soundboard and neck-through member remains a separate design question.

## Trade-Offs

The principal trade-off is between **structural continuity and acoustic freedom**.

A neck-through structure occupies space within the body and may constrain some approaches to maximising soundboard vibration.

An attached neck could leave the resonant body more independent, but would introduce a structural joint and require the body to participate more directly in carrying string load.

Because the reference instrument is primarily intended for amplified use, maximum acoustic projection does not justify adding structural complexity or compromising stability.

The neck-through approach therefore better serves the mission of the reference instrument.

## Decision

**Option 1: Neck-Through Structure**

The reference cigar box guitar will use a neck-through architecture.

The neck structure will continue through the body to the tail end of the instrument and will provide the structural foundation for the string anchor.

The body will contribute resonance, acoustic character and physical form, but will not be relied upon as the primary structural path for the longitudinal string load.

Structural stability and preservation of playing geometry take priority over maximising acoustic soundboard freedom.

## Consequences

This decision means that:

- the neck and through-body member form one continuous structural backbone;
- the body must be designed around the through-body structure;
- the tail-end string anchor will be structurally supported by that backbone;
- a conventional neck-to-body joint is not required;
- the neck structure must safely accommodate the maximum normal string load established in DD-005;
- body resonance remains desirable but is secondary to structural stability;
- bridge design must later determine how string vibration is coupled into the body;
- the dimensions, material and reinforcement of the neck-through member remain open design questions;
- the exact string-anchor implementation remains open;
- future instruments may use different neck architectures where their goals justify doing so.

## Future Revisit

The neck-through architecture should be reviewed after the reference instrument has been built and played for a meaningful period.

We should then ask:

- Did the structure maintain stable playing geometry?
- Did extending the neck through the body simplify construction?
- Did the string anchor feel structurally secure?
- Did the body still contribute useful resonance and character?
- Did the through-body member unnecessarily restrict the acoustic behaviour of the instrument?
- Did the architecture make setup and adjustment easier or harder?
- Would an attached neck provide a meaningful advantage on a future instrument?
- Would we choose the same architecture again for a similar cigar box guitar?

## Sign-Off

**Approved.**

The reference cigar box guitar will use a continuous neck-through structure extending to the tail end and supporting the string anchor, providing a stable structural backbone around which the resonant body can be developed.
