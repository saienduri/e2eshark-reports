Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/t5-large                          |      20.259 |        26.181 |       18.37  |          7.774 |       0     |
| pytorch/models/bert-large-uncased                |      15.356 |        16.888 |        9.331 |         13.471 |       0.669 |
| pytorch/models/mit-b0                            |       2.848 |         0.332 |        0.101 |          0.136 |       0     |
| pytorch/models/llama2-7b-GPTQ                    |     141.574 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-350m                          |      16.246 |        16.395 |        8.981 |          4.409 |       0     |
| pytorch/models/mobilebert-uncased                |       8.056 |         1.344 |        0.585 |          0.422 |       0     |
| pytorch/models/dlrm                              |      15.273 |        20.229 |       14.94  |          6.26  |       0     |
| pytorch/models/opt-1.3b                          |      27.124 |        48.527 |       37.858 |         15.651 |       0     |
| pytorch/models/whisper-base                      |       4.513 |         3.629 |        1.981 |          1.035 |       0     |
| pytorch/models/phi-2                             |     100.912 |       103.216 |       74.256 |         30.253 |       0     |
| pytorch/models/bge-base-en-v1.5                  |       7.507 |         5.59  |        3.488 |          5.604 |       0.268 |
| pytorch/models/miniLM-L12-H384-uncased           |       5.077 |         2.225 |        1.217 |          3.743 |       0.12  |
| pytorch/models/llama2-7b-hf                      |     218.541 |       442.881 |      313.671 |         75.142 |       0     |
| pytorch/models/phi-1_5                           |      53.019 |        54.29  |       38.544 |         15.839 |       0     |
| pytorch/models/t5-base                           |       9.711 |         9.957 |        5.762 |          2.807 |       0     |
| pytorch/models/bart-large                        |      13.37  |        10.949 |        6.657 |          3.225 |       0     |
| pytorch/models/vit-base-patch16-224              |       4.883 |         3.713 |        2.215 |          1.377 |       0     |
| pytorch/models/resnet50                          |       2.595 |         1.259 |        0.649 |          2.769 |       0.174 |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       5.567 |         4.371 |        2.761 |          1.645 |       0     |
| pytorch/models/whisper-medium                    |      21.252 |        17.659 |       10.317 |          5.082 |       0     |
| pytorch/models/opt-125M                          |       9.678 |         7.365 |        4.301 |          2.144 |       0     |
| pytorch/models/gpt2                              |       9.23  |         7.361 |        4.284 |          5.654 |       0.299 |
| pytorch/models/stablelm-3b-4e1t                  |       1.05  |         0     |        0     |          0     |       0     |
| pytorch/models/gemma-7b                          |       1.093 |         0     |        0     |          0     |       0     |
| pytorch/models/gpt2-xl                           |      53.103 |        59.098 |       43.604 |         39.115 |       2.373 |
| pytorch/models/opt-125m-gptq                     |      10.672 |         0     |        0     |          0     |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |       3.283 |         1.125 |        0.579 |          0.601 |       0     |
| pytorch/models/whisper-small                     |       9.931 |         7.4   |        4.303 |          2.167 |       0     |
