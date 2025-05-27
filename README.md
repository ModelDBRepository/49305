Note:
[Click here for the model tar.gz file](http://www.cns.atr.jp/neuroinfo/doi/doiJNSdemo.tar.gz) available from [http://www.cns.atr.jp/neuroinfo/doi/indexE.html](http://www.cns.atr.jp/neuroinfo/doi/indexE.html)

---

Note from the ModelDB administrator: here are some notes from an original readme supplied by the authors:

---

# Instruction for demo simulations that generate the simulation figures in

Tomokazu Doi, Shinya Kuroda, Takayuki Michikawa, and Mitsuo Kawato
Inositol 1,4,5-Tripshosphate-Dependent Ca2+ Threshold Dynamics Detect Spike Timing in Cerebellar Purkinje Cells.
*The Journal of Neuroscience* 25(4): 950-961, 2005

The simulation requires GENESIS version 2.2 and kinetikit version 9 or higher. Both of which are included in the compressed file you have downloaded. We have confirmed that our simulation scripts run on Red Hat Linux version 8 and Pentium 4 PCs.

---

## HOW TO RUN DEMOS

To extract doiJNSdemo.tar.gz, type

```
tar zxvf doiJNSdemo.tar.gz
```

The created directory has several files named fig*.g.  To run demos, just type

```
genesis fig3.g
```

(or choose other files named fig*.g)

GENESIS/kinetikit includes model scripts for the simulation, and displays and saves simulation results in `simresult/fig*/`. In simresult/fig*/, there are MATLAB script files (*.m) which display the simulation results as in the JNS paper. Comments in fig*.g might be useful to understand how GENESIS/kinetikit works.

Some simulations take enormous time, more than months. Here is a list of expected time for simulation on a 2 GHz Pentium 4 PC.

| File          | Time      |
|---------------|-----------|
| fig3.g        | 4 min     |
| fig4.g        | 12 min    |
| fig5.g        | 20 min    |
| fig6A.g       | 3 min     |
| fig6B.g       | 7 hrs     |
| fig6C.g       | 3 min     |
| fig7A.g       | 12 min    |
| fig7B.g       | 9 hrs     |
| fig8CDE.g     | 80 min    |
| fig8F.g       | 10 days   |
| fig9.g        | 25 min    |
| fig11A.g      | 4 min     |
| figS2A.g      | 12 min    |
| figS2BCDE.g   | 1 day     |
| figS2F.g      | 27 hrs    |
| figS2G.g      | 4 hrs     |
| figS2HIJK.g   | 120 days  |

To load the model scripts without demos, type

```
genesis DoiCaModel.g
```

All of the model parameters have notes in the scripts, which are identical to Supplemental Tables 1-3.

---

Tomoakazu Doi,
ATR Computational Neuroscience Labs,
26 Jan 2005

---

2025-05-27 – Standardized to Markdown.