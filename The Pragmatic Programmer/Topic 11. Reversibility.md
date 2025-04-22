> Nothing is more dangerous than an idea if it's the only one you have.
> Emil-Aguste Chartier (Alain), Propos sur la religion, 1938

## Vocabulary
- `myriad`: multitude, countless or an extreme number
- `hamper`: a basket to used for laundry. (v) To prevent someone to do something easily
- `myopic`: lack of insight, imagination
- `forcibly`: using force or violent
- `Draconian`: excessively harsh and severe. This word is derived from `Draco`, which is a law in Athenian scribe under whom small offenses had heavy punishment.
- `untenable`: not able to defend, maintain against the objection.
- `cast in something`: shape a material by pouring the molten into a mold.
- `contingency`: something might happen in the future, usually cause problem or making further arrangement necessary.
- `big hunk of iron`: in software engineer, this is an idiom refers to a mainframe computer, a powerful and large scale computer system used for critical applications and large scale data processing.
- `federations of big iron`: connecting mainframe computers together for distributed processing, resource pooling.
- `fad`: a style, activity, interest that becomes popular for a short time
- `awe`: a feeling of great respect, sometimes mixed with fear or surprise.
- `volatility`: tendency of a substance to evaporate at normal temperature, liable to change rapidly.
- `forgo`: omit or decline to something pleasant or valuable. Go without.

## Introduction

**Butterfly effect**
The phrase "butterfly flaps its wings" is a metaphor that is popularized by chaos theory, illustrating that small, seemingly insignificant event can cause large, and unpredictable consequences.

We cannot anticipate everything, something seemingly, insignificant can cause chaos. Most of the critical decisions are not easily reversible. When choosing the database provider, a deployment model, you're committed to a course of actions that cannot be undone, except at a great expense.

## Reversibility
Should prepare for contingencies that might happen any time in the future. Because there are no final decisions, decisions change rapidly so that we cannot cast the implementation to a stone. Instead, we should write it inside the sand to prepare for the incoming wave at anytime.

> Tip 18, There are no final decisions

### Flexible architecture
There are many fads about technology like the server-side architecture:
1. Big hunk of iron
2. Federated big hunk of iron
3. Load-balanced clusters of commodity hardware
4. Cloud-based virtual machine
5. Containerized
6. Cloud-supported serverless application
7. Eventually, some tasks moved back to a big hunks of iron nowadays.

> Tip 19, Forgo following fads

Should build the code to rock-n-roll:
- to rock on when it can.
- To roll with the punches when it must.

**Schrodinger's cat**
There is a black box that has a cat and a nuclear radioactive particle inside. The particle has 50% of the chance of fissioning into two. If it does the cat will die. So, is the cat alive or dead? Regarding Schrodinger's cat, it's both at least when we have not opened the box.
If we apply this metaphor into software engineering, every decision results in a new future. How many possible futures can your code support? Which one is more likely? How hard will it be to support them when the time comes?

