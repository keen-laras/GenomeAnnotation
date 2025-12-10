# EviAnn (Version 2.0.4) & BRAKER (Version 3.0.8) Genome Annotation

Hello, everyone!
This is a guide to homology-based annotate your assembly using annotations from EviAnn and BRAKER

The tutorial is built for [DCS Cloud](https://cloud.stomics.tech/) users

- Github repository: [EviAnn](https://github.com/alekseyzimin/EviAnn_release), [BRAKER](https://github.com/Gaius-Augustus/BRAKER)
- Contact email for [this](https://github.com/keen-laras/RepeatAnnotation/tree/main) guide: kinanti.seraphina@gmail.com

## Tutorial
### 1. Image
- Use this image to run EviAnn in online/offline analysis
<img width="1491" height="305" alt="image" src="https://github.com/user-attachments/assets/26dc10cd-0fb9-49e4-9b31-93e6eab03a0c" />

- Use this image to run BRAKER in online analysis
<img width="1544" height="374" alt="image" src="https://github.com/user-attachments/assets/c2b5d8d1-96c5-481d-8e8e-282ba4606f7e" />


### 2. Run software
run [run_eviann.sh](https://github.com/keen-laras/GenomeAnnotation/blob/main/run_eviann.sh) 

`bash run_eviann.sh`

run [run_braker.sh](https://github.com/keen-laras/GenomeAnnotation/blob/main/run_braker.sh)

`bash run_braker.sh`

For {masked_input}.fa, please see [repeat annotation](https://github.com/keen-laras/RepeatAnnotation). Refer to `{output}.FINAL.masked.fa}`

### 3. Merge output file

`bash run_mergeOutput.sh`

Find cleanup_braker_gtf.py [here](https://github.com/keen-laras/GenomeAnnotation/blob/main/cleanup_braker_gtf.py)
