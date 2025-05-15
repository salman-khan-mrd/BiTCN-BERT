

## Installation

You can install  with:

```python
pip install 
```

or 

```python
conda install -c conda-forge neuralforecast
``` 
Vist our [Installation Guide](https://nixtlaverse.nixtla.io/neuralforecast/docs/getting-started/installation.html) for further details.



## Why? 

There is a shared belief in Neural forecasting methods' capacity to improve forecasting pipeline's accuracy and efficiency.

Unfortunately, available implementations and published research are yet to realize neural networks' potential. They are hard to use and continuously fail to improve over statistical methods while being computationally prohibitive. For this reason, we created, a library favoring proven accurate and efficient models focusing on their usability.

## Features 

* Fast and accurate implementations of more than 30 state-of-the-art models. See the entire [collection here](https://nixtlaverse.nixtla.io/neuralforecast/docs/capabilities/overview.html).
* Support for exogenous variables and static covariates.
* Interpretability methods for trend, seasonality and exogenous components.
* Probabilistic Forecasting with adapters for quantile losses and parametric distributions.
* Train and Evaluation Losses with scale-dependent, percentage and scale independent errors, and parametric likelihoods.
* Automatic Model Selection with distributed automatic hyperparameter tuning.
* Familiar sklearn syntax: `.fit` and `.predict`.

## Highlights

* Official `NHITS` implementation, published at AAAI 2023. See [paper](https://ojs.aaai.org/index.php/AAAI/article/view/25854) and [experiments](./experiments/).
* Official `NBEATSx` implementation, published at the International Journal of Forecasting. See [paper](https://www.sciencedirect.com/science/article/pii/S0169207022000413).
* Unified with`StatsForecast`, `MLForecast`, and `HierarchicalForecast` interface `NeuralForecast().fit(Y_df).predict()`, inputs and outputs.
* Built-in integrations with `utilsforecast` and `coreforecast` for visualization and data-wrangling efficient methods.
* Integrations with `Ray` and `Optuna` for automatic hyperparameter optimization.
* Predict with little to no history using Transfer learning. Check the experiments [here](https://github.com/Nixtla/transfer-learning-time-series).

Missing something? Please open an issue or write us in [![Slack](https://img.shields.io/badge/Slack-4A154B?&logo=slack&logoColor=white)](https://join.slack.com/t/nixtlaworkspace/shared_invite/zt-135dssye9-fWTzMpv2WBthq8NK0Yvu6A)

## Examples and Guides

The [documentation page](https://nixtlaverse.nixtla.io/neuralforecast/docs/getting-started/introduction.html) contains all the examples and tutorials.

📈 [Automatic Hyperparameter Optimization](https://nixtlaverse.nixtla.io/neuralforecast/docs/capabilities/hyperparameter_tuning.html): Easy and Scalable Automatic Hyperparameter Optimization with `Auto` models on `Ray` or `Optuna`.

🌡️ [Exogenous Regressors](https://nixtlaverse.nixtla.io/neuralforecast/docs/capabilities/exogenous_variables.html): How to incorporate static or temporal exogenous covariates like weather or prices.

🔌 [Transformer Models](https://nixtlaverse.nixtla.io/neuralforecast/docs/tutorials/longhorizon_transformers.html): Learn how to forecast with many state-of-the-art Transformers models.

👑 [Hierarchical Forecasting](https://nixtlaverse.nixtla.io/neuralforecast/docs/tutorials/hierarchical_forecasting.html): forecast series with very few non-zero observations. 

👩‍🔬 [Add Your Own Model](https://nixtlaverse.nixtla.io/neuralforecast/docs/tutorials/adding_models.html): Learn how to add a new model to the library.

