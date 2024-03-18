
## Installation

To install and run the app boilerplate, follow these steps:

1. Clone this repository to your local machine:

```shell
git clone https://github.com/alejandro-ao/qdrant-cloud-app.git
```

2. Change into the project directory:

```shell
cd qdrant-cloud-app
```

3. Install the required Python packages using pip:

```shell
pip install -r requirements.txt
```

## Configuration

To configure the app

1. Copy the `.env.example` file and rename it to `.env`:

```shell
cp .env.example .env
```

2. Add the `.env` file in a text editor and provide your Qdrant Managed Cloud Service and OpenAI   credentials:

```plaintext
OPENAI_API_KEY=

QDRANT_HOST=
QDRANT_API_KEY=
QDRANT_COLLECTION_NAME=
```

## Usage

 you can run the app:

```shell
streamlit run app.py
```
