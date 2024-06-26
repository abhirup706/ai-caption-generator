AI Image Caption Generator

This service uses Salesforce BLIP transformer models to auto generate captions for image data (in base64 format)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)


## Installation

Instructions for setting up the project locally.

```bash
git clone https://abhirup706@bitbucket.org/ecomchain/ai-caption-generator.git
cd ai-caption-generator
```

### Create a virtual ennvironment:
```bash
pip3 install virtualenv
virtualenv --version
virtualenv ai-generated-caption
source ai-generated-caption/bin/activate
```

### Install the requirements

```bash
pip3 install -r requirements.txt
(Note: installation of pytorch might need about 12 GB of disk space)
```

## Usage
Run the following command to start the service
```bash
python3 app.py
```
To run it as a daemon process in background, use command:
```bash
nohup python3 app.py &
```
