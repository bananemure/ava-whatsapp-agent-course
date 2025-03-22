<p align="center">
        <img alt="logo" src="img/ava_final_design.gif" width=1000 />
    <h1 align="center">📱 Ava 📱</h1>
    <h3 align="center">Turning the Turing Test into a WhatsApp Agent</h3>
</p>

<p align="center">
    <img alt="logo" src="img/whatsapp_logo.png" width=100 />
</p>

## Table of Contents

- [Course Overview](#course-overview)
- [Who is this course for?](#who-is-this-course-for)
- [What you'll get out of this course](#what-youll-get-out-of-this-course)
- [Course syllabus](#course-syllabus)
- [Getting started](#getting-started)
- [The tech stack](#the-tech-stack)
- [Contributors](#contributors)
- [License](#license)

## Course Overview

What happens when [two ML Engineers](#contributors) with a love for sci-fi movies team up? 🤔

You get **Ava**, a Whatsapp agent that can engage with users in a "realistic" way, inspired by the great film [Ex Machina](https://www.imdb.com/es-es/title/tt0470752/). Ok, you won't find a fully sentient robot here, but you **will** have some pretty interesting Whatsapp conversations.

By the end of this course, you'll have built your own Ava too, capable of:


* Receiving and sending Whatsapp messages 📲
* Understanding your voice 🗣️
* Recognizing your images 🖼️
* Sending voice notes back 🎤
* Sharing updates about its "daily activities" 🚣
* Sending you images of its current activities 🖼️

>You can think of it as a modern reinterpretation of the Turing Test 🤣

Excited? Let's get started! 

---

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td width="20%" style="border: none;">
      <a href="https://theneuralmaze.substack.com/" aria-label="The Neural Maze">
        <img src="https://avatars.githubusercontent.com/u/151655127?s=400&u=2fff53e8c195ac155e5c8ee65c6ba683a72e655f&v=4" alt="The Neural Maze Logo" width="150"/>
      </a>
    </td>
    <td width="80%" style="border: none;">
      <div>
        <h2>📬 Stay Updated</h2>
        <p><b><a href="https://theneuralmaze.substack.com/">Join The Neural Maze</a></b> and learn to build AI Systems that actually work, from principles to production. Every Wednesday, directly to your inbox. Don't miss out!
</p>
      </div>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://theneuralmaze.substack.com/">
    <img src="https://img.shields.io/static/v1?label&logo=substack&message=Subscribe Now&style=for-the-badge&color=black&scale=2" alt="Subscribe Now" height="40">
  </a>
</p>

---

## Who is this course for?

This course is for Software Engineers, ML Engineers, and AI Engineers who want to level up by building complex end-to-end apps. It's not just a basic "Hello World" tutorial—it's a deep dive into making a production-ready WhatsApp agent.

## What you'll get out of this course

* Build a fully working WhatsApp agent you can chat with on your phone
* Get a solid understanding of how to build LangGraph workflows
* Set up a long-term memory system using Qdrant as a Vector Database
* Use Groq models to power AI Agent responses
* Implement STT systems using Whisper
* Implement TTS systems using ElevenLabs
* Generate high-quality images using diffusion models, like FLUX models
* Process images using VLM models, like llama-3.2-vision
* Create chat interfaces using Chainlit
* Deploy agentic applications to Cloud Run
* Connect agentic applications to the WhatsApp API

## Course syllabus

<table style="width:100%; border-collapse: collapse;">
  <tr>
    <th style="border: 1px solid #ddd; padding: 8px; text-align: center;">Lesson Number</th>
    <th style="border: 1px solid #ddd; padding: 8px; text-align: center;">Lesson</th>
    <th style="border: 1px solid #ddd; padding: 8px; text-align: center;">Video</th>
  </tr>
  <tr>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">1</td>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;"><a href="https://theneuralmaze.substack.com/p/meet-ava-the-whatsapp-agent">Project overview</a></td>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;"><a href="https://youtu.be/u5y06cFK2WA?si=RCx__sJNtr2DYf0U"><img src="img/video_thumbnails/thumbnail_1_play.png" alt="Thumbnail 1" style="width:300px;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">2</td>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;"><a href="https://theneuralmaze.substack.com/p/dissecting-avas-brain">Dissecting Ava's brain</a></td>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;"><a href="https://youtu.be/nTsLL3htkCU?si=aSmSkpL-U3rzw9Za"><img src="img/video_thumbnails/thumbnail_2_play.png" alt="Thumbnail 2" style="width:300px;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">3</td>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;"><a href="https://theneuralmaze.substack.com/p/can-agents-get-nostalgic-about-the">Unlocking Ava's memories</a></td>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;"><a href="https://youtu.be/oTHqYEpdFXg?si=MXEvjUJ8Xbc6h9l2"><img src="img/video_thumbnails/thumbnail_3_play.png" alt="Thumbnail 3" style="width:300px;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">4</td>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;"><a href="https://theneuralmaze.substack.com/p/the-ultimate-ai-voice-pipeline">Giving Ava a Voice</a></td>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;"><a href="https://youtu.be/RNmwvMjtIt0"><img src="img/video_thumbnails/thumbnail_4_play.png" alt="Thumbnail 4" style="width:300px;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">5</td>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;"><a href="https://theneuralmaze.substack.com/p/reading-images-drawing-dreams-vlms">Ava learns to see</a></td>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;"><a href="https://youtu.be/LS7k-XFBbeo"><img src="img/video_thumbnails/thumbnail_5_play.png" alt="Thumbnail 5" style="width:300px;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">6</td>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;"><a href="https://theneuralmaze.substack.com/p/connecting-an-ai-agent-to-whatsap">Ava installs Whatsapp</a></td>
    <td style="border: 1px solid #ddd; padding: 8px; text-align: center;"><a href="https://youtu.be/dFsI4lnUkKo"><img src="img/video_thumbnails/thumbnail_6_play.png" alt="Thumbnail 6" style="width:300px;"></td>
  </tr>
</table>

| Lesson Number | Lesson | Video | Description |
|---------------|--------|-------|-------------|
| 1 | [Project overview](https://theneuralmaze.substack.com/p/meet-ava-the-whatsapp-agent) | <a href="https://youtu.be/u5y06cFK2WA?si=RCx__sJNtr2DYf0U"><img src="img/video_thumbnails/thumbnail_1_play.png" alt="Thumbnail 1" width="300"></a> | Understand the project architecture and the tech stack. |
| 2 | [Dissecting Ava's brain](https://theneuralmaze.substack.com/p/dissecting-avas-brain) | <a href="https://youtu.be/nTsLL3htkCU?si=aSmSkpL-U3rzw9Za"><img src="img/video_thumbnails/thumbnail_2_play.png" alt="Thumbnail 2" width="300"></a> | Learn the basics of LangGraph and implement complex workflows using this framework. |
| 3 | [Unlocking Ava's memories](https://theneuralmaze.substack.com/p/can-agents-get-nostalgic-about-the) | <a href="https://youtu.be/oTHqYEpdFXg?si=MXEvjUJ8Xbc6h9l2"><img src="img/video_thumbnails/thumbnail_3_play.png" alt="Thumbnail 3" width="300"></a> | Build a short-term memory system for graph state persistence and chat history. Also, implement a long-term memory system using Qdrant. |
| 4 | [Giving Ava a Voice](https://theneuralmaze.substack.com/p/the-ultimate-ai-voice-pipeline) | <a href="https://youtu.be/RNmwvMjtIt0"><img src="img/video_thumbnails/thumbnail_4_play.png" alt="Thumbnail 4" width="300"></a> | Build a STT and a TTS pipeline to make Ava process input and output audio. |
| 5 | [Ava learns to see](https://theneuralmaze.substack.com/p/reading-images-drawing-dreams-vlms) | <a href="https://youtu.be/LS7k-XFBbeo"><img src="img/video_thumbnails/thumbnail_5_play.png" alt="Thumbnail 5" width="300"></a> | Understand how to process images using VLM models. Implement an image generation pipeline using FLUX models. |
| 6 | [Ava installs Whatsapp](https://theneuralmaze.substack.com/p/connecting-an-ai-agent-to-whatsap) | <a href="https://youtu.be/dFsI4lnUkKo"><img src="img/video_thumbnails/thumbnail_6_play.png" alt="Thumbnail 6" width="300"></a> | Connect Ava to WhatsApp. Learn how to deploy a LangGraph application to Google Cloud Run. |

---

## How much is this going to cost me?

The awesome thing about this project is you can run it on your own computer for free! The free tiers from Groq, ElevenLabs, Qdrant Cloud, and Together AI are more than enough to get you going.

If you want to try it out on Google Cloud Run, you can get a free account and get $300 in free credits. Even if you've already used up your free credits, Cloud Run is super cheap - so it will take just a buck or two for your experiments.

---

## Getting started

Before you begin the course, there are a few things you need to do. Creating a virtual environment, installing the dependencies, creating a `.env` file, setting up accounts with the services we'll use, etc.

All of this is detailed in the following doc: [GETTING STARTED.md](docs/GETTING_STARTED.md).

> Make sure you follow the instructions in the doc, as it's crucial for the course to work.

Once you have everything set up, it's time to run the project locally. This is the best way to check that everything is working before moving on to the next lesson.

To run the project locally, we have created a [Makefile](Makefile). Use the command `ava-run` to start the project.

```bash
make ava-run
```

This command will start a Docker Compose application with three services:

* A Qdrant Database (http://localhost:6333/dashboard)
* A Chainlit interface (http://localhost:8000)
* A FastAPI application (http://localhost:8080/docs)

The FastAPI application is necessary for the WhatsApp integration, but that's something we will cover in Lesson 6. So, for now,
you can ignore it. Simply click the link to the Chainlit interface to start interacting with Ava.

You should see something like this:

![Ava Chainlit](img/ava_chainlit.png)

Now that you have everything running, it's time to move on to the first lesson, where you'll understand the architecture behind Ava.

---

## The tech stack

<table>
  <tr>
    <th>Technology</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><img src="img/groq_logo.png" width="100" alt="Groq Logo"/></td>
    <td>Powering the project with Llama 3.3, Llama 3.2 Vision, and Whisper. Groq models are awesome (and fast!!)</td>
  </tr>
  <tr>
    <td><img src="img/qdrant_logo.png" width="100" alt="Qdrant Logo"/></td>
    <td>Serving as the long-term database, enabling our agent to recall details you shared months ago.</td>
  </tr>
  <tr>
    <td><img src="img/cloud_run_logo.png" width="100" alt="Cloud Run Logo"/></td>
    <td>Deploying your containers easily to Google Cloud Platform</td>
  </tr>
  <tr>
    <td><img src="img/langgraph_logo.png" width="100" alt="LangGraph Logo"/></td>
    <td>Learn how to build production-ready LangGraph workflows</td>
  </tr>
  <tr>
    <td><img src="img/elevenlabs_logo.png" width="100" alt="ElevenLabs Logo"/></td>
    <td>Amazing TTS models</td>
  </tr>
  <tr>
    <td><img src="img/together_logo.png" width="100" alt="Together AI Logo"/></td>
    <td>Behind Ava's image generation process</td>
  </tr>
</table>


## Contributors

<table>
  <tr>
    <td align="center"><img src="https://github.com/MichaelisTrofficus.png" width="100" style="border-radius:50%;"/></td>
    <td>
      <strong>Miguel Otero Pedrido | Senior ML / AI Engineer </strong><br />
      <i>Founder of The Neural Maze. Rick and Morty fan.</i><br /><br />
      <a href="https://www.linkedin.com/in/migueloteropedrido/">LinkedIn</a><br />
      <a href="https://www.youtube.com/@TheNeuralMaze">YouTube</a><br />
      <a href="https://theneuralmaze.substack.com/">The Neural Maze Newsletter</a>
    </td>
  </tr>
  <tr>
    <td align="center"><img src="https://github.com/jesuscopado.png" width="100" style="border-radius:50%;"/></td>
    <td>
      <strong>Jesús Copado | Senior ML / AI Engineer </strong><br />
      <i>Equal parts cinema fan and AI enthusiast.</i><br /><br />
      <a href="https://www.youtube.com/@jesuscopado-en">YouTube</a><br />
      <a href="https://www.linkedin.com/in/copadojesus/">LinkedIn</a><br />
    </td>
  </tr>
</table>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td width="20%" style="border: none;">
      <a href="https://theneuralmaze.substack.com/" aria-label="The Neural Maze">
        <img src="https://avatars.githubusercontent.com/u/151655127?s=400&u=2fff53e8c195ac155e5c8ee65c6ba683a72e655f&v=4" alt="The Neural Maze Logo" width="150"/>
      </a>
    </td>
    <td width="80%" style="border: none;">
      <div>
        <h2>📬 Stay Updated</h2>
        <p><b><a href="https://theneuralmaze.substack.com/">Join The Neural Maze</a></b> and learn to build AI Systems that actually work, from principles to production. Every Wednesday, directly to your inbox. Don't miss out!
</p>
      </div>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://theneuralmaze.substack.com/">
    <img src="https://img.shields.io/static/v1?label&logo=substack&message=Subscribe Now&style=for-the-badge&color=black&scale=2" alt="Subscribe Now" height="40">
  </a>
</p>