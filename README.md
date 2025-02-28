# ModelScout

**ModelScout** is a command-line tool designed to help users filter and analyze AI models from a CSV dataset. It provides flexible filtering options and an interactive mode for ease of use. Modelscout uses the same recommendation algorithm as [Macros On Demand](https://github.com/Hadi-M-Ibrahim/Macros-On-Demand) a great example of my SWE work. 


---

## Features
- **Interactive filtering**: Easily select filters step by step.
- **Customizable**: Filter models by company, cost, performance, context length, and API/tool availability.
- **Lightweight & Easy to Use**: Requires only Python and a CSV file.

---

##  Command-Line Arguments

| Argument | Description |
|----------|-------------|
| `file` (Default: `./models.csv`) | Path to the CSV file |
| `-find` | Launch interactive mode for selecting filters (Recommended) |
| `--company` | Filter by company name |
| `--min_performance` | Minimum performance rating (1.0-10.0) |
| `--max_cost` | Maximum cost per token |
| `--min_context_length` | Minimum context length |
| `--min_api_tools` | Minimum API/tools availability (1.0-10.0) |

---

## Installation

Ensure you have Python installed, then install ModelScout using pip:

```sh
pip install git+https://github.com/yourusername/ModelScout.git
```

Alternatively, clone the repository manually:

```sh
git clone https://github.com/yourusername/ModelScout.git
cd ModelScout
```
