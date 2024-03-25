# Welcome to the Microreact Cookbook

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.



<div class="grid cards" markdown>

-   :material-clock-fast:{ .lg .middle } __Set up in minutes__

    ---

    Install `bactopia` from [Bioconda](https://bioconda.github.io/) and start processing
    genomes in minutes

    [:octicons-arrow-right-24: Installation](installation.md)

-   :material-bacteria:{ .lg .middle } __Effortless bacterial genomics__

    ---

    Streamlined pipeline for efficient and complete analysis of bacterial genomes

    [:octicons-arrow-right-24: Beginner's Guide](beginners-guide.md)

-   :material-lightbulb-on:{ .lg .middle } __Seamlessly expand analyses__

    ---

    Rapidly extend studies with a variety of supplementary, ready-made, workflows

    [:octicons-arrow-right-24: Bactopia Tools](bactopia-tools/index.md)

-   :material-star:{ .lg .middle } __Making an impact__

    ---

    A free and open-source tool that regularly contributes back to the community

    [:octicons-arrow-right-24: Impact and Outreach](impact-and-outreach/index.md)

</div>

### <i class="fa-xl fas fa-terminal"></i> Input Parameters
The following parameters are how you will provide either local or remote samples to be processed by Bactopia.

| Parameter | Description |
|:---|---|
| <i class="fa-lg fas fa-file-alt"></i>` --samples` | A FOFN (via bactopia prepare) with sample names and paths to FASTQ/FASTAs to process <br/>**Type:** `string` |
| <i class="fa-lg fas fa-file-archive"></i>` --r1` | First set of compressed (gzip) Illumina paired-end FASTQ reads (requires --r2 and --sample) <br/>**Type:** `string` |
| <i class="fa-lg fas fa-file-archive"></i>` --r2` | Second set of compressed (gzip) Illumina paired-end FASTQ reads (requires --r1 and --sample) <br/>**Type:** `string` |
| <i class="fa-lg fas fa-file-archive"></i>` --se` | Compressed (gzip) Illumina single-end FASTQ reads  (requires --sample) <br/>**Type:** `string` |
| <i class="fa-lg fas fa-level-up"></i>` --ont` | Compressed (gzip) Oxford Nanopore FASTQ reads  (requires --sample) <br/>**Type:** `string` |
| <i class="fa-lg fas fa-level-up"></i>` --hybrid` | Create hybrid assembly using Unicycler.  (requires --r1, --r2, --ont and --sample) <br/>**Type:** `boolean` |
| <i class="fa-lg fas fa-level-up"></i>` --short_polish` | Create hybrid assembly from long-read assembly and short read polishing.  (requires --r1, --r2, --ont and --sample) <br/>**Type:** `boolean` |
| <i class="fa-lg fas fa-file"></i>` --sample` | Sample name to use for the input sequences <br/>**Type:** `string` |
| <i class="fa-lg fas fa-file-alt"></i>` --accessions` | A file containing ENA/SRA Experiment accessions or NCBI Assembly accessions to processed <br/>**Type:** `string` |
| <i class="fa-lg fas fa-font"></i>` --accession` | Sample name to use for the input sequences <br/>**Type:** `string` |
| <i class="fa-lg fas fa-file-archive"></i>` --assembly` | A assembled genome in compressed FASTA format. (requires --sample) <br/>**Type:** `string` |
| <i class="fa-lg fas fa-level-up"></i>` --check_samples` | Validate the input FOFN provided by --samples <br/>**Type:** `boolean` |



!!! tip "`--sample` is always required for single-sample processing"
    When processing a single sample, you will always have to provide `--sample`, no matter
    input type. This parameter is used to name the output files and directories. 


<div class="grid cards" markdown>

- :fontawesome-brands-html5: __HTML__ for content and structure
- :fontawesome-brands-js: __JavaScript__ for interactivity
- :fontawesome-brands-css3: __CSS__ for text running out of boxes
- :fontawesome-brands-internet-explorer: __Internet Explorer__ ... huh?

</div>