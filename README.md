# Examples

Files you can drop onto [tinidrop.com](https://tinidrop.com).

| Path | |
| --- | --- |
| [`sweetdelight.html`](sweetdelight.html) | Single HTML file. Upload as a file. Contact on the page: santoshadhikaripremi@gmail.com |
| [`sweet-delights/`](sweet-delights/) | Same site as a folder with `index.html`. Zip it, or upload the folder, to publish as a website. |
| [`nda-mutual.pdf`](nda-mutual.pdf) | Mutual NDA. Disclosing party: Santosh Premi Adhikari (`santoshadhikaripremi@gmail.com`). Receiving party: `test-pro@tinidrop.com`. Sample for demos, not legal advice. |

```bash
tinidrop deploy ./sweetdelight.html --slug sweet-delights-file
tinidrop deploy ./sweet-delights --slug sweet-delights
tinidrop deploy ./nda-mutual.pdf --slug nda
```
