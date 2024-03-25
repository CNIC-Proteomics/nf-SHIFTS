# nf-SHIFTS
Nextflow pipeline for the SHIFTS workflow


# Usage

Debugging using Ubuntu (Docker - backend):
```
cd /usr/local/nf-SHIFTS

nextflow \
    -log "/opt/nextflow/nextflow/log/nf-shifts.log" \
    run main.nf   \
        -params-file "/mnt/tierra/nf-SHIFTS/tests/test1/inputs/inputs.yml" \
        --outdir  "/mnt/tierra/nf-SHIFTS/tests/test1" \
        --params_file "/mnt/tierra/nf-SHIFTS/tests/test1/inputs/params.ini" \
        -resume
```

In Production using the Web Server

