# DD-011: String Anchor

**Status:** Approved  
**Date:** 2026-08-22

## The Question

How should the strings be anchored at the tail of the reference cigar box guitar?

DD-010 established a fully floating bridge. The bridge therefore does not anchor the strings and must instead be held against the soundboard by string downforce.

The string anchor must:

- carry the full longitudinal string load;
- transfer that load into the neck-through structural backbone;
- create sufficient break angle over the saddle to keep the floating bridge stable;
- maintain straight string paths behind the bridge;
- protect both the strings and timber from local wear;
- remain mechanically simple and visually compatible with the cigar box guitar character.

## Related Decisions

This decision builds particularly on:

- [`DD-005-string-set-and-tension.md`](DD-005-string-set-and-tension.md), which establishes the reference string set and expected tension range;
- [`DD-006-neck-architecture.md`](DD-006-neck-architecture.md), which establishes that the neck-through member continues to the tail and provides the structural foundation for the string anchor;
- [`DD-010-bridge-design.md`](DD-010-bridge-design.md), which establishes a fully floating bridge with 12 mm centre-to-centre string spacing.

## Goals

The string anchor should:

- transfer string tension directly into the neck-through backbone;
- avoid requiring the resonant body panels to carry the primary string tension;
- remain simple to construct and understand;
- require minimal additional hardware;
- permit straightforward restringing;
- provide durable bearing surfaces for the string ball ends;
- prevent strings from cutting into the timber where they emerge;
- create adequate downward force on the floating bridge;
- avoid excessive downward loading of the soundboard;
- maintain straight string paths from the saddle to the tail;
- allow exact geometry to respond to the completed bridge and soundboard rather than being fixed prematurely.

## Design Space

### Option 1: Separate Tailpiece

Attach a dedicated tailpiece to the neck-through backbone and anchor the strings to it.

**Advantages**

- conventional and well understood;
- easily replaceable;
- can provide considerable control over string geometry;
- allows specialised hardware to carry local string loads.

**Disadvantages**

- introduces another component;
- adds hardware and visual complexity;
- provides little benefit if the backbone itself can perform the anchoring role;
- moves away from the mechanically direct construction desired for the reference instrument.

### Option 2: Direct String-Through Anchor

Pass each string through a protected channel in the tail region of the neck-through backbone and retain its ball end against the tail face.

**Advantages**

- extremely direct structural load path;
- minimal hardware;
- simple visual appearance;
- uses the neck-through backbone for the role already established in DD-006;
- allows anchor geometry to be designed around the floating bridge;
- avoids placing primary string tension into the resonant body panels.

**Disadvantages**

- requires accurately drilled string paths;
- string exit geometry must be coordinated with bridge height;
- bearing surfaces must be protected to prevent wear;
- changing the anchor geometry later would be more difficult than replacing a separate tailpiece.

## Direct String Anchoring

The reference instrument will use **three direct string-through anchors** in the tail region of the neck-through backbone.

Each string will:

1. be retained by its ball end at the tail face;
2. pass through the backbone;
3. emerge through the upper surface behind the bridge;
4. continue forward to the saddle.

The exact drilling angle and hole positions will be determined from the completed instrument geometry.

## Ferrules

Each string path will use metal ferrules at both ends.

### Tail Ferrules

A ferrule at the tail face will provide a hard bearing surface for the string ball end.

This prevents the ball end from gradually crushing or wearing into the timber.

### Exit Ferrules

A second ferrule will protect the point where the string emerges from the upper surface of the backbone behind the bridge.

This will:

- prevent the string from cutting into the timber;
- provide a smooth transition toward the saddle;
- create a durable and repeatable string path.

The resulting arrangement is:

> **tail ferrule → backbone → top exit ferrule → saddle**

Exact ferrule type and dimensions remain implementation details.

## String Spacing

The three string anchors will use approximately:

**12 mm centre-to-centre spacing**

This matches the string spacing established at the bridge in DD-010.

The strings should therefore run substantially straight from their saddle contact points toward their corresponding tail anchors rather than fanning inward or outward.

This is particularly desirable with a floating bridge because it minimises lateral force that could encourage the bridge to creep sideways.

## Break Angle

The string path behind the saddle will target a break angle of approximately:

**10–15°**

The purpose of the break angle is to generate sufficient downward force to seat the floating bridge reliably against the soundboard.

The target should provide useful downward pressure without unnecessarily increasing the load applied to the bridge and resonant soundboard.

The break angle is a design target rather than a manufacturing tolerance.

The exact position of the string exit ferrules will therefore be determined from the actual:

- soundboard height;
- bridge height;
- saddle height;
- bridge position;
- tail geometry.

This avoids fixing anchor-hole dimensions before the playing geometry of the assembled instrument is known.

## Relationship to the Floating Bridge

The string anchor and bridge form a coupled system.

The tail anchor carries the longitudinal string tension.

The floating bridge redirects the strings at the saddle and transfers part of the resulting force downward into the soundboard.

The anchor geometry must therefore provide enough downforce to keep the bridge stable without using the bridge itself as a structural string anchor.

The strings will remain free to pull longitudinally against the neck-through backbone while the bridge primarily performs its acoustic and geometric roles.

## Trade-Offs

The central trade-off is between **simplicity and geometric flexibility**.

A separate tailpiece could provide an easily replaceable means of modifying the string anchor geometry.

Direct string anchoring provides a cleaner and more structurally direct solution, but makes the drilled geometry part of the instrument itself.

That makes it important not to drill the final string paths until the relevant bridge and soundboard dimensions are known.

The design therefore commits to the **architecture** of direct anchoring while deliberately deferring the exact hole positions.

A similar trade-off exists in break angle.

Too little break angle could leave the floating bridge insufficiently seated.

Too much would add unnecessary downward loading to the bridge and soundboard.

The 10–15° target provides a starting operating range that can be evaluated on the completed reference instrument.

## Decision

**Option 2: Direct String-Through Anchor**

The reference cigar box guitar will anchor its three strings directly through the tail region of the neck-through backbone.

The anchor system will:

- retain each string ball end at the tail face;
- use metal ferrules at the ball-end bearing points;
- use protected metal ferrules where the strings emerge onto the upper surface;
- maintain approximately 12 mm centre-to-centre spacing;
- keep the string paths substantially straight behind the saddle;
- target approximately 10–15° of break angle over the saddle;
- derive exact hole positions and drilling geometry from the actual completed bridge and soundboard geometry.

No separate tailpiece will initially be used.

## Consequences

This decision means that:

- the neck-through backbone will carry the primary string-anchor load;
- the resonant soundboard and body panels will not act as the primary longitudinal string anchor;
- the bridge can remain fully floating as established in DD-010;
- the bridge must receive sufficient downforce from the tail geometry to remain stable;
- the string anchor positions cannot be finalised until bridge and soundboard geometry are sufficiently defined;
- the three string paths should remain aligned with the 12 mm bridge spacing;
- six ferrules will be required, with three at the ball-end face and three at the upper string exits;
- suitable ferrule dimensions must be selected to match the reference string gauges;
- drilling accuracy will be important because the anchor paths pass through a structural component;
- the final break angle should be measured during setup rather than assumed from drawing dimensions alone;
- bridge stability and soundboard loading should both be evaluated on the completed instrument.

## Future Revisit

The string anchor should be reviewed after the reference instrument has been completed, restrung and played for a meaningful period.

We should then ask:

- Is restringing straightforward?
- Do the ball-end ferrules carry the load cleanly?
- Are the exit ferrules preventing visible string wear?
- Do the strings run straight from the saddle to the anchors?
- Does the floating bridge remain stable during normal playing?
- Is the achieved break angle appropriate?
- Is there any evidence of excessive downward loading on the soundboard?
- Have the ferrules remained secure?
- Did drilling the string paths through the backbone prove straightforward?
- Would a separate tailpiece offer any meaningful advantage?
- Would we choose direct string-through anchoring again for an instrument with similar goals?

## Sign-Off

**Approved.**

The reference cigar box guitar will use three ferrule-protected string-through anchors in the neck-through backbone, aligned with the bridge at 12 mm centres and positioned to produce approximately 10–15° of break angle over the floating bridge.
