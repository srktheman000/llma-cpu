# llma-cpu

## How To run ?

### step 1:

clone the repository 

``` bash
git clone https://github.com/srktheman000/llma-cpu.git
```


### step 2:

create a virtual enviornment

``` bash
conda create -n llma-cpu python=3.8 -y 
```

``` bash
conda  activate llma-cpu
```

``` bash
pip install -r requirements.txt
```

``` bash
python app.py
```


### Download the quantize model from the link provided in model folder & keep the model in the model directory:

```ini
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```