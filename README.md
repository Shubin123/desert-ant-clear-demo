# Clear browser demo

[Open the live demo](https://shubin123.github.io/desert-ant-clear-demo/)

Denoise, reduce reverberation, and normalize speech loudness with Desert Ant Labs.

Powered by [Desert Ant Labs](https://desertant.com) 🐜. The model, weights, and SDK are by Desert Ant Labs B.V.; this independent demo is maintained by Shubin123. See [ATTRIBUTION.md](ATTRIBUTION.md) and the [SDK license](https://license.desertant.com/1.0).

## Run locally

Serve the site directory over HTTP:

```sh
python3 -m http.server 8080 --directory site
```

Open http://localhost:8080. No build step or backend is required. The SDK and runtimes use a pinned import map; downloads occur on first inference. Microphone capture requires localhost or HTTPS. SDK usage telemetry contains no input or output content.

## Deployment

The GitHub Actions workflow publishes the site directory to GitHub Pages on pushes to main. Choose GitHub Actions as the Pages source.

## Upstream

- [SDK documentation](https://github.com/Desert-Ant-Labs/desert-ant-core/blob/main/docs/models/clear.md)
- [Original model](https://huggingface.co/desert-ant-labs/clear)
- [Desert Ant Labs](https://desertant.com)

Upload a short speech recording or record a sample. Compare the original with the enhanced WAV.

