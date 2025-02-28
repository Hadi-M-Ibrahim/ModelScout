# ModelScout

ModelScout is a command-line tool designed to help users filter and analyze AI models from a CSV dataset. It provides flexible filtering options and an interactive mode for ease of use.

## Command-Line Arguments

- `file` (Default: ./models.csv): Path to the CSV file.
- - `-find`: Interactively select filters.
- `--company`: Filter by company name.
- `--min_performance`: Minimum performance rating (1.0-10.0).
- `--max_cost`: Maximum cost per token.
- `--min_context_length`: Minimum context length.
- `--min_api_tools`: Minimum API/tools availability (1.0-10.0).


## Installation
Ensure you have Python installed, then install ModelScout easily using pip:
pip install git+https://github.com/yourusername/ModelScout.git

Alternatively, you can clone the repository manually:
git clone https://github.com/yourusername/ModelScout.git
cd ModelScout

#Interactive Mode (Recommended)
Use the -find argument to be guided through selecting filtering options interactively:
modelscout models.csv -find


