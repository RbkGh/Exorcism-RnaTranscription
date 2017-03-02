# Rna Transcription

Given a DNA strand, return its RNA complement (per RNA transcription).

Both DNA and RNA strands are a sequence of nucleotides.

The four nucleotides found in DNA are adenine (**A**), cytosine (**C**),
guanine (**G**) and thymine (**T**).

The four nucleotides found in RNA are adenine (**A**), cytosine (**C**),
guanine (**G**) and uracil (**U**).

Given a DNA strand, its transcribed RNA strand is formed by replacing
each nucleotide with its complement:
exercism submit src/main/java/extra/DnaStrand.java src/main/java/extra/RnaStrand.java src/main/java/main/DnaStrategy.java src/main/java/main/DnaStrategyContext.java src/main/java/main/RnaTranscriptProcessor.java src/main/java/strategies/AdenineStrategy.java src/main/java/strategies/CytosineDnaStrategy.java src/main/java/strategies/DefaultDnaStrategy.java src/main/java/strategies/GuanineDnaStrategy.java src/main/java/strategies/ThymineStrategy.java
* `G` -> `C`
* `C` -> `G`
* `T` -> `A`
* `A` -> `U`


To run the tests:

```sh
$ gradle test
```

For more detailed info about the Java track see the [help page](http://exercism.io/languages/java).

## Source

Rosalind [http://rosalind.info/problems/rna](http://rosalind.info/problems/rna)

## Submitting Incomplete Problems
It's possible to submit an incomplete solution so you can see how others have completed the exercise.
