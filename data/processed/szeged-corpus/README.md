# UD-annotated Szeged Treebank

This folder contains a slice of the [Szeged Dependency Treebank](https://rgai.inf.u-szeged.hu/node/113). The data provided contains sentences that are not
overlapping with the [UD Hungarian](https://universaldependencies.org/treebanks/hu_szeged/index.html) corpus 
(which is a subcorpus of the Szeged Corpus). UD annotations are automagically converted from the original annotation,
thus it might contain some errors.

# Morph Changelog
- 2022-09-16
  - Removed PronType=Dem when the token is "olyan" as a ADV
  - Replaced Mood=Ind to Mood=Pot when the token is "lehet" and "kerülhet" as a VERB
  - Replaced Voice=Act to Voice=Cau when the token is "tájékoztatta" as a VERB
  - Added VerbForm=Fin to some token when the token's POS is AUX
  - Added VerbForm=PartPast to some token when the token's POS is ADJ
  - Removed Degree=Pos and added VerbForm=PartPres/VerbForm=PartPast when the token's POS is ADJ and It has Case=Nom feature too