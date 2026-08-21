# DD-010: Bridge Design

**Status:** Approved  
**Date:** 2026-08-21

## The Question

What bridge architecture should the reference cigar box guitar use?

The bridge must perform several jobs simultaneously:

- define the vibrating end of each string;
- establish string spacing and action;
- allow accurate intonation;
- transmit string vibration into the soundboard;
- remain stable under string load;
- work with the resonant soundboard architecture established in earlier decisions.

The reference instrument should favour simplicity, acoustic coupling, adjustability during development and opportunities to learn from the completed build.

## Related Decisions

This decision builds particularly on:

- [`DD-004-scale-length.md`](DD-004-scale-length.md), which establishes the 630 mm nominal scale length;
- [`DD-005-string-set-and-tension.md`](DD-005-string-set-and-tension.md), which establishes the reference string set and expected tension range;
- [`DD-007-bridge-coupling.md`](DD-007-bridge-coupling.md), which establishes that the bridge should excite the soundboard rather than couple rigidly to the neck-through backbone;
- [`DD-009-soundboard-support.md`](DD-009-soundboard-support.md), which establishes a controlled resonant soundboard region supported by transverse braces ahead of and behind the bridge.

## Goals

The bridge should:

- remain mechanically simple;
- couple string vibration effectively into the soundboard;
- avoid unnecessary hardware and mass;
- allow the reference instrument to be adjusted experimentally;
- support accurate setup and intonation;
- provide comfortable string spacing;
- remain stable during normal playing;
- be straightforward to manufacture and modify;
- allow replacement or refinement without altering the soundboard;
- use durable materials suited to their specific roles;
- provide a useful baseline for future bridge experimentation.

## Design Space

### Option 1: Adjustable Metal Bridge

Use an electric-guitar-style metal bridge with mechanical height and intonation adjustment.

**Advantages**

- easy action adjustment;
- easy individual-string intonation adjustment;
- highly repeatable setup;
- commercially available components.

**Disadvantages**

- introduces unnecessary mechanical complexity;
- increases bridge mass;
- reduces the handmade character of the instrument;
- provides less direct experience with traditional bridge geometry and setup;
- may reduce the simplicity of the acoustic coupling between strings and soundboard.

### Option 2: Fixed Wooden Bridge

Use a wooden bridge permanently attached to the soundboard, with a separate saddle.

**Advantages**

- simple construction;
- strong positional stability;
- good acoustic coupling;
- traditional instrument-building approach;
- visually compatible with a handmade wooden instrument.

**Disadvantages**

- bridge position becomes difficult to change after attachment;
- experimental intonation adjustment becomes less convenient;
- bridge replacement or redesign risks affecting the soundboard;
- requires greater confidence in bridge position before final assembly.

### Option 3: Floating Wooden Bridge

Use a wooden bridge that rests on the soundboard and is held in position by string downforce rather than adhesive or mechanical fasteners.

A separate removable saddle provides the string contact surface.

**Advantages**

- very simple construction;
- bridge position can be adjusted during setup;
- bridge angle can be adjusted to improve intonation;
- bridge height can be refined away from the instrument;
- bridge designs can be replaced and compared easily;
- no permanent bridge attachment is required;
- suits the experimental role of the reference instrument;
- preserves direct acoustic coupling to the soundboard.

**Disadvantages**

- the bridge can move when string tension is removed;
- insufficient downforce or poor geometry could allow movement during use;
- bridge location must be checked after restringing;
- final stability can only be evaluated on the completed instrument.

## Floating Architecture

The reference instrument will initially use a **fully floating bridge**.

The bridge will not be:

- glued to the soundboard;
- pinned to the soundboard;
- screwed to the soundboard.

String downforce will hold it in position during normal use.

Starting with a fully floating arrangement preserves maximum reversibility during the reference build.

If real-world use demonstrates that the bridge moves too easily, positional control may subsequently be added.

Possible future modifications include:

1. small locating pins or dowels;
2. light permanent fixation;
3. full adhesive attachment.

The initial floating design should therefore avoid construction choices that would make later fixation unnecessarily difficult.

## Bridge Body

The bridge body will be made from a **single piece of wood**.

Its underside will be relieved through the central region, leaving **two substantial feet**, one toward each end of the bridge.

This provides:

- stable support;
- concentrated contact with the soundboard;
- reduced unnecessary contact area beneath the centre of the bridge;
- simple one-piece construction.

The feet should be substantial enough to resist rocking or twisting rather than being reduced to narrow legs.

## Preliminary Dimensions

The starting bridge dimensions will be approximately:

- **overall width: 50 mm**
- **front-to-back depth: 12 mm**

These are development dimensions rather than manufacturing tolerances.

The 50 mm width provides adequate structure beyond the outer strings while keeping the bridge compact.

The 12 mm depth provides a useful stance for a floating bridge without unnecessarily increasing contact with the soundboard.

Final height remains dependent on the completed neck, soundboard and required action.

## String Spacing

The three strings will use approximately:

**12 mm centre-to-centre spacing at the bridge**

This gives an overall distance of approximately:

**24 mm between the two outer strings**

The spacing is intended to provide comfortable room for:

- fingerstyle playing;
- slide;
- rhythmic muting;
- blues-oriented playing techniques;

without making the playing geometry unnecessarily wide.

## Saddle

The wooden bridge will use a **separate bone saddle**.

The saddle is the narrow component over which the strings pass and defines their precise vibrating endpoints.

The preferred material is:

**responsibly sourced bovine bone**

Bone is chosen because it is:

- hard;
- durable;
- dimensionally stable;
- readily shaped accurately;
- suitable for a precise string contact surface.

Where practical, the material should be sourced from a reputable supplier and identified as a by-product material rather than material obtained specifically for instrument manufacture.

## Saddle Mounting

The saddle will fit into a **snug slot in the wooden bridge**.

It will initially remain:

- removable;
- unglued.

String pressure will retain the saddle during normal use.

This allows the saddle to be:

- removed;
- reshaped;
- replaced;
- experimentally modified;

without replacing the bridge body.

Exact saddle thickness, height and slot dimensions remain later implementation details.

## Intonation Strategy

The initial saddle will be substantially **straight rather than individually compensated for each string**.

Initial intonation will be established by:

1. positioning the floating bridge at the appropriate distance from the nut;
2. adjusting the overall angle of the bridge as required;
3. testing fretted intonation;
4. refining individual saddle contact points only if testing demonstrates that additional compensation is necessary.

This allows the completed instrument to determine how much compensation it actually requires.

The nominal scale length remains 630 mm as established in DD-004.

The physical string contact points may sit slightly beyond the nominal scale length as required for correct intonation.

## Height Adjustment

The bridge will not use mechanical height adjusters.

Instead, it will be built initially with sufficient height to allow setup by material removal.

Final action will be established by shaping:

- the wooden bridge;
- the removable saddle;
- or both.

This provides precise adjustment without adding hardware.

Because the bridge and saddle are removable, either component can be replaced if too much material is removed during setup.

## Bridge Timber

The exact bridge timber species will not yet be specified.

Instead, the material should be selected against functional requirements.

The bridge timber should be:

- hard enough to resist crushing around the saddle;
- dimensionally stable;
- sufficiently strong across the relieved underside and feet;
- reasonably light;
- capable of being shaped accurately;
- suitable for a durable instrument component.

The final species will be chosen after suitable available timber is considered.

Material suitability takes priority over naming a traditional bridge species in advance.

## Trade-Offs

The central trade-off is between **adjustability and positional certainty**.

A permanently fixed bridge provides excellent positional stability but commits the instrument to a bridge location before the behaviour of the completed reference build is known.

A floating bridge allows:

- bridge position to move;
- bridge angle to change;
- bridge height to be refined;
- different bridges to be tested;

without altering the instrument itself.

That flexibility is particularly valuable on a reference instrument whose purpose includes learning through construction and use.

The cost is that the bridge may prove more mobile than desired.

Because conversion from floating to located or fixed is straightforward, the reversible choice carries relatively little long-term risk.

## Decision

**Option 3: Floating Wooden Bridge**

The reference cigar box guitar will initially use a fully floating wooden bridge.

The bridge will:

- be made from one piece of wood;
- have a relieved centre underneath;
- stand on two substantial feet;
- be approximately 50 mm wide;
- be approximately 12 mm deep;
- use 12 mm centre-to-centre string spacing;
- use a removable, unglued, responsibly sourced bovine-bone saddle;
- use a substantially straight saddle initially;
- use bridge position and angle as the primary means of establishing intonation;
- have no mechanical height-adjustment hardware;
- be shaped during setup to achieve the required action.

The exact bridge timber species will be selected later according to functional requirements and available suitable material.

## Consequences

This decision means that:

- the strings must be anchored independently of the floating bridge;
- the exact tail anchoring arrangement remains a later design decision;
- the bridge can be positioned experimentally during initial setup;
- the final bridge position does not need to be permanently established during body construction;
- bridge angle can be used to establish overall intonation compensation;
- individual saddle compensation can be introduced later if required;
- the bridge and saddle can be replaced without modifying the soundboard;
- the 50 mm bridge width now provides useful information for determining the final spacing of the DD-009 transverse soundboard braces;
- bridge height must be determined from the actual geometry of the completed neck, soundboard and required action;
- adequate string downforce must be provided to keep the floating bridge stable;
- bridge movement must be evaluated during actual playing;
- locator pins or permanent attachment remain available if testing demonstrates a need.

## Future Revisit

The bridge design should be reviewed after the reference instrument has been completed, set up and played for a meaningful period.

We should then ask:

- Does the floating bridge remain stable during normal playing?
- Does it return reliably to position after string changes?
- Is the two-foot arrangement stable against rocking or twisting?
- Does the bridge transfer enough vibration into the soundboard?
- Does the instrument respond acoustically as intended?
- Is 12 mm string spacing comfortable?
- Is the 50 × 12 mm bridge body appropriately sized?
- Was a straight saddle sufficient?
- Was bridge position and angle enough to achieve satisfactory intonation?
- Did individual saddle compensation become necessary?
- Was fixed-height setup easy to perform accurately?
- Was the chosen bridge timber appropriate?
- Would locator pins improve the design without unnecessary cost?
- Would we choose a fully floating bridge again for an instrument with similar goals?

## Sign-Off

**Approved.**

The reference cigar box guitar will initially use a simple, fully floating one-piece wooden bridge with two substantial feet, a removable responsibly sourced bone saddle and setup performed through bridge positioning, bridge angle and component shaping rather than mechanical adjustment.