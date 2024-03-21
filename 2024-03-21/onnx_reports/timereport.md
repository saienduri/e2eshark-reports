Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/t5-large                          |      21.333 |        26.353 |       18.22  |          7.779 |       0     |
| pytorch/models/bert-large-uncased                |      17.426 |        16.909 |        9.367 |         12.511 |       0.667 |
| pytorch/models/mit-b0                            |       3.193 |         0.33  |        0.107 |          0.133 |       0     |
| pytorch/models/llama2-7b-GPTQ                    |     798.465 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-350m                          |      10.161 |        16.445 |        9.011 |          4.405 |       0     |
| pytorch/models/mobilebert-uncased                |       8.276 |         1.308 |        0.586 |          0.424 |       0     |
| pytorch/models/dlrm                              |      15.277 |        20.242 |       14.928 |          6.255 |       0     |
| pytorch/models/opt-1.3b                          |      42.436 |        48.698 |       37.857 |         15.602 |       0     |
| pytorch/models/whisper-base                      |       4.575 |         3.638 |        1.973 |          1.035 |       0     |
| pytorch/models/phi-2                             |      79.964 |       103.655 |       74.148 |         30.219 |       0     |
| pytorch/models/bge-base-en-v1.5                  |       7.574 |         5.601 |        3.487 |          5.661 |       0.268 |
| pytorch/models/miniLM-L12-H384-uncased           |       5.126 |         2.23  |        1.228 |          3.784 |       0.121 |
| pytorch/models/llama2-7b-hf                      |     220.001 |       305.567 |      214.667 |         75.113 |       0     |
| pytorch/models/phi-1_5                           |      53.919 |        54.24  |       38.273 |         15.898 |       0     |
| pytorch/models/t5-base                           |       9.824 |        10.057 |        5.775 |          2.818 |       0     |
| pytorch/models/bart-large                        |      13.443 |        11.138 |        6.685 |          3.251 |       0     |
| pytorch/models/vit-base-patch16-224              |       5.048 |         3.754 |        2.231 |          1.379 |       0     |
| pytorch/models/resnet50                          |       2.613 |         1.273 |        0.651 |          2.793 |       0.171 |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       5.522 |         4.418 |        2.766 |          1.654 |       0     |
| pytorch/models/whisper-medium                    |      15.857 |        17.877 |       10.373 |          5.105 |       0     |
| pytorch/models/opt-125M                          |       6.863 |         7.406 |        4.304 |          2.159 |       0     |
| pytorch/models/gpt2                              |       9.098 |         7.421 |        4.302 |          6.372 |       0.307 |
| pytorch/models/stablelm-3b-4e1t                  |       1.09  |         0     |        0     |          0     |       0     |
| pytorch/models/gemma-7b                          |       1.027 |         0     |        0     |          0     |       0     |
| pytorch/models/gpt2-xl                           |      54.137 |        17.886 |        0     |          0     |       0     |
| pytorch/models/opt-125m-gptq                     |       7.045 |         0     |        0     |          0     |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |       3.395 |         1.136 |        0.582 |          0.601 |       0     |
| pytorch/models/whisper-small                     |       9.962 |         7.413 |        4.328 |          2.171 |       0     |
