# Torch package with transformers

This example tries to package the transformers library with torch.package:

1. python3.8 -m venv venv

2. source venv/bin/activate

3. pip install --pre torch --extra-index-url https://download.pytorch.org/whl/nightly/cpu

4. pip install transformers==4.10 # netest version 4.18 shows issues when packaging urllib3

5. python model_export.py

6. python model_import.py