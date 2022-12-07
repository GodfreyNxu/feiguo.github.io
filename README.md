# About Me

I am an assistant professor in Economics at Ningxia University in Yinchuan, China. I hold a double-PhD degree in Economics at City University of Hong Kong and Xi'an Jiaotong University.

My main research interests are fiscal and monetary policies, international finance, international investment, and financial development.

You can find my CV here.

# Publications
Fei GUO #, Isabel Kit-Ming YAN, Tao CHEN, Chun-Tien HU (2023). Fiscal multipliers, monetary efficacy, and hand-to-mouth households. Journal of International Money and Finance, 130, 102743 (forthcoming)[(download)](https://www.sciencedirect.com/science/article/pii/S0261560622001462).

Fei GUO, Shi HE #, Zhitao LIN, Lu YUE (2022). Truths and Myths About the Effect of Financial Development on Economic Growth in China: A Meta-Analysis. Emerging Markets Finance and Trade, 1-18[(download)](https://www.tandfonline.com/doi/abs/10.1080/1540496X.2022.2136940).

Maoxi Tian, Fei GUO #, Rong NIU (2022). Risk spillover analysis of China's financial sectors based on a new GARCH copula quantile regression model. The North American Journal of Economics and Finance, 63, 101817[(download)](https://www.sciencedirect.com/science/article/pii/S1062940822001528).

Fei GUO #, Eric Evans Osei OPUKU, Kate HYNES, Isabel Kit-Ming YAN (2021). Fiscal Decentralization and Fiscal Multiplier in China, The B E Journal of Macroeconomics, 22(2), 729-763[(download)](https://www.degruyter.com/document/doi/10.1515/bejm-2020-0275/html).

Fei GUO, Eric Evans Osei OPUKU, Isabel Kit-Ming YAN # (2021). The heterogeneous sectoral productivity impacts of FDI on real exchange rate, Journal of International Trade & Economic Development, 30(7), 1101-1121[(download)](https://www.tandfonline.com/doi/abs/10.1080/09638199.2021.1936135).

Fei GUO, Shi HE # (2020). The finance-growth nexus in China: a meta-analysis. Applied Economics Letters, 27(13), 1071-1075[(download)](https://www.tandfonline.com/doi/abs/10.1080/13504851.2019.1659926).

# Teaching
Mid-Level Macroeconomics for Undergraduates

International Finance for Undergraduates

Development Economics for Postgraduates

Fiscal Research for Postgraduates














A Github Pages template for academic websites. This was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

I think I've got things running smoothly and fixed some major bugs, but feel free to file issues or make pull requests if you want to improve the generic template / theme.

### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. 

# Instructions

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://academicpages.github.io/

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

# Changelog -- bugfixes and enhancements

There is one logistical issue with a ready-to-fork template theme like academic pages that makes it a little tricky to get bug fixes and updates to the core theme. If you fork this repository, customize it, then pull again, you'll probably get merge conflicts. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch. 

To support this, all changes to the underlying code appear as a closed issue with the tag 'code change' -- get the list [here](https://github.com/academicpages/academicpages.github.io/issues?q=is%3Aclosed%20is%3Aissue%20label%3A%22code%20change%22%20). Each issue thread includes a comment linking to the single commit or a diff across multiple commits, so those with forked repositories can easily identify what they need to patch.
