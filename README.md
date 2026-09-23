# Awesome-Genomics-Data-Platform

## Top Genomics Data Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Genomic Analysis Workspaces, Workflow Orchestration, Multi-Omics Data & Collaborative Bioinformatics*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Genomics Data Platforms**. These systems provide secure workspaces, workflow engines, data management, and collaboration tools for large-scale genomic and multi-omics analysis in research and clinical settings.



**Examples** include DNAnexus, Seven Bridges (Velsera), Illumina Connected Analytics, Terra (Broad Institute), BaseSpace Sequence Hub, Seqera, Genialis, Fabric Genomics, SOPHiA GENETICS, and PrecisionFDA (the category leaders).



**Open-source emphasis**: Genomics has excellent open platforms. **Galaxy**, **Cromwell/WDL**, **Nextflow**, and Terra’s open components power a large share of academic and consortium-scale analysis. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[DNAnexus](https://www.dnanexus.com/)**  

  Enterprise precision-health data platform for governed genomic data, workflows, notebooks, and cohort analysis with strong compliance posture.



- **[Seven Bridges / Velsera](https://www.sevenbridges.com/)**  

  Bioinformatics platform with deep oncology and multi-omics capabilities, CWL support, and major public-cloud research deployments (e.g., Cancer Genomics Cloud).



- **[Illumina Connected Analytics](https://www.illumina.com/)**  

  Illumina’s cloud analytics environment for secondary analysis, data management, and integration with sequencing workflows.



- **[Terra (Broad Institute)](https://terra.bio/)**  

  Cloud-native biomedical analysis platform co-developed by Broad, Verily, and Microsoft—widely used for WDL/GATK workflows, notebooks, and large consortia (pay for cloud resources).



- **[BaseSpace Sequence Hub](https://www.illumina.com/)**  

  Illumina’s sequencing data management and analysis hub for instrument output, apps, and collaboration.



- **[Seqera Platform](https://seqera.io/)**  

  Nextflow-centric orchestration and control plane for running pipelines across cloud, hybrid, and HPC environments.



- **[Genialis](https://www.genialis.com/)**  

  Biomedical data analysis platform focused on RNA-seq and multi-omics interpretation for research and translational use.



- **[Fabric Genomics](https://fabricgenomics.com/)**  

  Clinical genomic interpretation and analysis platform used in diagnostic and precision-medicine settings.



- **[SOPHiA GENETICS](https://www.sophiagenetics.com/)**  

  Data-driven medicine platform combining genomic analysis, AI, and clinical reporting for healthcare institutions.



- **[PrecisionFDA](https://precision.fda.gov/)**  

  FDA’s collaborative platform for evaluating bioinformatics pipelines and advancing regulatory science in genomics.



## Open-Source GitHub Projects

- **[Galaxy](https://github.com/galaxyproject/galaxy)**  

  Leading open-source, web-based platform for accessible, reproducible biomedical data analysis—thousands of tools, workflows, and a global training community.



- **[Cromwell](https://github.com/broadinstitute/cromwell)**  

  Open-source workflow engine for WDL (Workflow Description Language), designed for simplicity and scalability from laptop to cloud (core of Terra execution).



- **[Nextflow](https://github.com/nextflow-io/nextflow)**  

  Open-source workflow system for scalable and reproducible scientific pipelines, with strong cloud and container support (foundation of Seqera Platform).



- **[WARP (Broad Institute pipelines)](https://github.com/broadinstitute/warp)**  

  Open, production-grade, cloud-optimized WDL pipelines for large-scale genomics consortia, tuned for Terra and Cromwell.



- **[Snakemake](https://github.com/snakemake/snakemake)**  

  Open-source workflow management system widely used in bioinformatics for scalable, reproducible pipelines.



- **[nf-core](https://github.com/nf-core)**  

  Community collection of high-quality, curated Nextflow pipelines for genomics and multi-omics analysis.



- **[Dockstore](https://github.com/dockstore/dockstore)**  

  Open platform for sharing Docker-based tools and workflows (WDL, CWL, Nextflow) used across Terra, Galaxy, and other systems.



- **[GA4GH standards and tool registries](https://github.com/ga4gh)**  

  Open standards and reference implementations for genomic data sharing, workflows, and tool discovery.



- **[Bioconductor / open R genomics stacks](https://github.com/Bioconductor)**  

  Open R packages and infrastructure for statistical analysis of genomic data, often run inside Terra or Galaxy environments.



- **[Open notebook and analysis environments](https://github.com/)**  

  Jupyter, RStudio, and related open tools commonly deployed within genomics data platforms.



### Additional Strong Open-Source Options

- Running **Galaxy** (public servers or self-hosted) for accessible, tool-rich analysis.

- Using **Cromwell + WDL** or **Nextflow + nf-core** for scalable, reproducible pipelines on any cloud or HPC.

- Leveraging **Terra** as a managed front-end while keeping workflows and pipelines open.

- Combining open workflow engines with commercial data platforms for compliance-sensitive workloads.

- Accepting that validated clinical pipelines, multi-cloud governed data environments, and enterprise support still favor commercial platforms (DNAnexus, Seven Bridges, Illumina, SOPHiA, Fabric, etc.).

- Focusing open-source efforts on reproducibility, portability, and community-curated pipelines.



**Frameworks for building custom systems**: Write pipelines in WDL (Cromwell) or Nextflow → register in Dockstore → execute on Terra, self-hosted Cromwell/Nextflow, or Galaxy → analyze results in open notebooks or Bioconductor → share via GA4GH-compatible APIs. Suitable for academic, consortium, and many industry research teams. Clinical and highly regulated environments often layer commercial platforms on top of open methods.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Genomics data platforms handle highly sensitive human genetic data. Compliance (HIPAA, GDPR, clinical validation) and security are critical. Open-source tools require careful deployment and governance. This list is not clinical, regulatory, or legal advice.



---

**Made for bioinformaticians, genomic researchers, and precision-medicine teams.**

Let's keep genomic analysis reproducible, portable, and as open as practical.
