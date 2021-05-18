Python-based spaceship dodging game in terminal using curses (windows-curses), no pygame required.

> Windows version of Python doesn't come with built-in module `curses`, but you can work around by using `windows-curses`

### Linux

```bash
# unit test for linux
conda env create -f environment.yml -n spaceship # env name
# OR create a new env from scratch
conda create -n spaceship python
conda activate spaceship
# run the program
python test.py --canvas_height 30 --canvas_width 30 --diff_level 2
```

[youtube link to demo](https://youtu.be/x4g7NjKTjqw)

<iframe width="560" height="315" src="https://www.youtube.com/embed/x4g7NjKTjqw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></a>



### Windows

```bash
# unit test for windows
conda env create -f environment_win.yml -n spaceship # env name
conda activate spaceship
# run the program
python test.py --canvas_height 30 --canvas_width 30 --diff_level 2
```

demo

![](https://raw.githubusercontent.com/LuchaoQi/Spaceship/master/demo/demo_win.gif)

