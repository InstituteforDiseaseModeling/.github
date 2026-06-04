# Institute for Disease Modeling

The Institute for Disease Modeling (IDM) is part of the Gates Foundation’s Global Health Division. More information about IDM and our research is available on our website at [idmod.org](https://www.idmod.org/).

IDM’s goal is to support global efforts to eradicate infectious diseases and achieve permanent improvements in health by developing, using, and sharing computational modeling tools and promoting quantitative decision-making. Data-driven approaches, including the development of dynamic models, statistical analysis, and the development and application of innovative algorithms, make fundamental contributions that inform primary research programs, intervention strategies, resource allocation, and other avenues of health care delivery.

## Resources

IDM provides many modeling tools to the broader global health community. Documentation for the tools is available at [docs.idmod.org](https://docs.idmod.org/). Contributions are welcome (see information provided in individual repositories for specific contributing guidelines). In addition to the tools and code provided here, IDM provides three broad frameworks for modeling disease transmission, each of which contain models for specific diseases or health conditions and are in their own GitHub organizations.

- **Starsim**: The Starsim framework is used for examining the spread of infectious disease in situations when the details of how an individual's immune system, and heterogeneity across immune systems, changes the answer to a particular research question. Use Starsim models when within-host biology, co-infection, or fine-grained intervention effects matter.

  Best suited for: HIV, TB, STIs, HPV, Family Planning, and other questions where individual-level details shape population dynamics.

  See [Starsim on GitHub](https://github.com/starsimhub/starsim).
  
- **LASER**: The LASER (Light Agent Spatial modeling for ERadication) framework is especially suited for modeling disease transmission where spatial connectivity and heterogeneity matters. Geographic location, human movement patterns, and the specifics of disease transmission dynamics are combined to answer questions about locations and populations most at risk.

  Best suited for: spatial spread, meta-population models, and large-population campaigns such as polio eradication or evaluation of vaccination campaigns.

  See [LASER on GitHub](https://github.com/laser-base).
  
- **EMOD**: EMOD (Epidemiological MODeling software) is IDM's longest-running modeling framework, designed for diseases where both individual traits or behaviors and regional context are important for transmission. It is especially well-developed for malaria, with detailed components for mosquito life cycles, climate, and malaria-specific interventions. EMOD is no longer actively maintained but remains available to use.

  Best suited for: malaria eradication strategy evaluations, vector control, and regional campaign planning.

  See [EMOD on GitHub](https://github.com/emod-hub).

