conda create --name poetry
conda activate poetry
conda install -c conda-forge poetry

poetry init
poetry add mkdocs-material

poetry install
poetry update

