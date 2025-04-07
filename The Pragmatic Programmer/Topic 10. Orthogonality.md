## Vocabulary
- `Fall afoul of`: fall into trouble because of disobeying or not following
- `Inadvertently`: in a way that is not intentional.
- `Insidious`: harm that gradually and subtly grows from within, often unnoticed
- `Intrusive`: disrupt, annoying action
- `Snoop`: inspect to attempt to find out information about something like other affairs
- `Reciprocal`: in exchange for something in return.
- `Orthogonality`: Two vectors or lines intersect at a 90-degree angle
- `Signify`: be an indication of something
- `interdependent`: depend on each other
- `ripple`: a series of waves caused by a dropped object

## What is Orthogonality
Inspired by geometric principles, two modules are orthogonal when they only meet at a specific point. Which means changing one won't affect the other. This highlights the loose coupling, independence.
## Non orthogonal system
Tt's helicopter controls. It has 4 basic controls.
Changing each control input has side effects; therefore, we must adjust other controls to maintain stability.

## Benefit of orthogonality
The inherent effect is eliminate side effects between unrelated things
- Increase productivity by easy reusing, reduce testing time
- Reduce risk: decoupled code is isolated, less fragile, easier to test, and not tightly coupled to any particular vendor.

## Design orthogonal system