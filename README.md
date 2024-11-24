
# PowerPoint Text Extractor

This Python script extracts text from a PowerPoint (.pptx) file and writes it to a text file (.txt).
Each slide's content is separated by '------------------'.

## Prerequisites

Make sure you have Python installed on your system. You can check by running:
```bash
python --version
```

### (Optional) Create a Virtual Environment

Using a virtual environment is recommended to isolate dependencies. Here's how to set one up:

#### On Windows:
1. Create a virtual environment:
   ```bash
   python -m venv env
   ```

2. Activate the virtual environment:
   ```bash
   env\Scripts\activate
   ```

#### On macOS/Linux:
1. Create a virtual environment:
   ```bash
   python3 -m venv env
   ```

2. Activate the virtual environment:
   ```bash
   source env/bin/activate
   ```

3. Install the required library within the virtual environment:
   ```bash
   pip install python-pptx
   ```

## Installation

1. Install the required library:
   ```bash
   pip install python-pptx
   ```

   If you have multiple Python versions, use:
   ```bash
   python3 -m pip install python-pptx
   ```

2. Clone or download this script to your local machine.

## Usage

Run the script from the command line with the following syntax:
```bash
python extract_ppt_text.py <input_pptx_file> <output_txt_file>
```

### Example:
```bash
python extract_ppt_text.py presentation.pptx output.txt
```

- `<input_pptx_file>`: The PowerPoint file you want to process.
- `<output_txt_file>`: The file where the extracted text will be saved.

## Output Format

The text file will have the following structure:
```
Slide 1:
<content of slide 1>
------------------
Slide 2:
<content of slide 2>
------------------
```

## Common Issues

- **ModuleNotFoundError: No module named 'pptx'**  
  Make sure you have installed the `python-pptx` library using pip. If the issue persists, check your Python and pip versions.

## License

This script is open-source and free to use.
