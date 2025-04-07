Sometimes, code duplication is intentional because different contexts may require similar logic.
# Vocabulary:
- Fall afoul of: fall into trouble because of disobeying or not following
- Inadvertently: in a way that is not intentional.
- Insidious: harm that gradually and subtly grows from within, often unnoticed
- Intrusive: disrupt, annoying action
- Snoop: inspect to attempt to find out information about something like other affairs
- Reciprocal: in exchange for something in return.
- Orthogonality: Two vectors or lines intersect at a 90-degree angle
- Signify: be an indication of something
- interdependent: depend on each other
- ripple: a series of waves caused by a dropped object
- 

# Representation duplication
when exposing code via API, both producers and consumers need to store knowledges of these APIs
that's inevitable, but we can mitigate some by followings

## Duplicate across internal APIs
adopt to a tool that help to specify api in a neutral format.
these tools will help to generate functions, mock apis, funtional test, api client
the point is to be able to share across the team

## Duplicate across external APIs
Same as internal APIs; if a neutral format does not exist, let's create one to share with others.
## Duplicate with data source
can use a tool like ORM to create a container for a table schema

## Interdeveloper duplication
communication will help, like scrum meeting

# Orthogonality
Inspired by geometric principles, two modules are orthogonal when they only meet at a specific point.
which means changing one won't affect the other.
this highlights the loose coupling, independence

## non orthogonal system
it's helicopter controls. It has 4 basic controls.
When changing each control input, it has side effects, therefor we must compensate by changing other controls to make it stable.

## benefit of orthogonality
the inherent effect is eliminate side effects between unrelated things
- increase productivity by easy reusing, reduce testing time
- reduce risk. deseased code is isolated, less fragile, better test, not tight to any particular vendor

## design orthogonal system

