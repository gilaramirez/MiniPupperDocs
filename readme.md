# Mini Pupper - ROS, OpenCV, Open-source, Pi Robot Dog
Mini Pupper will make robotics easier for schools, homeschool families, enthusiasts and beyond.

「Mini Pupperは、学校、家庭学習、愛好家、そしてそれ以外の人々にも、ロボット工学をより身近なものにしてくれることでしょう」 by MangDang

## Sphinx Document Buildling

This document is written in [reStructuredText](https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html), designed following Sphinx practice, and hosted on [Read the Docs](https://mangdang-minipupperdocs.readthedocs-hosted.com/).

This document can also be built locally, where the following environment setup would be initially required:

```bash
# It is a good moment to create a Python virtual environment.
sudo apt-get install python3-venv
python -m venv .venv

source ./.venv/bin/activate
# When in fish shell environment
source ./.venv/bin/activate.fish

# Install Python requirements
pip3 install -r requirements.txt
```

Then the following commands can build a result of HTML documents to view in browsers directly:
```bash
cd ./docs
make rtd
# make rtd-ja
```

Now the build result files can be opened from `docs/_build/html`.
