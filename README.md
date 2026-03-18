# ttsv2

## Installation

cuda >= 12.3.2

docker pull ghcr.io/chenying99/ttsv2:v1

docker container run --rm -it --gpus all --mount type=bind,source=$(pwd)/resources,target=/app/resources -p 8000:8000 ghcr.io/chenying99/ttsv2:v1
