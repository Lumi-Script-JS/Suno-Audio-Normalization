# Suno Audio Normalize Pro

A professional, web-based audio normalization tool designed to help you easily adjust LUFS (Loudness Units relative to Full Scale), True Peak, and LRA (Loudness Range) of your audio files directly in your browser.

## Features

- **In-Browser Processing:** All audio processing is done locally in your browser using WebAssembly (`@ffmpeg/ffmpeg`). Your files are never uploaded to a server, ensuring absolute privacy.
- **LUFS Target:** Set your desired integrated loudness level (e.g., -14 LUFS for streaming platforms).
- **True Peak Target:** Prevent clipping by setting a maximum True Peak level.
- **LRA Adjustment:** Modify the loudness range (dynamics) of your audio.
- **Dynamic & Linear Normalization:** Choose between dynamic (compressing/expanding dynamics) or linear (straight volume adjustment) normalization based on your needs.
- **Modern UI:** Built with React, Tailwind CSS, and Radix UI primitives for a sleek and responsive user experience.

## Deploy
[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/Lumi-Script-JS/Suno-Audio-Normalization/)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Lumi-Script-JS/Suno-Audio-Normalization)

## Usage

1. Open the application in your browser.
2. Upload your audio file.
3. Configure your desired target LUFS, True Peak, and LRA settings, or use the provided presets.
4. Click "Process Audio".
5. Wait for the processing to finish and review the final output measurements.
6. Download your normalized audio file.

## Technologies

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [FFmpeg (WebAssembly)](https://ffmpegwasm.netlify.app/)
- [Radix UI](https://www.radix-ui.com/)
- [Lucide Icons](https://lucide.dev/)

## License

This project is open-source and available under the MIT License.
