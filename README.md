# markdown-to-pdf-sample
This project is a sample of automating the process of converting markdown to a pdf with styles.
It uses GitHub Actions to run pandoc and html5-to-pdf to convert [Sample.md](Sample.md) to a pdf file.
The Actions workflow defined in [ci.yml](.github/workflows/ci.yml) runs on each push to `master` and produces an artifact containing the pdf.
