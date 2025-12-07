### How to run vLLM locally and test bugs for inference optimization?
  - In the project folder `llm-demo/ ` run `python3 -m venv venv`, which generate a venv folder
    llm-demo/
      --vllm/
      --venv/
  - activate the python environment in venv
    `source venv/bin/activate`

  - make the vllm repo as editable environment
     `pip install -e vllm/`


### Run termimal in kaggle environment
- switch to script mode in notebook and into terminal console
- run ``` !git init ``` 
- run ``` !git clone https://github.com/pengw00/vllm-david-lab.git ```
- cd `vllm-david-lab/`
- `pip install -e .` to make the whole package Install the local version of the repo using the existing Python environment
   This ensures you are using the optimized, pre-configured environment provided by Kaggle while still running your specific vLLM code from the local     repository.
   You will see output stream: The terminal will immediately start displaying text showing the steps:
    ```
    Obtaining file:///kaggle/working/vllm-david-lab
    Collecting package-name...
    Downloading...
    Installing collected packages: package-name, ...
    ```
- `pip show vllm` to Verifying a Successful Installation
    
