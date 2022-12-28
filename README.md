# Brassinosteroid gene regulatory networks at cellular resolution in the Arabidopsis root

This repository contains the code to reproduce the analysis described in [Brassinosteroid gene regulatory networks at cellular resolution in the Arabidopsis root]( https://doi.org/10.1101/2022.09.16.508001) 

## Arabidopsis Root Virtual Expression eXplorer (ARVEX)

Visit [ARVEX](https://shiny.mdc-berlin.de/ARVEX/) to interactively view the data associated with this study. 

## Data

Raw and processed scRNA-seq data associated with this study are available on GEO: [GSE212230](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE212230)

input files for the notebooks below are under `data/`. Note that files larger than github's size limit can be downloaded from [ARVEX](https://shiny.mdc-berlin.de/ARVEX/).

## Notebooks 

[01-Run_COPILOT_preprocessing](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/COPILOT_preprocessing.ipynb)

[02-WT_atlas_dev_stage_reannotation](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/Atlas_dev_stage_reannotation.ipynb)

[03-Gene_ontology_WT_atlas_updated_dev_anno](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/01-BR-03-WT_atlas_updated_dev_anno_GO.ipynb)

[04-Label_transfer](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/Label_transfer.ipynb)

[05-Integration](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/Integration_BR_time_course.ipynb)

[06-Differential_expression_analysis_BL_2hour_vs_BRZ](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/01-BR-04-BL-2hour-vs-BRZ-pseudobulk-DE.ipynb)

[06-Differential_expression_analysis_bri1-T_vs_WT](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/03-bri1-01-bri1-T_vs_WT-pseudobulk-DE.ipynb)

[06-Differential_expression_analysis_BRZ_vs_Control](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/04-BRZ-WT-BRZ-vs-Control-pseudobulk-DE.ipynb)

[06-Differential_expression_analysis_pGL2-BRI1-GFP-bri1-T_vs_WT](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/03-bri1-02-pGL2-BRI1-GFP-bri1-T_vs_WT-pseudobulk-DE.ipynb)

[06-Differential_expression_analysis_pGL2-BRI1-GFP-bri1-T_vs_bri1-T](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/03-bri1-03-pGL2-BRI1-GFP-bri1-T_vs_bri1-T-pseudobulk-DE.ipynb)

[06-Differential_expression_analysis_gtl1df1_vs_WT](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/07-gtl1df1-02-gtl1df1_vs_WT-pseudobulk-DE.ipynb)

[06-Differential_expression_analysis_gtl1_vs_WT](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/07-gtl1df1-03-gtl1_vs_WT-pseudobulk-DE.ipynb)

[06-Differential_expression_analysis_df1_vs_WT](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/07-gtl1df1-04-df1_vs_WT-pseudobulk-DE.ipynb)

[07-Prepare_base_GRN_01](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/Base-01-GRN_preparation_for_CellOracle.ipynb)

[07-Prepare_base_GRN_02](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/Base-02-GRN_preparation_for_CellOracle.ipynb)

[07-Prepare_base_GRN_03](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/Base-03-GRN_preparation_for_CellOracle.ipynb)

[07-Prepare_base_GRN_04](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/Base-04-GRN_preparation_for_CellOracle.ipynb)

[08-Run_CellOracle_BR](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/CellOracle_BR_time_course.ipynb)

[08-Run_CellOracle_WT](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/CellOracle_WT.ipynb)

[08-CellOracle_WT_GRNs](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/06-GRNs-02-CellOracle-WT-GRN-configs.ipynb)

[08-CellOracle_BR_GRNs](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/06-GRNs-03-CellOracle-BR-GRN-configs.ipynb)

[08-CellOracle_compare_GRNs](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/06-GRNs-06-CellOracle-vs-bulk-GRN.ipynb)

[09-WOT_compute_trajectories](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/wot1-compute-trajectories.ipynb)

[09-WOT_analyze_results](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/wot2-analyze-results.ipynb)

[10-Compare_BES1_and_GTL1_targets_and_overlap_with_BL_scRNA-seq_data](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/07-gtl1df1-06-GTL1_BES1_targets.ipynb)

[11-Plot_bri1-T_DEGs_results_on_umap](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/03-bri1-04-bri1-T-DEG-umaps.ipynb)

[11-Plot_bri1-T_DEGs](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/03-bri1-06-bri1-DEG-barplots-and-GO.ipynb)

[11-Plot_gtl1_df1_DEGs](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/07-gtl1df1-05-DEGs-barplots-and-GO.ipynb)

[12-Plot_CellOracle_base_GRNs](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/06-GRNs-01-CellOracle-baseGRN.ipynb.ipynb)

[12-Plot_CellOracle_BR_cortex_GRN](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/06-GRNs-04-CellOracle-HAT7-GTL1-plotting.ipynb)

[13-Plot_MDS](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/03-bri1-05-bri1-T_MDS.ipynb)

[14-Plot_163_core_BR_DEGs](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/05-163-core-BR-DEGs-01-UpSet-plots.ipynb)

[15-Plot_cell_length](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/06-GRNs-05-gtl1-hat7-quad-cell-length-plots.ipynb)

[16-Plot_gtl_df1_samples_on_umap](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/07-gtl1df1-01-gtl1df1_umaps.ipynb)

[17-Plots_on_ARVEX](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/ARVEX_Plots.ipynb)

[18-Plot_marker_dot_plot](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/Marker_dot_plots.ipynb)

[19-Plot_tradeseq](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/Tradeseq_BR_time_course.ipynb)

[20-Plot_WOT_Cell_wall_signature_over_BR_time_series](https://github.com/tmnolan/Brassinosteroid-gene-regulatory-networks-at-cellular-resolution/tree/master/02_BR_02_WOT_density_and_bar_plots.ipynb)
