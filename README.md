# DVLT
DVLT: Decoupled Vision-Language Transformer for End-to-End Container Marking Text spotting

Requirement
python=3.8
pytorch=1.10.1
torchvision=0.11.0
transformers=4.22.0
detectron2=0.6

Train
python tools/train_net.py --config-file CONFIG_FILE

Eval
python tools/train_net.py --config-file CONFIG_FILE --eval-only
