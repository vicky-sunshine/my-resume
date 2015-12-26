## Install

1. Install the latest official [wkhtmltopdf][1] binary for your platform.
2. Install [Json Resume][2] with `sudo npm install -g resume-cli`
3. `resume init` to build a new Json file
4. Fill in the `resume.json` file or use [Resume Editor][3], which provides a graphical interface for editing your resume.
5. After you have your json file done, you can use `resume export <Filename> --format <file format> --theme <theme>` to get your resume!!

## Example
In this Repository, I use

`resume export resume --format pdf --theme paper` to get my resume.pdf

`resume export resume --format html --theme kendall-fix` to get my resume.html

You can explore more themes at [Resume Editor][3], but notice that just a few theme is compatible with [wkhtmltopdf][1].


[1]: http://wkhtmltopdf.org/
[2]: http://jsonresume.org
[3]: http://registry.jsonresume.org/
