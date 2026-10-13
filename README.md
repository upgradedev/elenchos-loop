# elenchos-loop

Second repository for the Elenchos runner-validated loop (r11). The base holds the
violating tree (`.github/workflows/r11-target.yml`) and the compliant source
(`loop-source/clean.yml`, not a workflow so it never triggers). Loop experiments push
`loop/<slug>/{before,repaired,clean}` branches; each push runs the target workflow once.
Evidence class: RUNNER_VALIDATED, never Sandbox.
