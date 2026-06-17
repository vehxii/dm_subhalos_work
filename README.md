This branch of the repository contains current work + past versions of a pipeline for automatically creating all relevant plots for the overall project.

The end goal is to have a single function that takes in Symphony simulation data and some directories + settings (base_dir, suite_list, etc), and some tweakable global settings (controlling linestyles and linewidths, colors, whether the 16-84% confidence band is on/off, whether individual host lines are on/off, etc). Intended outputs are:

1. Subhalo mass functions (SHMFs)
2. Mass accretion histories (MAHs)
3. Novel plot comparing the host mass growth with the subhalo population growth over time.
4. Subhalo infall time distributions (raw counts, PDF, CDF, 50% host mass normalized PDF and CDF, etc)
5. Correlation functions, such as auto-correlation, cross-correlation, and two-point correlation function (like d'Souza & Bell 2021)
