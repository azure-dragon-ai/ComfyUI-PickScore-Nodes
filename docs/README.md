```shell
https://github.com/Zuellni/ComfyUI-PickScore-Nodes
https://github.com/azure-dragon-ai/ComfyUI-HPSv2-Nodes
https://gitee.com/luomor/ComfyUI-HPSv2-Nodes
hpsv2
https://pypi.org/simple

set HF_ENDPOINT=https://hf-mirror.com
set HPS_ROOT=c:\Work\AI-Service\Score\HPSv2\HPSv2Models
.\python_embeded\python.exe -s ComfyUI\main.py --windows-standalone-build --cuda-device=0 --listen=[2408:8207:60ad:6cb0::6aa] --port=20002 --output-directory=\\NAS65A682\Web\images\test

pip install transformers==4.25.1
transformers                 4.34.1

https://github.com/azure-dragon-ai/ComfyUI-ClipScore-Nodes
https://gitee.com/luomor/ComfyUI-ClipScore-Nodes
```

```python
# Opencv读入的是 h w c 其中w是宽，h是高，c是通道数
numpy = tensor.numpy()
image = Image.fromarray(numpy)

transform = torchvision.transforms.Compose([  
    transforms.ToTensor()])  
tensor = transform(image)
```