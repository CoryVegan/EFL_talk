This repository holds the source code for my presentation on
["Do disaggregated electricity bills really help people to save energy?"](http://www3.imperial.ac.uk/newsandeventspggrp/imperialcollege/administration/energyfutureslab/eventssummary/event_5-4-2016-9-1-7)
presented as part of the Imperial College Energy Futures Lab seminars.

If you just want to view this presentation, just point your browser to
[http://jackkelly.github.io/EFL_talk](http://jackkelly.github.io/EFL_talk)

You do not need to clone this repository just to view the
presentation.

This presentation is based on my paper:
"[Does disaggregated electricity feedback reduce domestic electricity consumption? A systematic review of the literature](http://arxiv.org/abs/1605.00962)",
In *3rd International NILM Workshop*, Vancouver, Canada, 14-15 May
2016.

---

If you want to run this presentation locally then here is one way to
do that (on Ubuntu):

```
sudo apt-get install nodejs-legacy npm
sudo npm install -g grunt-cli http-server bower
bower install
```

Then run `http-server -c-1` from the base directory of this project.
And point your browser to `http://localhost:8080`.

# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
