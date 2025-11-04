<!-- # Pancakes -->
<p align="center" width="100%">
    <img width="90%" src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/1bcfb2729fd94f57fc03af56f8436bcbe70609fb_frame_2.svg"><br>
</p>
<center>The website for the Hack Club YSWS Pancakes!</center>

## Development

First, clone the repository and navigate into it.

```bash
git clone https://github.com/hackclub/pancakes
cd pancakes
```
Next, before running, install dependencies.

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Finally, you'll want to use the following command to run it in development mode.

```bash
fastapi dev main.py
```

Otherwise, if you are instead intending on running your own instance (though I don't really see a need for it...), run the following command:

```bash
fastapi run main.py
```

You should be good to go! PRs are very appreciated!
