# Learning SvelteKit

I've been building a generative AI app at work with Vanilla JS, but the code's getting really bloated and hard to manage.

So, I've started learning SvelteKit to fix that. SvelteKit looks like the easiest JavaScript framework to pick up, so I'm going to learn it.

## App

### Image Recognition

#### Gemini 2.0 Flash

<img src="docs/image_recognition_gemini.jpg" width=600>

#### TensorFlow.js mobilenet

<img src="docs/image_recognition_tf.jpg" width=600>

### Object Detection

#### Gemini 2.0 Flash

<img src="docs/object_detection_gemini.jpg" width=600>

#### TensorFlow.js coco-ssd

<img src="docs/object_detection_tf.jpg" width=600>

## Code

To run the app in the development environment,
```
$ cd app
$ npm run dev
```

To build the app,
```
$ cd app
$ npm run build
```

## TODO

Working with the following:
- OpenAI TTS
- OpenCV.js
- RAG (sqlite-vec)

## References

- [Tutorial](https://svelte.dev/tutorial/kit/introducing-sveltekit)
- [Creating a project](https://svelte.dev/docs/kit/creating-a-project)
- [Static Site Deployment](https://svelte.dev/docs/kit/adapter-static)
- [Building an app](https://svelte.dev/docs/kit/building-your-app)
- [TensorFlow.js](https://www.tensorflow.org/js)
