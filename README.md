# tools
Scripts and tools for Quokka data processing and initial condition preparation.

To use the tools, install chongchonghe's fork of YT from https://github.com/chongchonghe/yt and add the `bin` directory of this repo to your `PATH`.

## Plotting 

### quick_plot

Quickly plot slices or projections of a field with particle annotations, enabling parallel processing for multiple snapshots. Run `quick_plot -h` for a full list of options.

Example usage:

```bash
quick_plot plt00* --field n --particles StochasticStellarPop_particles -j 8 --p_size 300 --time_interval 0.1_Myr 
```

