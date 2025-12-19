# RenderCV Project: Sardak Serhii

This repository contains the source files for generating my CV using [RenderCV](https://github.com/sinaatalay/rendercv).

## Project Structure

*   `Sardak_Serhii_RenderCV.yaml`: The main configuration file containing all the CV data (experience, education, skills, etc.).
*   `.gitignore`: Prevents temporary build files and generated PDFs from being tracked.

## How to Usage

To generate the CV in PDF and LaTeX formats, follow these steps:

### 1. Install RenderCV
If you haven't installed RenderCV yet, you can do so via pip:

```bash
pip install rendercv
```

### 2. Generate the CV
Run the following command in the terminal from the project root:

```bash
rendercv render Sardak_Serhii_RenderCV.yaml
```

### 3. Output
After running the command, a folder named `rendercv_output` will be created (if it doesn't exist) containing:
*   `Sardak_Serhii_RenderCV.pdf`
*   `Sardak_Serhii_RenderCV.tex`
*   Other auxiliary files.

## Customization
You can edit the `Sardak_Serhii_RenderCV.yaml` file to update your information. RenderCV will automatically reflect the changes the next time you run the `render` command.
