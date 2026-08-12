# Neural CBF from Expert Demonstrations (ICL)

Project page for [arXiv:2510.21560](https://arxiv.org/abs/2510.21560).

## Local preview

Open `index.html`, or:

```powershell
python -m http.server 8080
```

## Push to the org

```powershell
cd F:\websites\NeuralCBF-ICL
git init
git add .
git commit -m "Initial project page for arXiv 2510.21560"
git branch -M main
gh repo create TrustworthyAutonomy/NeuralCBF-ICL --public --source=. --remote=origin --push
```

Then enable **Settings → Pages → Source: GitHub Actions**.

Site URL: https://trustworthyautonomy.github.io/NeuralCBF-ICL/
