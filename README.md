
# DeepSeek-R1: Next-Generation Local Reasoning Model 

Experience cutting-edge reasoning directly in your browser with **DeepSeek-R1**, a 1.5B parameter model powered by WebGPU. Everything runs locally with **no data sent to servers**, ensuring privacy and performance. Built with 🤗 **Transformers.js** and **ONNX Runtime Web**, it’s lightweight, offline-capable, and blazing-fast at **60 tokens per second**. More information can be found [here](https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf).

## Why DeepSeek-R1?

DeepSeek-R1 is designed for developers, researchers, and enthusiasts who need a fast, secure, and privacy-focused reasoning model. By running locally in your browser, DeepSeek-R1 eliminates server latency and ensures complete control over your data.

## Features

- **Local Execution**: Runs entirely in your browser—no external dependencies or server-side processing using php.
- **WebGPU Acceleration**: Leverages WebGPU for fast, efficient computation.
- **Offline Support**: Once loaded, you can use the model without an internet connection.
- **Privacy First**: All processing stays on your device.
- **Open Source**: Fully transparent, with source code available on [GitHub](https://github.com/iamgmujtaba/deepseek-r1).

Note: Code is tested on MacOS and Linux (Ubuntu). 

## Getting Started

Follow these steps to set up and run **DeepSeek-R1** locally.

### 1. Clone the Repository

Clone the project to your local machine:

```sh
git clone http://localhost:8000/
```

### 2️. Navigate to the Project Directory

Move into the project directory:

```sh
cd deepseek-r1
```


### 3. Start the Application Server

Start the local development server with:

```sh
bash run.sh
```

### 4. Example

https://github.com/user-attachments/assets/8ca9c2fa-5b92-401b-bf05-d041ee730504


The application will open automatically in your default web browser at `http://localhost:8000`.


## 🔗 Base Code Attribution

This project builds upon the excellent work available in the [Hugging Face Examples](https://github.com/huggingface/transformers.js-examples).


