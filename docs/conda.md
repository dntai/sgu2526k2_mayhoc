
deactivate
conda create --name ml2604 python ipykernel

activate ml2604

python -m ipykernel install --user --name=ml2604

python -m pip install Pillow
python -m pip install matplotlib
python -m pip install pandas seaborn joblib scikit-learn openpyxl
python -m pip install openpyxl