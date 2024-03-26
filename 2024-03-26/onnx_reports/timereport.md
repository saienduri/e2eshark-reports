Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/t5-large                          |      20.399 |        26.25  |       17.121 |          8.252 |       0     |
| pytorch/models/bert-large-uncased                |      16.372 |        16.854 |        9.362 |          8.449 |       0     |
| pytorch/models/mit-b0                            |       2.871 |         0.333 |        0.1   |          0.133 |       0     |
| pytorch/models/llama2-7b-GPTQ                    |     802.657 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-350m                          |      13.135 |        16.303 |        8.932 |          4.389 |       0     |
| pytorch/models/mobilebert-uncased                |       8.361 |         1.316 |        0.575 |          0.421 |       0     |
| pytorch/models/dlrm                              |      15.236 |        20.195 |       14.118 |          6.234 |       0     |
| pytorch/models/opt-1.3b                          |      43.03  |        48.749 |       35.92  |         15.676 |       0     |
| pytorch/models/whisper-base                      |       4.552 |         3.63  |        1.985 |          1.029 |       0     |
| pytorch/models/phi-2                             |     101.796 |       105.577 |       69.927 |         30.191 |       0     |
| pytorch/models/bge-base-en-v1.5                  |       7.77  |         5.607 |        3.501 |          5.637 |       0.275 |
| pytorch/models/miniLM-L12-H384-uncased           |       5.14  |         2.191 |        1.213 |          3.738 |       0.115 |
| pytorch/models/llama2-7b-hf                      |     220.502 |       260.09  |      184.258 |         74.69  |       0     |
| pytorch/models/phi-1_5                           |      53.763 |        54.037 |       36.401 |         15.826 |       0     |
| pytorch/models/t5-base                           |       9.553 |        10.013 |        5.758 |          2.814 |       0     |
| pytorch/models/bart-large                        |      13.085 |        11.065 |        6.695 |          3.232 |       0     |
| pytorch/models/vit-base-patch16-224              |       4.949 |         3.701 |        2.233 |          1.368 |       0     |
| pytorch/models/resnet50                          |       2.566 |         1.258 |        0.64  |          2.807 |       0.173 |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       5.592 |         4.404 |        2.764 |          1.649 |       0     |
| pytorch/models/whisper-medium                    |      21.882 |        17.738 |       10.392 |          5.084 |       0     |
| pytorch/models/opt-125M                          |       6.673 |         7.37  |        4.31  |          2.149 |       0     |
| pytorch/models/gpt2                              |       9.405 |         7.361 |        4.304 |          5.664 |       0.302 |
| pytorch/models/stablelm-3b-4e1t                  |       1.077 |         0     |        0     |          0     |       0     |
| pytorch/models/gemma-7b                          |       0.934 |         0     |        0     |          0     |       0     |
| pytorch/models/gpt2-xl                           |      53.735 |        59.092 |       41.004 |         39.49  |       2.381 |
| pytorch/models/opt-125m-gptq                     |       7.191 |         0     |        0     |          0     |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |       3.431 |         1.129 |        0.578 |          0.605 |       0     |
| pytorch/models/whisper-small                     |       8.073 |         7.402 |        4.334 |          2.168 |       0     |
