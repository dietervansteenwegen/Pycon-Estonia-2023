# Call for proposals

[Online form](https://pyconestonia.typeform.com/to/hBOEtTQ3?typeform-source=pycon.ee)

## What would be the title of your talk?

Starting with Python as part of a big project - things I wish my parents would have taught me.

## What category should we consider your talk for?

```plaintext
Regular talk (30 min) or Lightning talk (10 min).
```

-> Lightning talk or possibly regular talk

## What should be the level of your audience to understand the talk?

```plaintext
* Beginner
* Intermediate
* Advanced
* All levels
```

-> All levels

## Can you describe the content of your talk?

```plaintext
This abstract will be seen by organizers while making the selection and may eventually be seen on conference website and other public materials. Include how you would structure it, what kind of examples if any you'd use and other relevant info.
```

About 6 years ago I was -unexpectedly- hired to design a robotic system that could make offshore measurements for satellite validation. I'd have to do hardware, software and electronics all by myself. I was delighted. I'd have the freedom and resources to create my own hardware and electronics and build something useful with it.

Rather inconveniently I also had little programming experience. None, actually.

I got a couple of beginners' books on Python and started with lots of good intentions. Six years later the system has been named "Panthyr" and has grown into a working system with multiple measurement stations set up around Europe and partial project funding by ESA. It's been quite a (bumpy) journey learning Python and getting everything working on an embedded platform with limited resources.

There are plenty of things I wish I would have read in beginners' books early in my journey, some as simple as using `pdb` to debug or the `logging` module instead of `print`, others more advanced such as adding type hints for myself or using Sphinx to auto-create documentation. I'd like to share some of the tricks and habits I figured out along the way as well as mistakes and bad choices I've made along the way...

## Have you delivered this talk before at any other conference?

No, but I have presented the Panthyr system at the INMARTECH 2018 Symposium, North Falmouth, USA. In that presentation I already discussed a couple of things I wish I'd have done differently or started doing more quickly.

Furthermore, the Panthyr system itself has been presented at a couple of scientific conferences, though without any specific attention to the software. See https://www.vliz.be/nl/imis?module=person&persid=34772 for some references.

## Can you provide references or additional information about the talk you've proposed?

* Most of the code is in public repositories on Github (https://www.github.com/panthyr)
* There is a (very outdated) paper on the system itself: Vansteenwegen D, Ruddick K, Cattrijsse A, Vanhellemont Q, Beck M. The Pan-and-Tilt Hyperspectral Radiometer System (PANTHYR) for Autonomous Satellite Validation Measurements—Prototype Design and Testing. Remote Sensing. 2019; 11(11):1360. <https://doi.org/10.3390/rs11111360>

## Notes for the selection committee

```plaintext
Notes will only be seen by selection committee while making the selection. This is where you should explain things such as why you're the best person to speak on this topic etc.
```

First of all, I selected a 30 minute talk, but a 10 minute talk would be very possible as well and maybe even better. Hard to judge.

While a lot of great talks and books about Python in general (and data science specifically) are available, there are much less about using Python to control hardware, working on limited systems and keeping your project maintainable. I am convinced that it would be helpful to teach about things like logging, type annotations, packaging and using version control early on in a beginners journey instead of treating them as "advanced topics".

I started my project without any experience or clear vision. After four years and working prototypes proving their worth while making scientific measurements in Italy and Belgium, I decided I couldn't live with the mess and quality of the packages I had created and started rewriting and restructuring everything. That has been a huge task but -looking back at it- very rewarding. I wish someone would have taught me early on some of the things I came up with along the way which would have helped tremendously. I have a young colleague that started just a year ago and seeing him struggle on the same points as I did made me think that there might be some things I can share that could help others...

## Discussion points

* Installing as editable package
* pdb
* ptpython/bpython
* venv
* using type annotations when starting out
* logging module
* git branches (develop/master-or-main)
* linters/pre-commit hooks
* docstrings sphinx
* create a blank repo with instructions for yourself