Code to demonstrate how a mix of regex processing and AI can be used to extract ISO codes and form numbers from a commercial insurance policy pdf. 

MIT license.

Prerequisites:
- Install Tesseract for OCR `brew install tesseract`
- Create a local .env file with a valid OpenAI API key

Instructions:
1. Create a virtual environment 
2. Activate it and install everything in requirements.txt
3. Open the Jupyter notebook `extract_policy_codes.ipynb` and select the virtual environment as the kernel
4. Run various example pdfs following the notebook
5. For some example pdfs, ground truth is available in the `examples/ground_truth` folder. This can be used to manually evaluate results. 


