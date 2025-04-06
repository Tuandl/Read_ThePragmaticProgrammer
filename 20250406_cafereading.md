Sometimes, code duplication is on good purpose, because they are different knowledge but coincidently same logic.

# Vocabulary:
- Fall afoul of: fall into trouble because of disobeying or not following
- Inadvertenly: in a way that is not intention.
- Insidious: a harm that gradually, subtly grow from inside that you don't aware about it
- Intrusive: disrupt, annoying action
- Snoop: inspect to attempt to find out information about something like other affairs
- Reciprocol: in exchange for something inreturn.
- Orthogonality: 2 vectors, 2 lines intersect at 90 degree angle
- Signify: be an indication of something
- interdependent: depend on each other
- riplle: a serie of waves caused by a dropped object
- 

# Representation duplication
when exposing code via API, both producers and consumers need to store knowledges of these APIs
that's inevitable, but we can mitigate some by followings

## Duplicate across internal APIs
adopt to a tool that help to specify api in a neutral format.
these tools will help to generate functions, mock apis, funtional test, api client
the point is to be able to share across the team

## Duplicate across external APIs
same with internal apis. should find a neutral format, if there is none, let's creat one to share others

## Duplicate with data source
can use a tool like ORM to create a container for a table schema

## Interdeveloper duplication
communication will help, like scrum meeting

# Orthogonality
Inpired from geomatric, 2 modules are orthogonal when they only meet at a speciclfic point
Which mean changing 1 won't affect the other.
this highlights the loose coupling, independence

## non orthogonal system
it's helicopter controls. It has 4 basic controls.
When changing each control input, it has side effects, therefor we must compensate by changing other controls to make it stable.

## benefit of orthogonality
the inherent effect is eliminate side effects between unrelated things
- increase productivity by easy reusing, reduce testing time
- reduce risk. deseased code is isolated, less fragile, better test, not tight to any particular vendor

## design orthogonal system

