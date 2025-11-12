# HUST Letter LaTeX Template

This is a LaTeX template for letters from **Huazhong University of Science and Technology (HUST)**.

## 🚀 How to Use

### Option 1: Overleaf (Recommended)

This is the easiest way to get started, as you do not need a local LaTeX installation.

* **[TODO: Once submitted]** [**Click here to use this template on Overleaf**](https://link-to-your-overleaf-template)
* **(For now)** You can download a `.zip` file of this repository and upload it to Overleaf via "New Project" -> "Upload Project".

### Option 2: Local Compilation

1.  **Get the files:**
    * Clone the repository: `git clone https://github.com/YourUsername/HUST-Letter-Template.git`
    * Or, download the `.zip` package.

2.  **Ensure all dependencies are present:**
    * Your main `.tex` file (e.g., `HUST_letter.tex`)
    * `HUST_blue.pdf` (The HUST logo, required)
    * `huster.png` (Your signature image, optional)

3.  **Customize your content:**
    Open the `.tex` file and edit the `CUSTOMIZABLE VARIABLES` section at the top:
    ```latex
    \newcommand{\senderName}{Your Name}
    \newcommand{\senderTitle}{School/Department of XXX}
    \newcommand{\senderInstitution}{Huazhong University of Science and Technology (HUST)}
    \newcommand{\senderPhone}{0000000000}
    \newcommand{\senderEmail}{yourname@hust.edu.cn}

    \newcommand{\recipientName}{Mr./Mrs.\ Name}
    \newcommand{\recipientTitle}{Title of Letter}
    \newcommand{\recipientInstitution}{Institute / Department / Company / ...}
    ```

4.  **Compile:**
    Compile the main `.tex` file using `pdflatex`.

## 🙏 Acknowledgements

* The structure and inspiration for this template come from [ViGeng/HKUSTGZ-letter-latex-template](https://github.com/ViGeng/HKUSTGZ-letter-latex-template). Thank you to the original author for their work.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
