# LocalGPT

LocalGPT allows you to train a GPT model locally using your own data and access it through a chatbot interface.

## Installation

### Clone the repository:

```bash
$ git clone https://github.com/alesr/localgpt.git
$ cd localgpt
```

### Create a virtual environment:

```bash
$ pip3 install virtualenv
```

```bash
$ python3 -m venv env
```

```bash
$ source env/bin/activate
```

### Install the dependencies:

```bash
$ pip3 install -r requirements.txt
```

###Set the OpenAI API key as an environment variable:

```bash
$ export OPENAI_API_KEY=<your-api-key>
```

## Usage

Load files to train the model by adding them to the `data` folder located in the root of the project.

Then run the following command:

```bash
$ python3 localgpt.py
```

This will train the model and start the chatbot interface.
