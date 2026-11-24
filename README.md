# site-generator-speed-01 entry

A faster drop-in for makefun-site 1.0.0: `solve.js` exports `run(input)` and
returns the identical output tree (byte for byte) at lower CPU time.
`main.ts` is the standard harness driver (reads /input/cases.json, writes
/output/answers.json).
