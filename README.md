# website

Personal website generator powered by [Pelican](https://getpelican.com/). The result is published [here](https://toyat522.github.io/) along with the [GitHub Pages repository](https://github.com/toyat522/toyat522.github.io).

## Setup

Clone this repository and initialize submodules:
```
git clone git@github.com:toyat522/website.git
git submodule update --init --recursive
```

Create a virtual environment and install pelican:
```
python -m venv venv
pip install "pelican[markdown]"
```

## Usage

Generate the website:
```
pelican content
```

Preview the website:
```
pelican --listen
```
