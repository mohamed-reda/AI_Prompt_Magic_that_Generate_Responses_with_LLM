# AI Prompt Magic: Generating Responses with Language Models

Welcome to the AI Prompt Magic repository! This repository hosts three exciting projects that showcase the power of
language models in generating responses to various prompts. Explore these projects to witness the magic of AI in action.

## Project 1: AI Tweet

The **AI Tweet** project demonstrates the capabilities of AI in composing tweets based on given prompts. Utilizing
OpenAI's language model, this project crafts engaging tweets with just a few instructions.

## Project 2: Magic of AI

In the **Magic of AI** project, we delve into the realm of childhood imagination and curiosity. Witness how AI
interprets prompts as if through the eyes of a child, unveiling the wonders of the world with innocence and creativity.

## Project 3: AI Prompt Magic

**AI Prompt Magic** showcases the versatility of language models in responding to various types of prompts. Explore how
AI generates responses to comma-separated lists and structured queries, providing insightful and accurate information.

Each project offers a unique perspective on the capabilities of language models and their applications in generating
text-based content. Dive into the projects to explore the possibilities of AI prompt magic!


------------

**Running streamlit:**

To launch streamlit, use the following command:

```bash
python -m streamlit.cli run app.py
```

----------------


**Running Jupyter Notebook:**

To launch the Jupyter Notebook server, use the following command:

```bash
jupyter notebook
```

(Note: Use Control-C to stop the server)

---

**Installing Dependencies:**

Ensure that the required dependencies are installed by running the following commands:

```bash
pip install -r requirements.txt
python -m pip install jupyter
```

---

**Memory Profiling:**

To profile the memory usage, decorate your Python script with `@memory_profiler.profile` and run the following command:

```bash
python -m memory_profiler main.py
```

---

**Line Profiling:**

For line-level profiling, use the `line_profiler_pycharm` package. Decorate your Python script with `@profile` and
execute the following command:

```bash
python -m line_profiler main.py.lprof > results.txt
```

Make sure to replace `main.py` with the appropriate filename.