# ModelScout

**ModelScout** is a command-line tool designed to help users pick the best LLM for their needs. Modelscout uses a similar recommendation algorithm as to the beta version of [Macros On Demand](https://github.com/Hadi-M-Ibrahim/Macros-On-Demand) a more in-depth example of my SWE work. While ModelScout is simple it serves as a useful stop-gap in the quickly evolving field of LLMs. As the name suggests ModelScout is simply a scout and should serve as the beginning, not the end of your LLM search.

Subjective metrics such as performance and the degree to which a model is supported are gathered from various sources and forums (ie. Benchmarks, Reddit, Google trends. etc) and are based largely on community sentiment so should be taken with a grain of salt. Further note the cost per million tokens for open source models are very rough estimates with varying accuracy.

---

## Installation

Ensure you have Python installed, then install ModelScout using pip:

```sh
pip install modelscout
```

Alternatively, clone the repository manually:

```sh
git clone https://github.com/Hadi-M-Ibrahim/ModelScout.git
cd ModelScout
```

For installation details, visit the [ModelScout PyPI page](https://pypi.org/project/modelscout/).

---

## Command-Line Arguments

| Argument                         | Description                                                 |
| -------------------------------- | ----------------------------------------------------------- |
| `file` (Default: `./models.csv`) | Path to the CSV file                                        |
| `--scout`                        | Launch interactive mode for selecting filters (Recommended) |
| `--top`                          | Number of recommended models to display (5 by default)      |
| `--license`                      | Ideal license (1 for open source, 0 for no preference)      |
| `--performance`                  | Ideal performance rating (1.0-10.0)                         |
| `--cost`                         | Ideal cost per million tokens                               |
| `--context_length`               | Ideal context length                                        |
| `--Support`                      | Ideal API/tools availability (1.0-10.0)                     |

For implemtion details, visit the [ModelScout Github Repo](https://github.com/Hadi-M-Ibrahim/ModelScout).

---

## CSV format

```
Model Name,Company,Context Length,Cost per Million Tokens,Performance,license,Support
```
