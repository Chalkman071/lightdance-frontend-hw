# Lightdance Frontend Homeworks

## Environment setup

1. Install [uv](https://docs.astral.sh/uv/), a python project manager.

2. Setup venv

```bash
uv venv
```

3. Install dependencies

```bash
uv sync
```

To run your script, use:
```bash
uv run <script_name>
```

## HW1
#### Goal
Learn how to use asyncio and aiohttp to fetch remote resources asynchronously.

#### Tutorials
[Python asyncio 從不會到上路](https://myapollo.com.tw/blog/begin-to-asyncio/) (recommended)

[Getting Started With Async Features in Python](https://realpython.com/python-async-features/) (recommended)

[Asyncio in Python - Full Tutorial](https://youtu.be/Qb9s3UiMSTA?si=VDx9KZ7kcWxArxSK) (optional)

[Intro to async Python | Writing a Web Crawler](https://youtu.be/ftmdDlwMwwQ?si=M6CicFzyT14TadTT)(~5:58)(optional)

#### Requirements
Fetch the content of the following URLs asynchronously and save them locally in `HW1/main.py`.
- https://example.com -> example.html
- https://github.com/NTUEELightDance/LightDance-Editor/releases/latest/download/editor-blender.zip -> editor-blender.zip

#### Examples in lightdance editor

- Simple example: `editor-blender/client/__init__.py`
- Complicated example: `editor-blender/operators/async_core/__init__.py`
