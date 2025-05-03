## 12TweleveLAbs

 Powered with text-to-speech, voice conversion, and audio generation. Some tutorials would just call an API like ElevenLabs', but not us! Instead of external API services, you'll self-host three AI models (StyleTTS2, Seed-VC, and Make-An-Audio) from GitHub, fine-tune them to specific voices, then containerize them with Docker and expose inference endpoints via FastAPI. The AI backend will be built using Python and PyTorch. You'll create a Next.js application where users can use the AI models to generate audio, and also switch between voices and view previously generated audio files, stored in an S3 bucket. The project includes user authentication, a credit system, and an Inngest queue to prevent overloading of the server hosting the AI models. The web application is built on the T3 Stack with Next.js, React, Tailwind, and Auth.js. Follow along for the entire process from development to deployment.


 


