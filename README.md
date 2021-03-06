# Simple Git versioning for Sketch

Read more in [the story on Medium](https://medium.com/cloudaper/simple-git-versioning-for-sketch-5d77df01571e).

Any feedback or even a pull request welcomed!

## How to

1. Set up a new repository for Sketch files
2. Install Python 3 _(optional)_
3. Download the [pre-commit](https://raw.githubusercontent.com/cloudaper/sketch-git-hooks/master/pre-commit), [post-merge](https://raw.githubusercontent.com/cloudaper/sketch-git-hooks/master/post-merge) and [post-checkout](https://raw.githubusercontent.com/cloudaper/sketch-git-hooks/master/post-checkout) hooks from this repository
4. Copy them into .git/hooks folder in your repository
5. Make the scripts executable: run `chmod +x .git/hooks/pre-commit .git/hooks/post-merge .git/hooks/post-checkout` in your repository
6. And try to commit some Sketch files!
