# udacity_code_projects
This is a repo for my udacity code projects

## Some important commands while using github
* git clone <https://your_repo>
* git add <your_file.py>
* git commit -m "message describing what this commit means"
* git push
* git checkout -b
* git branch
* git status


# Questions for a Code Review

## Questions to Ask Yourself when Conducting a Code Review
First, let's look over some of the questions we might ask ourselves while reviewing code. These are drawn from the concepts covered throughout this course.

* Is the code clean and modular?
    * Can I understand the code easily?
    * Does it use meaningful names and whitespace?
    * Is there duplicated code?
    * Can I provide another layer of abstraction?
    * Is each function and module necessary?
    * Is each function or module too long?
* Is the code efficient?
    * Are there loops or other steps I can vectorize?
    * Can I use better data structures to optimize any steps?
    * Can I shorten the number of calculations needed for any steps?
    * Can I use generators or multiprocessing to optimize any steps?
* Is the documentation effective?
    * Are inline comments concise and meaningful?
    * Is there complex code that's missing documentation?
    * Do functions use effective docstrings?
    * Is the necessary project documentation provided?
* Is the code well tested?
    * Does the code high test coverage?
    * Do tests check for interesting cases?
    * Are the tests readable?
    * Can the tests be made more efficient?
* Is the logging effective?
    * Are log messages clear, concise, and professional?
    * Do they include all relevant and useful information?
    * Do they use the appropriate logging level?