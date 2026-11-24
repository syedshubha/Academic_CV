# Syed Emad Uddin Shubha

| Document | Latest PDF | LaTeX source |
| --- | --- | --- |
| Academic CV | [View CV](https://syedshubha.com/assets/Curriculum_Vitae_Syed_Emad_Uddin_Shubha.pdf) | [CV_Shubha.tex](CV_Shubha.tex) |
| One-page résumé | [View résumé](https://syedshubha.com/assets/Resume_Syed_Emad_Uddin_Shubha.pdf) | [Resume_Shubha.tex](Resume_Shubha.tex) |

## Publish an update from Overleaf

1. Edit and recompile the document in Overleaf.
2. Open **Integrations → GitHub → Push Overleaf changes to GitHub** and click **Sync**.
3. The [Publish documents workflow](https://github.com/syedshubha/Academic_CV/actions/workflows/publish-documents.yml) compiles both sources with pdfLaTeX. The website opens the latest published PDFs in new tabs. If a build fails, the links keep serving the last successful pair.

Each [release](https://github.com/syedshubha/Academic_CV/releases) lists the source commit used to build its PDFs. To compile locally, run `pdflatex` twice on the desired source so LaTeX can resolve references and page counts.
