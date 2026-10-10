Kisan Sahulat - کسان سہولت

An AI farm advisor for Pakistani farmers, built for the Agricultural Operations module at SEECS, NUST.

Team: Tooba, Areeba

What it does
- Land:feasibility check from live weather, air quality (smog proxy) and river flow (flood signal)
- Crop: disease and pest diagnosis with advice (active ingredients only, no brands or doses)
- Money: Monte Carlo profit simulation (P10 / median / P90, chance of loss) and a fair-price check against middlemen
- Guidance: multilingual advisor with voice, grounded on the farm report
- Languages: Urdu, English, Punjabi, Sindhi, Saraiki, Pashto, Balochi, Brahui

Demo
- 🎥 Screen recording: coming soon
- 📊 Slides: coming soon
- 🔗 Live demo:(https://c4f882605bd326a00b.gradio.live/)

 ata sources
- Open-Meteo (weather, air quality, river discharge)

Limitations
- The pollution score is an AQI proxy, not rainwater pH.
- Crop and cost tables are prototype assumptions, not official figures.
- The flood signal is indicative only.
- Punjabi, Sindhi, Saraiki, Pashto, Balochi and Brahui translations are weaker than Urdu, and the voices are approximate.
- Advice does not replace a local agriculture officer.

Tech
Python, Google Colab, Gradio, Open-Meteo, gTTS / edge-tts, LLM API for chat and translation.
