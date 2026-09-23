## Hi, I'm Varun 👋

Software engineer with an MS in Computer Science from Portland State University. I build backend
systems and the infrastructure around LLMs: agents that operate real software, retrieval
pipelines, and the APIs underneath them. I care most about making them deterministic, testable,
and safe to run.

### Featured projects

**Computer-Use Automation System** · *in progress*
An LLM learns a task in a legacy web UI once and saves it as a typed capability artifact. The
artifact is then replayed deterministically with no LLM in the loop. Perception runs on the
accessibility tree, and locators are validated at record time. Replay errors are classified so
that a business outcome is never mistaken for a failure, and a human can take over the live
session.
`Python` `Playwright` `Chrome DevTools Protocol` `Pydantic` `Flask` `pytest`

**[APIverse](https://github.com/tago893/APIverse-test)**
An API hub for students: placeholder image and text, weather, gradebook, and Star Wars endpoints
behind API-key authentication. It pairs a Flask gateway with a FastAPI backend and runs on Google
Cloud Run with Cloud Datastore.
`Python` `FastAPI` `Flask` `Docker` `GCP`

**[Image Retrieval](https://github.com/tago893/image-retrieval)**
Content-based image search on Caltech101. A fine-tuned ResNet-50 (92.4% top-5 accuracy) produces
embeddings, which are indexed with FAISS and served through a
[live Streamlit demo](https://image-retrieval-jwdpxketfpngmusvgxw8rg.streamlit.app/).
`PyTorch` `FAISS` `Streamlit`

<!-- Featured slot 4: add project here -->

<!-- Featured slot 5: add project here -->

### Tech

**Languages** · Python, Java, SQL, JavaScript
**Backend** · FastAPI, Flask, Django, Spring Boot, REST APIs
**AI / ML** · LLM agents and tool calling, RAG, PyTorch, FAISS
**Infra & testing** · Docker, GCP, AWS, Playwright, pytest, Git
