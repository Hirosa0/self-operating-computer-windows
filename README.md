<h1 align="center">Self-Operating Computer Framework for Windows</h1>

<p align="center">
  <strong>A framework to enable multimodal models to operate a computer.</strong>
</p>
<p align="center">
  Using the same inputs and outputs of a human operator, the model views the screen and decides on a series of mouse and keyboard actions to reach an objective. 
</p>

<div align="center">
  <img src="https://github.com/OthersideAI/self-operating-computer/blob/main/readme/self-operating-computer.png" width="750"  style="margin: 10px;"/>
</div>

### Key Features
- **Compatibility**: Designed for various multimodal models.
- **Integration**: Currently integrated with **GPT-4v** as the default model.
- **Future Plans**: Support for additional models.

### Current Challenges
> **Note:** The GPT-4v's error rate in estimating XY mouse click locations is currently quite high. This framework aims to track the progress of multimodal models over time, aspiring to achieve human-level performance in computer operation.

### Ongoing Development
At [HyperwriteAI](https://www.hyperwriteai.com/), we are developing a multimodal model with more accurate click location predictions.

### Additional Thoughts
We recognize that some operating system functions may be more efficiently executed with hotkeys such as entering the Browser Address bar using `command + L` rather than by simulating a mouse click at the correct XY location. We plan to make these improvements over time. However, it's important to note that many actions require the accurate selection of visual elements on the screen, necessitating precise XY mouse click locations. A primary focus of this project is to refine the accuracy of determining these click locations. We believe this is essential for achieving a fully self-operating computer in the current technological landscape.
## Demo

https://github.com/OthersideAI/self-operating-computer/assets/42594239/9e8abc96-c76a-46fb-9b13-03678b3c67e0

## Quick Start Instructions
Below are instructions to set up the Self-Operating Computer Framework locally on your computer.

1. **Clone the repo** to a directory on your computer:
```
git clone https://github.com/OthersideAI/self-operating-computer-windows.git
```
2. **Cd into directory**:

```
cd self-operating-computer
```

3. **Create a Python virtual environment**. [Learn more about Python virtual environment](https://docs.python.org/3/library/venv.html).

```
python3 -m venv venv
```
4. **Activate the virtual environment**:
```
./venv/bin/activate
```
5. **Install the project requirements**:
```
pip install -r requirements.txt
```
6. **Install Project and Command-Line Interface**:
```
pip install .
```
7. **Then rename the `.example.env` file to `.env` so that you can save your OpenAI key in it.**
```
mv .example.env .env
``` 
8. **Add your Open AI key to your new `.env` file. If you don't have one, you can obtain an OpenAI key [here](https://platform.openai.com/account/api-keys)**:
```
OPENAI_API_KEY='your-key-here'
```
9. **Run it**!
```
operate
```


### Contributions are Welcomed! Some Ideas: 
- **Prompt Improvements**: Noticed any areas for prompt improvements? Feel free to make suggestions or submit a pull request (PR). 
- **Adding New Multimodal Models**: Integration of new multimodal models is welcomed. If you have a specific model in mind that you believe would be a valuable addition, please feel free to integrate it and submit a PR.
- **Framework Architecture Improvements**: Think you can enhance the framework architecture described in the intro? We welcome suggestions and PRs.

For any input on improving this project, feel free to reach out to me on [Twitter](https://twitter.com/josh_bickett).

### Follow HyperWriteAI for More Updates

Stay updated with the latest developments:
- Follow HyperWriteAI on [Twitter](https://twitter.com/HyperWriteAI).
- Follow HyperWriteAI on [LinkedIn](https://www.linkedin.com/company/othersideai/).

