The-Mechanization-of-Standard-ML
================================

A fully formalized elaborative semantics for Standard ML based on the interpretation given
by Harper and Stone (see the Milner Festschrifft).  Contains a formal definition of the statics
and dynamics of the internal type theory of Standard ML, and a formalized elaboration from
the Standard ML external language into the internal language.  Also contains a machine-checked
proof of type safety of the internal language, and a machine-checked proof that well-elaborated
programs are type correct.  Therefore, well-elaborated Standard ML programs cannot incur a run-time
error arising from a misapplication of a primitve to a value.

This is the first, and until now, only fully formalized, machine-checked definition of a full-scale
usable programming language.  The mechanization was carried out by Karl Crary and Robert Harper using
"pair programming", meeting once per week for 2-3 hours over the course of a semester.  It was not
difficult to pick up the work from week to week, and there were no great obstacles to the mechanization
effort.  The prior work of Mark Lillibridge, Chris Stone, Daniel Lee, and the authors prepared the ground.
The project confirms the experience that one cannot expect to carry out a verification of an artifact
"thrown over the wall", but that it is entirely practical to do so if the development is carried out
with verification in mind.  This is a well-known fact about programs in general; this work confirms the
experience for programming languages themselves.
