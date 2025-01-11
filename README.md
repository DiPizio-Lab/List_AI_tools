# ProteinDesign



| Software Name        | Code Repository                                                                                                     | Webserver                                                                                            | Method                                 | Monomers   | Complexes   | Non-Protein   | Ensemble   | Sequence   | Reference                                                                     | Description                                                                                                                       |
|:---------------------|:--------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------|:---------------------------------------|:-----------|:------------|:--------------|:-----------|:-----------|:------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------|
| AlphaFold 2          | https://github.com/google-deepmind/alphafold                                                                        | nan                                                                                                  | nan                                    | Yes        | Yes         | No            | No         | No         | 10.1038/s41586-021-03819-2                                                    | nan                                                                                                                               |
| AlphaFold 3          | https://github.com/google-deepmind/alphafold3                                                                       | https://alphafoldserver.com/                                                                         | nan                                    | Yes        | Yes         | Yes           | No         | No         | 10.1038/s41586-024-07487-w                                                    | nan                                                                                                                               |
| AlphaFold-Multimer   | nan                                                                                                                 | nan                                                                                                  | nan                                    | Yes        | Yes         | No            | No         | No         | 10.1101/2021.10.04.463034v2.full                                              | nan                                                                                                                               |
| RoseTTAFold          | https://github.com/RosettaCommons/RoseTTAFold                                                                       | https://robetta.bakerlab.org/                                                                        | Neuronal Network                       | Yes        | Yes         | No            | No         | No         | 10.1126/science.abj8754                                                       | nan                                                                                                                               |
| RoseTTAFold All-Atom | https://github.com/baker-laboratory/RoseTTAFold-All-Atom; https://github.com/baker-laboratory/rf_diffusion_all_atom | https://neurosnap.ai/service/RoseTTAFold%20All-Atom                                                  | RFAA architecture                      | Yes        | Yes         | Yes           | No         | No         | 10.1126/science.adl2528                                                       | Denovo design                                                                                                                     |
| HelixFold3           | https://github.com/PaddlePaddle/PaddleHelix                                                                         | https://paddlehelix.baidu.com/app/all/helixfold3/forecast                                            | nan                                    | Yes        | Yes         | Yes           | No         | No         | https://arxiv.org/abs/2408.16975                                              | nan                                                                                                                               |
| Chai-1               | https://github.com/chaidiscovery/chai-lab                                                                           | https://lab.chaidiscovery.com/auth/login?callbackUrl=https%3A%2F%2Flab.chaidiscovery.com%2Fdashboard | nan                                    | Yes        | Yes         | Yes           | No         | No         | 10.1101/2024.10.10.615955                                                     | nan                                                                                                                               |
| Protenix             | https://github.com/bytedance/Protenix                                                                               | nan                                                                                                  | nan                                    | Yes        | Yes         | Yes           | No         | No         | https://github.com/bytedance/Protenix/blob/main/Protenix_Technical_Report.pdf | nan                                                                                                                               |
| Boltz-1              | https://github.com/jwohlwend/boltz                                                                                  | https://neurosnap.ai/service/Boltz-1%20(AlphaFold3)                                                  | nan                                    | Yes        | Yes         | Yes           | No         | No         | 10.1101/2024.11.19.624167                                                     | nan                                                                                                                               |
| ESM-2 Fold           | https://github.com/facebookresearch/esm/tree/main                                                                   | nan                                                                                                  | nan                                    | Yes        | No          | No            | No         | No         | 10.1073/pnas.2016239118                                                       | nan                                                                                                                               |
| OmegaFold            | https://github.com/HeliXonProtein/OmegaFold                                                                         | nan                                                                                                  | nan                                    | Yes        | No          | No            | No         | No         | s41467-023-37139-y                                                            | nan                                                                                                                               |
| AlphaFlow            | https://github.com/bjing2016/alphaflow                                                                              | nan                                                                                                  | nan                                    | Yes        | No          | No            | Yes        | No         | https://arxiv.org/abs/2402.04845                                              | nan                                                                                                                               |
| RF peptides          | https://www.ipd.uw.edu/2024/11/introducing-rfpeptides-ai-for-cyclic-peptide-design/                                 | nan                                                                                                  | nan                                    | No         | Yes         | No            | No         | No         | 10.1101/2024.11.18.622547v1                                                   | peptide design                                                                                                                    |
| RF difussion         | https://github.com/RosettaCommons/RFdiffusion/tree/main                                                             | nan                                                                                                  | nan                                    | Yes        | Yes         | No            | No         | No         | 10.1101/2022.12.09.519842                                                     | Denovo design                                                                                                                     |
| AlphaFold-multistate | https://github.com/huhlim/alphafold-multistate                                                                      | nan                                                                                                  | nan                                    | Yes        | Yes         | No            | No         | No         | 10.1002/prot.26382                                                            | GPCR specific bias to get active and inactive                                                                                     |
| trRosetta            | https://github.com/gjoni/trDesign                                                                                   | https://yanglab.nankai.edu.cn/trRosetta/download/                                                    | nan                                    | Yes        | No          | No            | No         | No         | s41586-021-04184-w                                                            | protein design applications                                                                                                       |
| Cfold                | https://github.com/patrickbryant1/Cfold                                                                             | Cfold.ipynb - Colab                                                                                  | nan                                    | Yes        | Yes         | No            | Yes        | No         | s41467-024-51507-2                                                            | predicting alternative conformations of protein structures                                                                        |
| DMFold-Multimer      | FOLD: https://zhanggroup.org/DMFold; MSA: https://zhanggroup.org/DeepMSA/                                           | nan                                                                                                  | deep learning                          | Yes        | Yes         | No            | No         | No         | 10.1038/s41592-023-02130-4                                                    | nan                                                                                                                               |
| Chroma               | https://github.com/generatebio/chroma                                                                               | https://colab.research.google.com/github/generatebio/chroma/blob/main/notebooks/ChromaDemo.ipynb     | nan                                    | Yes        | Yes         | No            | No         | No         | 10.1038/s41586-023-06728-8                                                    | protein design with given shape, generative model for proteins and protein complexe                                               |
| CombFold             | https://github.com/dina-lab3D/CombFold                                                                              | https://colab.research.google.com/github/dina-lab3D/CombFold/blob/master/CombFold.ipynb              | based partially on AF2-multimer        | No         | Yes         | No            | No         | No         | s41592-024-02174-0                                                            | assembles large protein complexes                                                                                                 |
| FragFold             | https://github.com/swanss/FragFold                                                                                  | nan                                                                                                  | employed AF2                           | No         | Yes         | No            | No         | No         | 10.1101/2023.12.19.572389                                                     | predict protein fragment binding to full-length proteins in a high-throughput manner                                              |
| MaSIF                | https://github.com/LPDI-EPFL/masif_seed                                                                             | nan                                                                                                  | nan                                    | No         | Yes         | No            | No         | No         | s41586-023-05993-x                                                            | De novo design                                                                                                                    |
| AF Cluster           | https://github.com/HWaymentSteele/AF_Cluster                                                                        | https://colab.research.google.com/github/HWaymentSteele/AF_Cluster/blob/main/AFcluster.ipynb         | nan                                    | Yes        | No          | No            | Yes        | No         | s41586-023-06832-9                                                            | generate ensemble suing AF2                                                                                                       |
| ProteinMPNN          | https://github.com/dauparas/ProteinMPNN                                                                             | nan                                                                                                  | deep learningbased protein sequence design                                        | No         | No          | No            | No         | Yes        | 10.1126/science.add2187                                                       | ProteinMPNN solves sequence design problems                                                                                       |
| ProtGPT2             | https://huggingface.co/nferruz/ProtGPT2                                                                             | nan                                                                                                  | nan                                    | No         | No          | No            | No         | Yes        | 10.1038/s41467-022-32007-7                                                    | protein design                                                                                                                    |
| ZymCTRL              | https://huggingface.co/AI4PD/ZymCTRL/tree/main                                                                      | nan                                                                                                  | nan                                    | No         | No          | No            | No         | Yes        | https://doi.org/10.1101/2024.05.03.592223                                     | enzyme design                                                                                                                     |
| NeuralPlexer         | https://github.com/zrqiao/NeuralPLexer                                                                              | nan                                                                                                  | multiscale deep generative model       | No         | No          | Yes           | No         | No         | s42256-024-00792-z                                                            | proteinligand complex structures using protein sequence and ligand molecular graph inputs                                                                                                                                   |
| DiffDock-L           | https://github.com/gcorso/DiffDock                                                                                  | https://huggingface.co/spaces/reginabarzilaygroup/DiffDock-Web                                       | nan                                    | No         | No          | Yes           | No         | No         | https://arxiv.org/abs/2402.18396                                              | proteinligand complex structures                                                                                                                                   |
| DynamicBind          | https://github.com/luwei0917/DynamicBind                                                                            | https://neurosnap.ai/service/DynamicBind                                                             | deep equivariant generative model      | No         | No          | Yes           | No         | No         | s41467-024-45461-2                                                            | proteinligand complex structures; it works with unbound protein structures                                                                                                                                   |
| PocketGen            | https://github.com/zaixizhang/PocketGen                                                                             | https://zitniklab.hms.harvard.edu/projects/PocketGen/                                                | nan                                    | No         | No          | Yes           | No         | No         | s42256-024-00920-9                                                            | Generating Full-Atom Ligand-Binding Protein Pockets                                                                               |
| GrASP                | https://github.com/tiwarylab/GrASP                                                                                  | https://colab.research.google.com/github/tiwarylab/GrASP/blob/main/GrASP.ipynb                       | nan                                    | No         | No          | No            | No         | No         | 10.1021/acs.jcim.3c01698                                                      | Identifying Druggable Binding Sites                                                                                               |
| LightDock            | https://github.com/lightdock                                                                                        | https://server.lightdock.org/                                                                        | nan                                    | No         | No          | Yes           | No         | No         | 10.1093/nar/gkad327                                                           | protein and all type of ligand DNA,RNA and small molecules                                                                        |
| AlphaMissense        | https://github.com/deepmind/alphamissense                                                                           | nan                                                                                                  | unsupervised protein language modeling | nan        | nan         | nan           | nan        | nan        | 10.1126/science.adg7492                                                       | effect of mutation in the sequnece and structural level, proteome-wide missense variant effect prediction                         |
| evo                  | https://github.com/evo-design/evo                                                                                   | https://colab.research.google.com/github/evo-design/evo/blob/main/scripts/hello_evo.ipynb            | Large language models                  | nan        | nan         | nan           | nan        | nan        | 10.1126/science.ado9336                                                       | design crisp system, designs synthetic multi-component biological systems, predicts the effects of mutations down to genome level |
| AlphaFold database   | nan                                                                                                                 | https://alphafold.ebi.ac.uk/                                                                         | nan                                    | Yes        | No          | No            | No         | nan        | nan                                                                           | Database with over                                                                                                                |
| ColabFold            | nan                                                                                                                 | https://github.com/sokrypton/ColabFold                                                               | nan                                    | Yes        | Yes         | Yes           | No         | nan        | 10.1101/2024.11.18.622547v1                                                   | jupyter notebooks to run on clouds different software                                                                             |
| AlphaBridge          | nan                                                                                                                 | alpha-bridge.eu                                                                                      | nan                                    | No         | No          | No            | No         | nan        | 10.1101/2024.10.23.619601v1                                                   | tools for analysis of alphafold results                                                                                           |
| cPEPmatch            | https://github.com/briandasantini/cPEPmatch                                                                         | https://t38webservices.nat.tum.de/cpepmatch/                                                         | Classical homology model               | Yes        | Yes         | No            | No         | nan        | https://pubmed.ncbi.nlm.nih.gov/33134275/                                     | cyclic peptide design                                                                                                             |
