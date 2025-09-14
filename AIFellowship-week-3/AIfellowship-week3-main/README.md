# Week 3 ——— Advanced Prompting: Zero-Shot, Few-Shot, and Chain-of-Thought (CoT)

This package includes:

Prompt templates (Zero-Shot, Few-Shot, CoT)
Experiment runner script (run_experiments.py)
Sample datasets (logic, math, reasoning, benchmark)
Evaluation rubric and scoring framework
Example report with sample results
Step-by-step instructions for reproducing experiments

## Quick start
1. Extract the archive and navigate into the project folder:
cd week03_advanced_prompting
2. Install the required dependencies:
```bash
pip install openai pandas tqdm
```
3. Set your OpenAI API key as an environment variable:
```bash
export OPENAI_API_KEY="sk-..."
```
4.Run the experiments (this will call the OpenAI API):
```bash
python run_experiments.py
```
Results will be saved in the results/ directory as CSV files.

If you prefer not to call the API, use the dry-run option to simulate runs with the sample dataset: `python run_experiments.py --dry-run`
 This will display example outputs and show how the pipeline works without sending API requests.