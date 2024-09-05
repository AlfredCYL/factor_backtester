# FactorAnalyser

FactorAnalyser is a powerful toolkit designed to analyze cross-sectional factors and optimize alpha strategies. It comprises two core components: **FactorBacktester** and **FactorFactory**, each providing essential functionalities for comprehensive factor analysis.

## FactorBacktester

FactorBacktester is dedicated to backtesting cross-sectional factors. Key features include:
- Computing rankICs, quantile returns, and factor returns through various methods.
- **Planned Enhancements**:
  1. **Risk Evaluation Module**: Implement a risk assessment framework (e.g., Barra) to evaluate factor risks.
  2. **Base Correlation Integration**: Add correlation analysis with baseline factors to improve model robustness.
  3. **IC Attenuation Testing**: Develop lead-lag tests to measure IC variation over time, evaluating IC attenuation over n days.

## FactorFactory

FactorFactory is designed to streamline the creation and management of cross-sectional factors. It is tightly integrated with FactorBacktester, offering advanced capabilities for factor refinement and analysis.

## Example

For detailed usage, please refer to the [functional demo](Functional%20Demo.ipynb) included in the repository.

## License

This project is released under the [MIT License](LICENSE). Please note that **FactorAnalyser** is still in active development, and feedback or contributions are welcome!