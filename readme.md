# Quasi-normal Mode Analysis of Black Hole Ringdown
- In this coursework, I fit a QNM solution to the ringdown of a black hole merger event using Bayesian inference on the parameters.
- The likelihood used is verified by analysing the properties of the noise.
- A consistency test on the predictions of GR is performed.

## Repository Structure
- This is a very simple repository.
```
A5-Gravitational-Waves-QNM-Fitting-CW/
├── data/
│   ├── data.dat        # time-domain strain data from the black hole ringdown
│   └── psd.dat         # power spectral density of the detector noise
├── solutions.ipynb     # main notebook: noise analysis, QNM fitting, GR consistency test
├── plateau.png         # convergence/plateau diagnostic plot
├── requirements.txt    # Python dependencies
├── report.pdf              # The delicious report
├── LICENSE
└── readme.md
```

## Solutions
- All the solutions to the questions are in the solutions.ipynb
- When running this, please be warned that I did an extension analysing the $t_0$ at slight perturnbations. This takes several hours to run; as such, it might be better not to run this section. It is at the very bottom and should not affect the rest of the analysis: best not use the "run all" button.
- Q9 is written in the report in more detail.

## Setup
- There is a requirements.txt provided to deal with all the dependencies.
```
# Clone the repo
git clone https://gitlab.developers.cam.ac.uk/phy/data-intensive-science-mphil/assessments/a5_coursework/zyw26.git

# Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Then run the notebook!
```

## Autogeneration Usage 
LLMs, specifically Claude, were used to support this coursework. They were used to debug code, improve code efficiency and help with some of the more esoteric Matplotlib functions. THE ANALYSIS IS MY OWN.