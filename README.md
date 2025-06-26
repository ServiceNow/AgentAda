<!-- 
### Evaluation

### File Connections
In the root of the project (research-raga directory) run this command:
```bash
export PYTHONPATH=$(pwd):$PYTHONPATH
```

#### Insights
```bash
python main.py -e insights
```

#### Skills
```bash
python main.py -e skills
```


### Data Generation
```bash
python main_gen.py
```
### Links to CSV file of Kaggle Bench

The questions, meta information, and goal are in `data` directory.

Batch 1: https://drive.google.com/file/d/1NF2VKPTwUW82oZwmypBXDg6HLtAtQ60U/view?usp=drivesdk

Batch 2: https://drive.google.com/file/d/1iBFOv4O6QUYUrguodnRU4rq-47GKl4Dr/view?usp=sharing

Batch 3: https://drive.google.com/file/d/13pOwQPhpKErSN9NBI4KjUUTMewC33pgL/view?usp=sharing

Batch 4: https://drive.google.com/file/d/12dIzjTG5LtA4azTj1UL1jfB0pkSBssqh/view?usp=sharing

Batch 5: https://drive.google.com/file/d/1x9f4ENEIjyn59mgBSHZdm3z40Dompght/view?usp=sharing

Batch 6: https://drive.google.com/file/d/1V317E3WCB20ilAdUixIf5eNY7JIWLFTP/view?usp=sharing

Batch 7: https://drive.google.com/file/d/1HxXmeQWjGdglEjnKdvedtdLgpvDAYok0/view?usp=sharing  -->

## AgentADA: An Advanced Data Analytics and Evaluation Framework

<center>
<img src="data/Agent_ADA.png" alt="Agent ADA Logo" width="500"/>
</center>

**Agent ADA** is a comprehensive evaluation and data analytics framework focused on insights generation and skills assessment.

## Features

- **Insights Generation**: Generate and evaluate data-driven insights
- **Skills Assessment**: Evaluate analytical capabilities
- **Batch Processing**: Support for processing multiple datasets
- **Interactive Visualization**: Using Gradio for question-answer-plot interactions
- **LLM Integration**: Advanced language model evaluation capabilities
- **Automated Goal Generation**: Smart goal setting and question generation
- **Data Encoding Management**: Specialized encoding conversion tools
- **Visualization Tools**: JSON-based visualization capabilities

## 📥 Installation

```bash
# Set Python Path in the project root
export PYTHONPATH=$(pwd):$PYTHONPATH
```

## 🚀 Usage

### 1. Insights Evaluation
```python
python main.py -e insights
```

### 2. Skills Evaluation
```python
python main.py -e skills
```

### 3. Data Generation
```python
python main_gen.py
```

## Dataset Resources

The framework includes extensive datasets organized in batches. Access the Kaggle Bench CSV files:

- [Batch 1](https://drive.google.com/file/d/1NF2VKPTwUW82oZwmypBXDg6HLtAtQ60U/view?usp=drivesdk)
- [Batch 2](https://drive.google.com/file/d/1iBFOv4O6QUYUrguodnRU4rq-47GKl4Dr/view?usp=sharing)
- [Batch 3](https://drive.google.com/file/d/13pOwQPhpKErSN9NBI4KjUUTMewC33pgL/view?usp=sharing)
- [Batch 4](https://drive.google.com/file/d/12dIzjTG5LtA4azTj1UL1jfB0pkSBssqh/view?usp=sharing)
- [Batch 5](https://drive.google.com/file/d/1x9f4ENEIjyn59mgBSHZdm3z40Dompght/view?usp=sharing)
- [Batch 6](https://drive.google.com/file/d/1V317E3WCB20ilAdUixIf5eNY7JIWLFTP/view?usp=sharing)
- [Batch 7](https://drive.google.com/file/d/1HxXmeQWjGdglEjnKdvedtdLgpvDAYok0/view?usp=sharing)

## Project Structure

```
agent-ada/
├── data/           # Dataset and resource files
├── prompts/        # Prompt templates and configurations
├── scripts/        # Utility scripts
├── src/           # Source code
└── main.py        # Main execution script
```

## Key Components

1. **LLM Evaluation** (`LLM_only_EVAL.py`): Evaluate Language Model performance
2. **Batch Generation** (`batch_generator.py`): Generate and process data batches
3. **Question-Answer-Plot Interface** (`gradio_QuesAnsPlot.py`): Interactive visualization
4. **Goal Generation** (`main_gen_goal.py`): Generate analytical goals
5. **Question Generation** (`main_gen_questions.py`): Generate analytical questions

<!-- ## Contributing

We welcome contributions! Please check our issues page or submit pull requests. -->

## Citation

```
@misc{abaskohi2025agentadaskilladaptivedataanalytics,
      title={AgentAda: Skill-Adaptive Data Analytics for Tailored Insight Discovery}, 
      author={Amirhossein Abaskohi and Amrutha Varshini Ramesh and Shailesh Nanisetty and Chirag Goel and David Vazquez and Christopher Pal and Spandana Gella and Giuseppe Carenini and Issam H. Laradji},
      year={2025},
      eprint={2504.07421},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2504.07421}, 
}
```

## 🤝 Contributing
Please check the outstanding issues and feel free to open a pull request.
For more information, please check out the [contributing guidelines](CONTRIBUTING.md) and [issue template](ISSUE_TEMPLATE.md).


## Acknowledgments

Developed and maintained by ServiceNow. Join our community to collaborate on advancing data analytics and evaluation frameworks. 

### Thank you!!