# UD-annotated Szeged Treebank

This folder contains a slice of the [Szeged Dependency Treebank](https://rgai.inf.u-szeged.hu/node/113). The data provided contains sentences that are not
overlapping with the [UD Hungarian](https://universaldependencies.org/treebanks/hu_szeged/index.html) corpus 
(which is a subcorpus of the Szeged Corpus). UD annotations are automagically converted from the original annotation,
thus it might contain some errors.

# Changelog

- 2023-10-24
  - Fixed lemmata of errounously HTML encoded numerical tokens

- 2022-09-27
  - Case=Sub now means subessive in corpus; sublative relabeled to Case=Sbl.

- 2022-09-16
  - Removed PronType=Default
  - Replace Definite=Indef to Definite=Ind
  - Replace Cas=none|SubPOS=c to Case=Nom|Number=Sing
  - Removed PronType=Dem when the token is "olyan" as a ADV
  - Replaced Mood=Ind to Mood=Pot when the token is "lehet" and "kerülhet" as a VERB
  - Replaced Voice=Act to Voice=Cau when the token is "tájékoztatta" as a VERB
  - Added VerbForm=Fin to some token when the token's POS is AUX
  - Added VerbForm=PartPast to some token when the token's POS is ADJ
  - Removed Degree=Pos and added VerbForm=PartPres/VerbForm=PartPast when the token's POS is ADJ and It has Case=Nom feature too
