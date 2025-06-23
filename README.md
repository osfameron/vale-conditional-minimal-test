# Output

```
❯ vale .

 test-with-definition.adoc
 1:1   error  'TLA' hasn't been defined.      Minimal.UnexplainedAcronym
              Spell it out if it's
              unfamiliar to the audience.
 3:11  error  'TLA' hasn't been defined.      Minimal.UnexplainedAcronym
              Spell it out if it's
              unfamiliar to the audience.


 test-without-definition.adoc
 1:11  error  'TLA' hasn't been defined.      Minimal.UnexplainedAcronym
              Spell it out if it's
              unfamiliar to the audience.

✖ 3 errors, 0 warnings and 0 suggestions in 3 files.
```

# Expectation

Would expect test-with-definition.adoc to NOT be flagged?
